# GraphQL Character Query Project

This project demonstrates how to use GraphQL to query character details. The main purpose is to fetch details about characters using their `id`. The repository includes GraphQL queries and the output responses for different character IDs.

## Project Structure

The repository contains the following files:

- **README.md**: This file.
- **character-id-1.graphql**: GraphQL query to fetch character details for ID 1.
- **character-id-1-output.json**: The output JSON response for the character with ID 1.
- **character-id-2.graphql**: GraphQL query to fetch character details for ID 2.
- **character-id-2-output.json**: The output JSON response for the character with ID 2.
- **character-id-3.graphql**: GraphQL query to fetch character details for ID 3.
- **character-id-3-output.json**: The output JSON response for the character with ID 3.
- **character-id-4.graphql**: GraphQL query to fetch character details for ID 4.
- **character-id-4-output.json**: The output JSON response for the character with ID 4.

## Query Structure

The main GraphQL query in this project requests the following fields for each character:

- **id**: The character's ID.
- **name**: The character's name.
- **status**: The character's current status (e.g., Alive, Dead).
- **species**: The character's species.
- **type**: The character's type (if applicable).
- **gender**: The character's gender.

The GraphQL query uses aliases to avoid conflicts when querying multiple characters with different IDs:

```graphql
query {
  character1: character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
  character2: character(id: 2) {
    id
    name
    status
    species
    type
    gender
  }
  character3: character(id: 3) {
    id
    name
    status
    species
    type
    gender
  }
  character4: character(id: 4) {
    id
    name
    status
    species
    type
    gender
  }
}
```
