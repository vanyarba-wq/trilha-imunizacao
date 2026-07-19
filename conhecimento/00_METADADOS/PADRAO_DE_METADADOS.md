# 🧬 Padrão de Metadados da Trilha de Imunização

Todo Objeto de Conhecimento da Trilha deverá iniciar com o seguinte bloco de metadados.

```yaml
id:
titulo:

dominio:
categoria:
subcategoria:

descricao:

publico_alvo:
  - Profissionais de Saúde
  - Estudantes
  - Professores
  - Gestores
  - Pesquisadores

nivel_conhecimento:
  - Básico
  - Intermediário
  - Avançado

palavras_chave:

objetos_relacionados:

documentos_oficiais:

sistemas_relacionados:

estruturas_relacionadas:

contextos_aplicacao:
  - Atenção Primária
  - Hospital
  - CRIE
  - Saúde Indígena
  - Rede de Frio
  - Campanhas
  - Extramuros

ultima_atualizacao:

versao:

status:
  - Em construção
  - Em revisão
  - Publicado

autor:

revisado_por:
```

---

## Observações

- Nem todos os campos serão obrigatórios em todos os Objetos de Conhecimento.
- Os metadados têm como finalidade facilitar a organização da Base de Conhecimento, a navegação da plataforma e a recuperação de informações por mecanismos de busca e Inteligência Artificial.
- Sempre que possível, os relacionamentos deverão apontar para Objetos de Conhecimento existentes na Trilha, evitando duplicação de conteúdo.
