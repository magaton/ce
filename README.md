# POC based on neo4j-graphql official library

## Quickstart

Create .env file in root dir
```
NEO4J_URI=bolt://localhost:7687
NEO4J_USER=neo4j
NEO4J_PASSWORD=admin

GRAPHQL_SERVER_HOST=0.0.0.0
GRAPHQL_SERVER_PORT=4001
GRAPHQL_SERVER_PATH=/graphql
```

## Import data into graph
Execute src/export.cypher


## Run
- npm install
- npm run start:dev


## Execute queries
Go to: Apollo studio: http://localhost:4001/graphql

Execute queries from src/queries.graphql