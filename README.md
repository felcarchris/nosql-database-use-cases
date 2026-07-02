# NoSQL Database Use Cases

## Overview
This repository groups academic notebook examples related to NoSQL data modeling and backend
storage scenarios.

## Why this collection exists
- the individual notebooks are too small to justify separate repositories
- together they show stronger alignment with backend, databases and data modeling
- the grouped format creates a better portfolio story around comparative storage approaches

## Current contents
- `Trabalho Bras 2024-11-11` -> preserved as `notebooks/original/trabalho_bras_2024_11_11_original.ipynb`
- `Neo4j.ipynb` -> preserved as `notebooks/original/neo4j_product_recommendation_original.ipynb`
- `Análise de Dados de Mídia Social` -> preserved as `notebooks/original/mongodb_social_media_posts_original.ipynb`
- `Armazenamento de Dados de Comércio Eletrônico` -> preserved as `notebooks/original/mongodb_ecommerce_products_original.ipynb`

## Positioning
This collection is meant for compact, didactic storage examples. Projects should move to their own
repositories only if they gain stronger architecture, reproducible setup and clearer problem framing.

## Repository structure
```text
nosql-database-use-cases/
|-- README.md
|-- .gitignore
|-- notebooks/
|   `-- original/
|       `-- trabalho_bras_2024_11_11_original.ipynb
|       `-- neo4j_product_recommendation_original.ipynb
|       `-- mongodb_social_media_posts_original.ipynb
|       `-- mongodb_ecommerce_products_original.ipynb
|-- docs/
|   `-- trabalho_bras_2024_11_11_assessment.md
|   `-- neo4j_product_recommendation_assessment.md
|   `-- mongodb_social_media_posts_assessment.md
|   `-- mongodb_ecommerce_products_assessment.md
|-- data/
|   |-- raw/
|   |   `-- .gitkeep
|   `-- processed/
|       `-- .gitkeep
`-- reports/
    `-- .gitkeep
```

## Publishing guidance
- keep each case small and explicit about the storage goal
- avoid hard-coded local endpoints or credentials in public-facing versions
- separate one notebook per database or use case when refactoring later
