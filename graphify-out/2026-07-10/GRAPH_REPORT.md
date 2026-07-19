# Graph Report - .  (2026-07-10)

## Corpus Check
- cluster-only mode — file stats not available

## Summary
- 17 nodes · 13 edges · 9 communities (3 shown, 6 thin omitted)
- Extraction: 77% EXTRACTED · 23% INFERRED · 0% AMBIGUOUS · INFERRED: 3 edges (avg confidence: 0.87)
- Token cost: 232 input · 63 output

## Community Hubs (Navigation)
- Quality and Taxonomy Standards
- Knowledge Base Architecture
- Immunization Metadata Standards
- Visual Identity and Home
- Editorial Guidelines
- Immunobiological Data Model
- Arquitetura da Trilha
- Princípios da Plataforma
- Trilha de Imunização README

## God Nodes (most connected - your core abstractions)
1. `Modelo de Objeto de Conhecimento` - 5 edges
2. `Objeto de Conhecimento: BCG` - 5 edges
3. `Changelog` - 4 edges
4. `Critérios de Qualidade` - 2 edges
5. `Padrão de Metadados` - 2 edges
6. `Modelo de Vacina` - 2 edges
7. `Trilha de Imunização Home` - 1 edges
8. `Arquitetura da Base de Conhecimento` - 1 edges
9. `Taxonomia dos Objetos` - 1 edges
10. `Programa Nacional de Imunizações (PNI)` - 1 edges

## Surprising Connections (you probably didn't know these)
- `Núcleo do Conhecimento` --references--> `Modelo de Objeto de Conhecimento`  [INFERRED]
  docs/NUCLEO_DO_CONHECIMENTO.md → conhecimento/MODELO_OBJETO_DE_CONHECIMENTO.md
- `Changelog` --references--> `Modelo de Objeto de Conhecimento`  [EXTRACTED]
  CHANGELOG.md → conhecimento/MODELO_OBJETO_DE_CONHECIMENTO.md
- `Trilha de Imunização Home` --implements--> `Guia de Identidade Visual`  [INFERRED]
  index.html → docs/GUIA_IDENTIDADE_VISUAL.md
- `Changelog` --references--> `Critérios de Qualidade`  [EXTRACTED]
  CHANGELOG.md → conhecimento/CRITERIOS_DE_QUALIDADE.md
- `Changelog` --references--> `Modelo de Vacina`  [EXTRACTED]
  CHANGELOG.md → conhecimento/imunobiologicos/vacinas/MODELO_VACINA.md

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Knowledge Base Structural Framework** — conhecimento_arquitetura_da_base, conhecimento_modelo_objeto_de_conhecimento, conhecimento_padrao_de_metadados, conhecimento_taxonomia_dos_objetos, conhecimento_criterios_de_qualidade [EXTRACTED 1.00]
- **Immunization Domain Entities** — conhecimento_programa_nacional_imunizacoes_pni, conhecimento_imunobiologicos_vacinas_bcg_bcg [EXTRACTED 1.00]

## Communities (9 total, 6 thin omitted)

### Community 0 - "Quality and Taxonomy Standards"
Cohesion: 0.50
Nodes (4): Changelog, Critérios de Qualidade, Modelo de Vacina, Taxonomia dos Objetos

### Community 1 - "Knowledge Base Architecture"
Cohesion: 0.67
Nodes (3): Arquitetura da Base de Conhecimento, Modelo de Objeto de Conhecimento, Núcleo do Conhecimento

### Community 2 - "Immunization Metadata Standards"
Cohesion: 0.67
Nodes (3): Objeto de Conhecimento: BCG, Padrão de Metadados, Programa Nacional de Imunizações (PNI)

## Knowledge Gaps
- **11 isolated node(s):** `Trilha de Imunização README`, `Trilha de Imunização Home`, `Arquitetura da Base de Conhecimento`, `Guia Editorial`, `Taxonomia dos Objetos` (+6 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **6 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Modelo de Objeto de Conhecimento` connect `Knowledge Base Architecture` to `Quality and Taxonomy Standards`, `Immunization Metadata Standards`?**
  _High betweenness centrality (0.153) - this node is a cross-community bridge._
- **Why does `Objeto de Conhecimento: BCG` connect `Immunization Metadata Standards` to `Quality and Taxonomy Standards`, `Knowledge Base Architecture`?**
  _High betweenness centrality (0.113) - this node is a cross-community bridge._
- **Why does `Changelog` connect `Quality and Taxonomy Standards` to `Knowledge Base Architecture`?**
  _High betweenness centrality (0.096) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `Modelo de Objeto de Conhecimento` (e.g. with `Arquitetura da Base de Conhecimento` and `Núcleo do Conhecimento`) actually correct?**
  _`Modelo de Objeto de Conhecimento` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `Trilha de Imunização README`, `Trilha de Imunização Home`, `Arquitetura da Base de Conhecimento` to the rest of the system?**
  _11 weakly-connected nodes found - possible documentation gaps or missing edges._