### Task 0: GraphQL Query to Get a Specific Character by ID

This task demonstrates how to write a GraphQL query to fetch the details of a specific character using their ID.

**Files:**

- `character-id-1.graphql`: Contains the GraphQL query for character with ID 1.
- `character-id-1-output.json`: The expected JSON response from the GraphQL API for character ID 1.
- `character-id-2.graphql`: Contains the GraphQL query for character with ID 2.
- `character-id-2-output.json`: The expected JSON response from the GraphQL API for character ID 2.
- `character-id-3.graphql`: Contains the GraphQL query for character with ID 3.
- `character-id-3-output.json`: The expected JSON response from the GraphQL API for character ID 3.
- `character-id-4.graphql`: Contains the GraphQL query for character with ID 4.
- `character-id-4-output.json`: The expected JSON response from the GraphQL API for character ID 4.

**Query Details:**

The queries use the `character(id: ID!)` field to retrieve data. The fields requested for each character are `id`, `name`, `status`, `species`, `type`, and `gender`.

---

### Task 1: GraphQL Query to Get a List of All Characters

This task demonstrates how to write a paginated GraphQL query to fetch a list of all characters.

**Files:**

- `characters-page-1.graphql`: Contains the GraphQL query for character page 1.
- `characters-page-1-output.json`: The expected JSON response for character page 1.
- `characters-page-2.graphql`: Contains the GraphQL query for character page 2.
- `characters-page-2-output.json`: The expected JSON response for character page 2.
- `characters-page-3.graphql`: Contains the GraphQL query for character page 3.
- `characters-page-3-output.json`: The expected JSON response for character page 3.
- `characters-page-4.graphql`: Contains the GraphQL query for character page 4.
- `characters-page-4-output.json`: The expected JSON response for character page 4.

**Query Details:**

The queries use the `characters(page: Int)` field to retrieve paginated data. The fields requested for each character are `id`, `name`, `status`, and `image`.