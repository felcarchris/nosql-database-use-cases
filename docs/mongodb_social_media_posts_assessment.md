# MongoDB Social Media Posts Assessment

## Current file
- original name: `Análise de Dados de Mídia Social`
- preserved copy: `notebooks/original/mongodb_social_media_posts_original.ipynb`

## Theme
Basic MongoDB document modeling for social media posts plus simple aggregate queries.

## What the notebook currently does
- connects to local MongoDB at `mongodb://localhost:27017/`
- creates a `social_media_db` database and a `posts` collection
- inserts a few example posts
- computes average likes and comments by platform
- retrieves top posts sorted by likes

## Why it fits the collection
- it is small, didactic and database-oriented
- it adds a concrete document-modeling example to the MongoDB section
- it complements the broader NoSQL theme around backend storage use cases

## Why it should stay in the collection
- it is only a single-cell example
- it assumes a local MongoDB instance without setup instructions
- it has no README, schema note or indexing guidance
- the analytical logic is still minimal

## Classification decision
`media relevancia` as a MongoDB subcase inside the NoSQL collection.

## Recommended next steps
1. document startup steps for MongoDB
2. explain why a document model works well for this example
3. later group it with the other MongoDB notebooks under a shared `mongodb/` section

## Suggested future structure inside the collection
```text
mongodb/
  social-media-posts/
```

## Honest portfolio framing
This is a compact MongoDB modeling exercise, useful as part of a NoSQL portfolio set but too small
to stand alone.

