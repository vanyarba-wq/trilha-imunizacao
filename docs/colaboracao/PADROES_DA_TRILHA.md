# Padrões da Trilha de Imunização

## Objetivo

Este documento define os padrões utilizados na Trilha de Imunização para garantir organização, consistência e facilidade de manutenção do projeto.

---

## 1. Princípios Gerais

- Uma única fonte de verdade para cada informação.
- Evitar duplicação de conteúdo.
- Todo conhecimento deve ser reutilizável.
- Alterações devem preservar o histórico do projeto.
- A documentação deve ser compreensível para pessoas e agentes de IA.

---

## 2. Estrutura do Projeto

Cada pasta possui uma responsabilidade específica.

Exemplo:

- `assets/` → Recursos visuais e arquivos estáticos.
- `biblioteca/` → Conteúdo técnico de imunização.
- `clinico/` → Assistente Clínico.
- `conhecimento/` → Base de Conhecimento e Objetos de Conhecimento.
- `docs/` → Documentação oficial do projeto.
- `docs/arquitetura/` → Arquitetura da plataforma.
- `docs/colaboracao/` → Governança e colaboração entre humanos e IA.
- `indicadores/` → Indicadores e análises.
- `sistemas/` → Assistente de Sistemas.
- `treinamento/` → Conteúdo educacional.

---

## 3. Nomenclatura

Os arquivos devem utilizar:

- LETRAS MAIÚSCULAS
- Separação por underline (_)
- Sem espaços
- Sem acentos

Exemplo:

**Correto**

```
VISAO_DO_PROJETO.md
```

**Incorreto**

```
visao projeto.md
```

---

## 4. Objetos de Conhecimento

Todo novo conhecimento deve ser criado como um Objeto de Conhecimento.

Cada objeto deve conter:

- título
- descrição
- assunto
- fonte
- data
- versão
- palavras-chave
- relacionamentos

---

## 5. Documentação

Cada documento deve possuir:

- objetivo
- conteúdo principal
- documentos relacionados
- navegação (anterior e próximo)

---

## 6. Colaboração

Antes de criar novos documentos:

- verificar se o conteúdo já existe;
- atualizar documentos existentes sempre que possível;
- evitar duplicação de informações.

---

## 7. Agentes de IA

Todos os agentes devem seguir estes padrões.

Qualquer novo agente deverá utilizar esta documentação como referência antes de produzir conteúdo.

---

## 8. Governança

A Trilha de Imunização é desenvolvida de forma colaborativa entre especialistas humanos e agentes de Inteligência Artificial.

Cada colaborador possui responsabilidades definidas em documentos específicos da pasta `docs/colaboracao`.

Toda contribuição deve respeitar:

- Arquitetura da Trilha;
- Padrões da Base de Conhecimento;
- Modelo de Objetos de Conhecimento;
- Guia Editorial;
- Critérios de Qualidade;
- Fluxo de Atualização da Base.

O objetivo é garantir que a evolução do projeto ocorra de forma consistente, organizada e rastreável.

## Versão

Versão 1.0