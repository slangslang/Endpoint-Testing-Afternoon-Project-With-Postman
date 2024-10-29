# Endpoint Testing with Postman

## Project Overview
This project focuses on practicing the fundamentals of endpoint testing using Postman. By creating and executing various tests for a server's API endpoints, I ensured the robustness and reliability of the API. Special thanks to [DevMountain](https://github.com/DevMountain) for providing this free live endpoint testing project!!! Here's the direct repo link [Endpoint Testing Afternoon](https://github.com/DevMountain/endpoint-testing-afternoon).

---

## Table of Contents
- [Setup](#setup)
- [Testing Steps](#testing-steps)
  - [1. Importing Postman Collection](#1-importing-postman-collection)
  - [2. GET Requests](#2-get-requests)
  - [3. Query Testing](#3-query-testing)
  - [4. Updating User](#4-updating-user)
  - [5. Creating Users](#5-creating-users)
  - [6. Deleting Users](#6-deleting-users)
  - [7. Running All Tests](#7-running-all-tests)
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
<summary>1. Importing Postman Collection</summary>
  
- Open Postman.
  
- Click on the **Import** button in the top left corner.

- Import the collection located in the `postman_collection` folder.

- You should now see a collection titled **Endpoint Testing Afternoon**.
</details>

<details>
<summary>2. GET Requests</summary>

- **All Users**:
  - Verify the response status is **200**.
  - Check that the returned data is an array with a length of **100**.

- **User by ID**:
  - Ensure the correct user properties are returned for the specified ID.

- **User by ID (Error)**:
  - Confirm that appropriate error messages are displayed for invalid ID requests.

</details>

<details>
<summary>3. Query Testing</summary>

- **User with Query**:
  - Validate that users can be fetched based on query parameters.

- **User with Query (Error)**:
  - Check for correct error messaging when an improper query is sent.

</details>

<details>
<summary>4. Updating User</summary>

- **Update by ID**:
  - Test user updates, ensuring the returned user has updated properties.

- **Update by ID (Error)**:
  - Verify error handling for invalid updates.

</details>

<details>
<summary>5. Creating Users</summary>

- **Create User**:
  - Ensure new users can be created and verify the returned data.

- **Create User (Error)**:
  - Check that the server responds correctly when required data is missing.

</details>

<details>
<summary>6. Deleting Users</summary>

- **Remove User**:
  - Validate successful user removal and check the returned ID.

- **Remove User (Error)**:
  - Confirm proper error handling for attempts to delete non-existent users.

</details>

<details>
<summary>7. Running All Tests</summary>

- Restart the server.
- Click the right arrow next to the collection name in Postman and select **Run**.
- Execute the entire collection to ensure all tests pass.

</details>

---

## Conclusion
Through this project, you gained valuable hands-on experience in API endpoint testing, validating responses, handling errors, and ensuring API reliability using Postman.

---

Feel free to reach out if you have any questions or need further clarification!
