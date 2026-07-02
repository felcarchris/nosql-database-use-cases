# Trabalho Bras 2024-11-11 Assessment

## Current file
- original name: `Trabalho Bras 2024-11-11`
- preserved copy: `notebooks/original/trabalho_bras_2024_11_11_original.ipynb`

## Theme
Two introductory NoSQL examples:
- Cassandra for event and participant management
- MongoDB for article/comment-style document storage

## What the notebook currently does
- installs `cassandra-driver` inline
- connects to local Cassandra at `127.0.0.1`
- creates a keyspace and two tables
- inserts one event and one participant
- installs `pymongo` inline
- connects to local MongoDB at `mongodb://localhost:27017/`
- inserts a single example document into a collection

## Why it should not be a standalone repository yet
- the Cassandra and MongoDB cases are mixed in one notebook without a shared narrative
- both examples are still very small and mostly demonstrative
- setup is done inline instead of through reproducible environment instructions
- the notebook assumes local database services without documentation
- there is no README, architecture note or explanation of modeling tradeoffs

## Why it still has good portfolio value
- it matches your backend and database profile much better than generic toy notebooks
- the subject matter is relevant for modeling, APIs and storage discussions
- once grouped with related MongoDB, Neo4j and Cassandra cases, it supports a coherent NoSQL theme

## Classification decision
`media/alta relevancia` as part of a database-focused collection, not as an isolated repository.

## Recommended next steps
1. split Cassandra and MongoDB into separate notebooks or folders
2. replace inline installs with setup instructions
3. add a short README for each use case
4. later add `docker-compose` or simple local startup notes
5. merge related MongoDB and Neo4j notebooks from the same source folder into this collection

## Suggested future structure
```text
mongodb/
  social-media-posts/
  ecommerce-products/
  content-management/
cassandra/
  event-management/
neo4j/
  product-recommendation/
```

## Honest portfolio framing
Publicly, this should be described as a collection of introductory NoSQL modeling labs, not as a
production-ready persistence platform.
