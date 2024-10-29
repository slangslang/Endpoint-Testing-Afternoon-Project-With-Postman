# Endpoint Testing with Postman

## Project Overview
This project focuses on practicing the fundamentals of endpoint testing using Postman. By creating and executing various tests for a server's API endpoints, I ensured the robustness and reliability of the API. Special thanks to [DevMountain](https://github.com/DevMountain) for providing this free live endpoint testing project!!! Here's the direct repo link [Endpoint Testing Afternoon](https://github.com/DevMountain/endpoint-testing-afternoon).

---

## Table of Contents
- [Setup](#setup)
- [Testing Steps](#testing-steps)
  - [1. Importing Postman Collection](#importing-postman-collection)
  - [2. GET Requests](#get-requests)
  - [3. Query Testing](#query-testing)
  - [4. Updating User](#updating-user)
  - [5. Creating Users](#creating-users)
  - [6. Deleting Users](#deleting-users)
  - [7. Running All Tests](#running-all-tests)
- [Conclusion](#conclusion)

---

## Setup
1. **Fork and Clone the Repository**:
   ```bash
   git clone <your-repo-url>
   cd <your-repo-folder>
   ```
2. **Install Dependencies**:
   ```bash
   npm install
   ```
3. **Start the Server**:
   ```bash
   nodeman
   ```
   The server will run on port 3535. Please do not change this port.

---

## Testing Steps

<details>
<summary id="importing-postman-collection">1. Importing Postman Collection</summary>
  
- Open Postman.
  
- Click on the **Import** button in the top left corner.

- Import the collection located in the `postman_collection` folder.

- You should now see a collection titled **Endpoint Testing Afternoon**.
</details>

<details>
<summary id="get-requests">2. GET Requests</summary>

- **All Users**:
  - Verify the response status is **200**.
  - Check that the returned data is an array with a length of **100**.

- **User by ID**:
  - Ensure the correct user properties are returned for the specified ID.

- **User by ID (Error)**:
  - Confirm that appropriate error messages are displayed for invalid ID requests.

</details>

<details>
<summary id="query-testing">3. Query Testing</summary>

- **User with Query**:
  - Validate that users can be fetched based on query parameters.

- **User with Query (Error)**:
  - Check for correct error messaging when an improper query is sent.

</details>

<details>
<summary id="updating-user">4. Updating User</summary>

- **Update by ID**:
  - Test user updates, ensuring the returned user has updated properties.

- **Update by ID (Error)**:
  - Verify error handling for invalid updates.

</details>

<details>
<summary id="creating-users">5. Creating Users</summary>

- **Create User**:
  - Ensure new users can be created and verify the returned data.

- **Create User (Error)**:
  - Check that the server responds correctly when required data is missing.

</details>

<details>
<summary id="deleting-users">6. Deleting Users</summary>

- **Remove User**:
  - Validate successful user removal and check the returned ID.

- **Remove User (Error)**:
  - Confirm proper error handling for attempts to delete non-existent users.

</details>

<details>
<summary id="running-all-test">7. Running All Tests</summary>

- Restart the server.
- Click the right arrow next to the collection name in Postman and select **Run**.
- Execute the entire collection to ensure all tests pass.

</details>

---

## Conclusion
Through this project, you gained valuable hands-on experience in API endpoint testing, validating responses, handling errors, and ensuring API reliability using Postman.

---

Feel free to reach out if you have any questions or need further clarification!
