# MongoDB Ecommerce Products Assessment

## Current file
- original name: `Armazenamento de Dados de Comércio Eletrônico`
- preserved copy: `notebooks/original/mongodb_ecommerce_products_original.ipynb`

## Theme
Basic MongoDB document storage for e-commerce product records.

## What the notebook currently does
- connects to local MongoDB at `mongodb://localhost:27017/`
- creates an `ecommerce_db` database and a `products` collection
- inserts sample product documents
- updates product information
- deletes one product
- queries products by category and lists all remaining products

## Why it fits the collection
- it is a clear MongoDB CRUD and modeling example
- it aligns with backend and data-storage themes
- it complements the social-media and article-style MongoDB cases

## Why it should remain in the collection
- it is still only a one-cell notebook
- it assumes a local MongoDB service without setup documentation
- there is no discussion of indexes, schema choices or inventory rules
- it is too small to justify an isolated repository

## Classification decision
`media relevancia` inside the NoSQL collection.

## Recommended next steps
1. document the local MongoDB setup
2. explain the document shape and why MongoDB suits this use case
3. group it with other MongoDB examples under a shared section

## Suggested future structure inside the collection
```text
mongodb/
  ecommerce-products/
```

## Honest portfolio framing
This is a compact e-commerce storage exercise, useful as part of a broader NoSQL showcase rather
than as a standalone project.

