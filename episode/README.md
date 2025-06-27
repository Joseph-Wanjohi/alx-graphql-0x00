# Episode Queries - Rick and Morty GraphQL

This directory contains GraphQL queries for fetching episode data from the Rick and Morty API.

## API Endpoint
```
https://rickandmortyapi.com/graphql
```

## Task 2: Get Specific Episodes by ID

### Files:
- `episode-page-1.graphql` - Query for episode with ID 1
- `episode-page-1-output.json` - Response data for episode ID 1
- `episode-page-2.graphql` - Query for episode with ID 2
- `episode-page-2-output.json` - Response data for episode ID 2
- `episode-page-3.graphql` - Query for episode with ID 3
- `episode-page-3-output.json` - Response data for episode ID 3
- `episode-page-4.graphql` - Query for episode with ID 4
- `episode-page-4-output.json` - Response data for episode ID 4

### Fields Retrieved:
- `id` - Episode's unique identifier
- `name` - Episode's title/name
- `air_date` - When the episode aired
- `episode` - Episode code (e.g., S01E01)

## How to Use

1. Copy any `.graphql` file content
2. Go to https://rickandmortyapi.com/graphql
3. Paste the query in the GraphQL playground
4. Click the play button to execute
5. View the results (examples saved in corresponding `.json` files)

## Example Query Structure

```graphql
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}
```

## Learning Objectives

- Understanding GraphQL query syntax for different data types
- Fetching episode information by ID
- Working with date fields in GraphQL
- Selecting specific fields to optimize data transfer