# Graph Report - .  (2026-07-16)

## Corpus Check
- cluster-only mode — file stats not available

## Summary
- 60 nodes · 46 edges · 26 communities (4 shown, 22 thin omitted)
- Extraction: 93% EXTRACTED · 7% INFERRED · 0% AMBIGUOUS · INFERRED: 3 edges (avg confidence: 0.9)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- AI and Platform Architecture
- National Immunization Systems
- Immunization Data Management
- Health Information Networks
- Knowledge Object Documentation
- Knowledge Base Standards
- Project Logs and Memories
- Change History
- Knowledge Base Architecture
- Quality Standards
- Glossary of Terms
- Editorial Guidelines
- Immunobiological Data Model
- BCG Vaccine Documentation
- Vaccine Data Model
- Knowledge Base Map
- Knowledge Object Structure
- Metadata Standards
- Knowledge Object Framework
- National Immunization Program
- Object Taxonomy
- Project Backlog
- Visual Identity Guidelines
- Core Knowledge Base
- Immunization Trail Homepage
- Immunization Trail Documentation

## God Nodes (most connected - your core abstractions)
1. `Arquitetura da Trilha` - 11 edges
2. `Calendário Nacional de Vacinação` - 7 edges
3. `Visão do Projeto` - 7 edges
4. `Sistema de Informação do Programa Nacional de Imunizações (SI-PNI)` - 7 edges
5. `Home Versão 1` - 4 edges
6. `Jornada do Usuário` - 4 edges
7. `Sistemas de Informação` - 3 edges
8. `Rede de Frio` - 3 edges
9. `AI Context` - 3 edges
10. `Princípios da Plataforma` - 3 edges

## Surprising Connections (you probably didn't know these)
- `Imunobiológicos` --conceptually_related_to--> `Calendário Nacional de Vacinação`  [INFERRED]
  conhecimento/imunobiologicos/README.md → clinico/CALENDARIO_NACIONAL_DE_VACINACAO.md
- `Manifesto da Base de Conhecimento` --references--> `Calendário Nacional de Vacinação`  [EXTRACTED]
  conhecimento/MANIFESTO_DA_BASE.md → clinico/CALENDARIO_NACIONAL_DE_VACINACAO.md
- `Diário de Bordo` --conceptually_related_to--> `Memórias da Trilha`  [INFERRED]
  docs/DIARIO_DE_BORDO.md → docs/MEMORIAS_DA_TRILHA.md
- `Roadmap` --references--> `Arquitetura da Trilha`  [EXTRACTED]
  docs/ROADMAP.md → docs/arquitetura/ARQUITETURA_DA_TRILHA.md
- `Roadmap` --references--> `Visão do Projeto`  [EXTRACTED]
  docs/ROADMAP.md → docs/VISAO_DO_PROJETO.md

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Definição da Experiência do Usuário** — docs_home_versao_1, docs_jornada_do_usuario, docs_publico_e_cenarios_de_uso [INFERRED 0.90]
- **Visão Estratégica do Projeto** — docs_visao_do_projeto, docs_principios_da_plataforma, docs_roadmap, docs_ai_context [INFERRED 0.90]
- **Documentação de Arquitetura** — docs_arquitetura_arquitetura_da_trilha, docs_arquitetura_arquitetura_da_base_de_conhecimento, docs_arquitetura_arquitetura_do_grafo_semantico, docs_arquitetura_arquitetura_dos_agentes_ia, docs_arquitetura_fluxo_de_atualizacao_da_base, docs_arquitetura_roadmap_da_arquitetura [EXTRACTED 1.00]
- **Fluxo de Dados de Vacinação** — conhecimento_sipni_sipni, conhecimento_sipni_rnds, conhecimento_sipni_rqdv [EXTRACTED 0.85]
- **Estrutura da Base de Conhecimento** — conhecimento_readme, conhecimento_manifesto_da_base, conhecimento_mapa_da_base [EXTRACTED 0.90]
- **Sistemas Centrais da Trilha de Imunização** — si_pni, e_sus_pec, rnds [EXTRACTED 0.95]
- **Knowledge Base Structural Framework** — conhecimento_arquitetura_da_base, conhecimento_modelo_objeto_de_conhecimento, conhecimento_padrao_de_metadados, conhecimento_taxonomia_dos_objetos, conhecimento_criterios_de_qualidade [EXTRACTED 1.00]
- **Immunization Domain Entities** — conhecimento_programa_nacional_imunizacoes_pni, conhecimento_imunobiologicos_vacinas_bcg_bcg [EXTRACTED 1.00]

## Communities (26 total, 22 thin omitted)

### Community 0 - "AI and Platform Architecture"
Cohesion: 0.27
Nodes (13): AI Context, Arquitetura da Base de Conhecimento, Arquitetura da Trilha, Arquitetura do Grafo Semântico, Arquitetura dos Agentes de IA, Fluxo de Atualização da Base, Roadmap da Arquitetura, Home Versão 1 (+5 more)

### Community 1 - "National Immunization Systems"
Cohesion: 0.27
Nodes (10): Calendário Nacional de Vacinação, Imunobiológicos, Manifesto da Base de Conhecimento, Programa Nacional de Imunizações (PNI), Sistemas de Informação, e-SUS PEC, Programa Nacional de Imunizações, Rede de Frio (+2 more)

### Community 2 - "Immunization Data Management"
Cohesion: 0.25
Nodes (8): Calendário Nacional de Vacinação, e-SUS PEC, Imunobiológicos, Programa Nacional de Imunizações (PNI), Rede de Frio, Rede Nacional de Dados em Saúde (RNDS), Rastreador de Qualidade dos Dados Vacinais (RQDV), Sistema de Informação do Programa Nacional de Imunizações (SI-PNI)

### Community 3 - "Health Information Networks"
Cohesion: 0.50
Nodes (4): Rede de Frio, e-SUS PEC, RNDS, SI-PNI

## Knowledge Gaps
- **42 isolated node(s):** `Changelog`, `Trilha de Imunização README`, `Arquitetura da Base de Conhecimento`, `Critérios de Qualidade`, `Guia Editorial` (+37 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **22 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What connects `Changelog`, `Trilha de Imunização README`, `Arquitetura da Base de Conhecimento` to the rest of the system?**
  _42 weakly-connected nodes found - possible documentation gaps or missing edges._