# Neo4j Product Recommendation Assessment

## Current file
- original name: `Neo4j.ipynb`
- preserved copy: `notebooks/original/neo4j_product_recommendation_original.ipynb`

## Theme
Introductory graph-based product recommendation example with Neo4j.

## What the notebook currently does
- imports the Neo4j Python driver
- defines local connection settings for `bolt://localhost:7687`
- creates uniqueness constraints for users and products
- inserts a small sample graph with users, products and `PURCHASED` relationships
- runs a simple recommendation query based on co-purchase behavior

## Why it fits well in this collection
- the graph recommendation theme is more distinctive than a generic CRUD example
- it aligns with backend, data modeling and database exploration
- it complements the Cassandra and MongoDB notebooks well

## Why it should still remain in a collection for now
- it is only a single-cell notebook
- it uses a hard-coded password placeholder
- there is no `.env.example`, Docker setup or local startup guide
- the example graph is very small and purely demonstrative
- there is no README or comparison to alternative recommendation approaches

## Classification decision
`media/alta relevancia` inside the NoSQL collection, with better thematic value than a standalone
repository in its current form.

## Recommended next steps
1. move connection settings to environment variables
2. document local Neo4j setup
3. separate schema creation, seed data and recommendation query into clearer files
4. later add a small `docker-compose` example and a concise README

## Suggested future structure inside the collection
```text
neo4j/
  product-recommendation/
```

## Honest portfolio framing
This is a clean introductory graph recommendation lab. It is useful and aligned with your profile,
but still too small to market as a complete recommendation platform.

