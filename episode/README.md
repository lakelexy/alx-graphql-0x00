# GraphQL Episode Query

This project contains a GraphQL query and its output to fetch details of an episode from the Rick and Morty API.

## Files

### Queries

- **`episode-page-1.graphql`**: Query to fetch details of the first episode.

### Outputs

- **`episode-page-1-output.json`**: Output for the query, containing details of the first episode.

## Query Details

The query retrieves the following fields:

- `id`: The unique identifier of the episode.
- `name`: The name of the episode.
- `air_date`: The original air date of the episode.
- `episode`: The code representing the episode (e.g., `S01E01`).

## Usage

To execute the query, use any GraphQL client, such as:

- GraphiQL
- Postman
- Apollo Client

Replace the `id` argument in the query to fetch details of a different episode.
