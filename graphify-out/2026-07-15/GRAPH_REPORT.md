# Graph Report - .  (2026-07-15)

## Corpus Check
- cluster-only mode — file stats not available

## Summary
- 49 nodes · 23 edges · 31 communities (5 shown, 26 thin omitted)
- Extraction: 87% EXTRACTED · 13% INFERRED · 0% AMBIGUOUS · INFERRED: 3 edges (avg confidence: 0.87)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- National Vaccination Systems
- Health Information Networks
- User Roles and Journeys
- National Immunization Program
- Project Context and Logs
- Knowledge Object Documentation
- Project Changelog
- Knowledge Base Architecture
- Quality Criteria
- Project Glossary
- Editorial Guidelines
- Immunobiological Data Model
- BCG Vaccine Information
- Vaccine Data Model
- Knowledge Base Map
- Knowledge Object Template
- Metadata Standards
- Knowledge Object Structure
- Immunization Program Details
- Object Taxonomy
- Learning Path Architecture
- Project Backlog
- Visual Identity Guide
- Knowledge Core
- Platform Principles
- Project Roadmap
- Project Vision
- Immunization Path Home
- Immunization Coordinator Role
- Indigenous Health Professional
- Immunization Path Documentation

## God Nodes (most connected - your core abstractions)
1. `Calendário Nacional de Vacinação` - 7 edges
2. `Rede de Frio` - 4 edges
3. `Sistemas de Informação` - 3 edges
4. `Imunobiológicos` - 2 edges
5. `AI Context` - 2 edges
6. `Diário de Bordo` - 2 edges
7. `Jornada do Usuário` - 2 edges
8. `Técnica de Enfermagem` - 2 edges
9. `Memórias da Trilha` - 2 edges
10. `Manifesto da Base de Conhecimento` - 1 edges

## Surprising Connections (you probably didn't know these)
- `Imunobiológicos` --conceptually_related_to--> `Calendário Nacional de Vacinação`  [INFERRED]
  conhecimento/imunobiologicos/README.md → clinico/CALENDARIO_NACIONAL_DE_VACINACAO.md
- `Manifesto da Base de Conhecimento` --references--> `Calendário Nacional de Vacinação`  [EXTRACTED]
  conhecimento/MANIFESTO_DA_BASE.md → clinico/CALENDARIO_NACIONAL_DE_VACINACAO.md
- `Home Versão 1` --references--> `Rede de Frio`  [INFERRED]
  docs/HOME_VERSAO_1.md → conhecimento/REDE_DE_FRIO.md
- `Diário de Bordo` --conceptually_related_to--> `Memórias da Trilha`  [INFERRED]
  docs/DIARIO_DE_BORDO.md → docs/MEMORIAS_DA_TRILHA.md
- `Base de Conhecimento README` --references--> `Modelo de Objeto de Conhecimento`  [EXTRACTED]
  conhecimento/README.md → conhecimento/MODELO_OBJETO_CONHECIMENTO.md

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Documentação Base da Trilha** — docs_diario_de_bordo, docs_memorias_da_trilha, docs_roadmap, docs_backlog [EXTRACTED 0.95]
- **Personas do Projeto** — persona_tecnico_enfermagem, persona_enfermeiro, persona_coordenador_imunizacao, persona_profissional_dsei [EXTRACTED 1.00]
- **Estrutura da Base de Conhecimento** — conhecimento_readme, conhecimento_manifesto_da_base, conhecimento_mapa_da_base [EXTRACTED 0.90]
- **Sistemas Centrais da Trilha de Imunização** — si_pni, e_sus_pec, rnds [EXTRACTED 0.95]
- **Knowledge Base Structural Framework** — conhecimento_arquitetura_da_base, conhecimento_modelo_objeto_de_conhecimento, conhecimento_padrao_de_metadados, conhecimento_taxonomia_dos_objetos, conhecimento_criterios_de_qualidade [EXTRACTED 1.00]
- **Immunization Domain Entities** — conhecimento_programa_nacional_imunizacoes_pni, conhecimento_imunobiologicos_vacinas_bcg_bcg [EXTRACTED 1.00]

## Communities (31 total, 26 thin omitted)

### Community 0 - "National Vaccination Systems"
Cohesion: 0.38
Nodes (7): Calendário Nacional de Vacinação, Manifesto da Base de Conhecimento, Sistemas de Informação, e-SUS PEC, Rede de Frio, RNDS, SI-PNI

### Community 1 - "Health Information Networks"
Cohesion: 0.40
Nodes (5): Rede de Frio, Home Versão 1, e-SUS PEC, RNDS, SI-PNI

### Community 2 - "User Roles and Journeys"
Cohesion: 0.50
Nodes (4): Jornada do Usuário, Público e Cenários de Uso, Enfermeiro, Técnica de Enfermagem

### Community 3 - "National Immunization Program"
Cohesion: 0.67
Nodes (3): Imunobiológicos, Programa Nacional de Imunizações (PNI), Programa Nacional de Imunizações

### Community 4 - "Project Context and Logs"
Cohesion: 1.00
Nodes (3): AI Context, Diário de Bordo, Memórias da Trilha

## Knowledge Gaps
- **35 isolated node(s):** `Changelog`, `Trilha de Imunização README`, `Arquitetura da Base de Conhecimento`, `Critérios de Qualidade`, `Guia Editorial` (+30 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **26 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Calendário Nacional de Vacinação` connect `National Vaccination Systems` to `National Immunization Program`?**
  _High betweenness centrality (0.025) - this node is a cross-community bridge._
- **What connects `Changelog`, `Trilha de Imunização README`, `Arquitetura da Base de Conhecimento` to the rest of the system?**
  _35 weakly-connected nodes found - possible documentation gaps or missing edges._