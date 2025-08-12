### Task 2: GraphQL Query to Get a Specific Episode by ID

This task demonstrates how to write a GraphQL query to fetch the details of a specific episode using its ID.

**Files:**

- `episode-id-1.graphql`: Contains the GraphQL query for episode with ID 1.
- `episode-id-1-output.json`: The expected JSON response from the GraphQL API for episode ID 1.
- `episode-id-2.graphql`: Contains the GraphQL query for episode with ID 2.
- `episode-id-2-output.json`: The expected JSON response from the GraphQL API for episode ID 2.
- `episode-id-3.graphql`: Contains the GraphQL query for episode with ID 3.
- `episode-id-3-output.json`: The expected JSON response from the GraphQL API for episode ID 3.
- `episode-id-4.graphql`: Contains the GraphQL query for episode with ID 4.
- `episode-id-4-output.json`: The expected JSON response from the GraphQL API for episode ID 4.

**Query Details:**

The queries use the `episode(id: ID!)` field to retrieve data. The fields requested for each episode are `id`, `name`, `air_date`, and `episode`.