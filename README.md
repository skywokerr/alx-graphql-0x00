# Episode Information GraphQL Queries

This directory contains GraphQL queries to fetch episode information from the Rick and Morty API using episode IDs.

## Episode Queries Included

- `episode-id-1.graphql` - Query for episode with ID 1
- `episode-id-2.graphql` - Query for episode with ID 2  
- `episode-id-3.graphql` - Query for episode with ID 3
- `episode-id-4.graphql` - Query for episode with ID 4

## Fields Requested

Each query requests the following fields:
- `id` - The episode's unique identifier
- `name` - The episode's name
- `air_date` - The date when the episode was first broadcast
- `episode` - The episode code (e.g., S01E01)

## API Endpoint

All queries use the Rick and Morty GraphQL API endpoint: