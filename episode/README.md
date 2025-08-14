# Episode Queries - ALX GraphQL 0x00

This directory contains GraphQL queries and their corresponding output files for retrieving episode details from the provided GraphQL endpoint.

## Description
We use the `episode(id: ID!)` field to retrieve information about a specific episode.  
The fields retrieved are:
- `id`
- `name`
- `air_date`
- `episode`

## Files
- **README.md** → This file, containing instructions and information.
- **episode-page-1.graphql** → The GraphQL query for retrieving episode details by ID.
- **characters-page-1-output.json** → Output JSON for page 1 characters.
- **characters-page-2.graphql** → Query for retrieving characters on page 2.
- **characters-page-2-output.json** → Output JSON for page 2 characters.
- **characters-page-3.graphql** → Query for retrieving characters on page 3.
- **characters-page-3-output.json** → Output JSON for page 3 characters.
- **characters-page-4.graphql** → Query for retrieving characters on page 4.
- **characters-page-4-output.json** → Output JSON for page 4 characters.

## Usage
1. Open the `.graphql` file to view the query.
2. Use a GraphQL client (such as [Rick and Morty GraphQL Playground](https://rickandmortyapi.com/graphql)) to execute the query.
3. Save the returned result into the corresponding `.json` output file.

## Example Query
```graphql
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}
