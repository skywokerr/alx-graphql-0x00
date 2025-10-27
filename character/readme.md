# Character Information GraphQL Queries

This directory contains GraphQL queries to fetch character information from the Rick and Morty API.

## Individual Character Queries

- `character-id-1.graphql` - Query for character with ID 1
- `character-id-2.graphql` - Query for character with ID 2  
- `character-id-3.graphql` - Query for character with ID 3
- `character-id-4.graphql` - Query for character with ID 4

## Paginated Character Queries

- `characters-page-1.graphql` - Query for characters on page 1
- `characters-page-2.graphql` - Query for characters on page 2
- `characters-page-3.graphql` - Query for characters on page 3
- `characters-page-4.graphql` - Query for characters on page 4

## Fields Requested

### Individual Character Queries:
- `id` - The character's unique identifier
- `name` - The character's name
- `status` - The character's status (Alive, Dead, Unknown)
- `species` - The character's species
- `type` - The character's type or subspecies
- `gender` - The character's gender

### Paginated Character Queries:
- `id` - The character's unique identifier
- `name` - The character's name
- `status` - The character's status
- `image` - The character's image URL

## API Endpoint

All queries use the Rick and Morty GraphQL API endpoint: