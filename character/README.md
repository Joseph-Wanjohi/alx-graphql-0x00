# Character Queries - Rick and Morty GraphQL

This directory contains GraphQL queries for fetching character data from the Rick and Morty API.

## API Endpoint
```
https://rickandmortyapi.com/graphql
```

## Task 0: Get Specific Characters by ID

### Files:
- `character-id-1.graphql` - Query for character with ID 1
- `character-id-1-output.json` - Response data for character ID 1
- `character-id-2.graphql` - Query for character with ID 2
- `character-id-2-output.json` - Response data for character ID 2
- `character-id-3.graphql` - Query for character with ID 3
- `character-id-3-output.json` - Response data for character ID 3
- `character-id-4.graphql` - Query for character with ID 4
- `character-id-4-output.json` - Response data for character ID 4

### Fields Retrieved:
- `id` - Character's unique identifier
- `name` - Character's name
- `status` - Character's status (Alive, Dead, unknown)
- `species` - Character's species (Human, Alien, etc.)
- `type` - Character's type or subspecies
- `gender` - Character's gender

## Task 1: Get Paginated List of Characters

### Files:
- `characters-page-1.graphql` - Query for characters on page 1
- `characters-page-1-output.json` - Response data for page 1
- `characters-page-2.graphql` - Query for characters on page 2
- `characters-page-2-output.json` - Response data for page 2
- `characters-page-3.graphql` - Query for characters on page 3
- `characters-page-3-output.json` - Response data for page 3
- `characters-page-4.graphql` - Query for characters on page 4
- `characters-page-4-output.json` - Response data for page 4

### Fields Retrieved:
- `id` - Character's unique identifier
- `name` - Character's name
- `status` - Character's status (Alive, Dead, unknown)
- `image` - Character's image URL

## How to Use

1. Copy any `.graphql` file content
2. Go to https://rickandmortyapi.com/graphql
3. Paste the query in the GraphQL playground
4. Click the play button to execute
5. View the results (examples saved in corresponding `.json` files)

## Learning Objectives

- Understanding GraphQL query syntax
- Fetching single vs multiple records
- Working with pagination in GraphQL
- Selecting specific fields to optimize data transfer