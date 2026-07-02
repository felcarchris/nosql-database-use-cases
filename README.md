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
|-- docs/
|   `-- trabalho_bras_2024_11_11_assessment.md
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

