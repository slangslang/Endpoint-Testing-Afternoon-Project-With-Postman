# 🛠️ Endpoint Testing with Postman

## 🌟 Project Overview

I'm excited to share my completed project on **Endpoint Testing Afternoon with Postman**! 🚀 In this project, I explored the fundamentals of API endpoint testing, developing and executing a comprehensive suite of tests to validate the robustness and reliability of this API.

### A Special Shoutout! 🎉
A huge thank you to [DevMountain](https://github.com/DevMountain) for providing this fantastic free live endpoint testing project! Be sure to check out their repository: [Endpoint Testing Afternoon](https://github.com/DevMountain/endpoint-testing-afternoon).

I invite you to explore the details of my project and see how I tackled endpoint testing with Postman. Let’s get started! 💪

---

## 📊 Project Demo

![endpoint testing afternoon demo](https://github.com/slangslang/Endpoint-Testing-Afternoon-Project-With-Postman/blob/main/Untitledvideo-ezgif.com-video-to-gif-converter.gif)   
*Preview of the finished project with all test passing in the collection*

---

## 🛠️ Setup
1. **Forked and Cloned the Repository**:
   ```bash
   git clone <repo-url>
   cd <my-github-repo-folder>
   ```
2. **Installed Dependencies**:
   ```bash
   npm install
   ```
3. **Started the Server**:
   ```bash
   nodeman
   ```
   The server ran on port 3535.

---

## 🔍 Testing Steps

<details>
<summary><strong>1. Imported Postman Collection</strong></summary>

- I opened Postman and clicked on the <kbd>Import</kbd> button in the top left corner.
- I successfully imported the collection from the `postman_collection` folder.
- Now, I can see a collection titled **Endpoint Testing Afternoon** ready for use.
</details>

<details>
<summary><strong>2. Executed GET Requests</strong></summary>

- **All Users**:
  - I verified that the response status is **200**.
  - I checked that the returned data is an array with a length of **100**.

- **User by ID**:
  - I ensured the correct user properties were returned for the specified ID.

- **User by ID (Error)**:
  - I confirmed that appropriate error messages were displayed for invalid ID requests.
</details>

<details>
<summary><strong>3. Conducted Query Testing</strong></summary>

- **User with Query**:
  - I validated that users could be fetched based on query parameters.

- **User with Query (Error)**:
  - I checked for correct error messaging when an improper query was sent.
</details>

<details>
<summary><strong>4. Updated User Information</strong></summary>

- **Update by ID**:
  - I tested user updates and ensured the returned user had updated properties.

- **Update by ID (Error)**:
  - I verified that error handling was effective for invalid updates.
</details>

<details>
<summary><strong>5. Created New Users</strong></summary>

- **Create User**:
  - I ensured new users could be created successfully and verified the returned data.

- **Create User (Error)**:
  - I checked that the server responded correctly when required data was missing.
</details>

<details>
<summary><strong>6. Deleted Users</strong></summary>

- **Remove User**:
  - I validated the successful removal of a user and checked the returned ID.

- **Remove User (Error)**:
  - I confirmed that proper error handling was in place for attempts to delete non-existent users.
</details>

<details>
<summary><strong>7. Ran All Tests</strong></summary>

- I restarted the server to ensure everything was fresh.
- I clicked the right arrow next to the collection name in Postman and selected **Run**.
- I executed the entire collection and confirmed that all tests passed successfully.
</details>

### 📡 Explore the API with Postman
Click the button below to access the finished in-depth project:

[![Postman Collection](https://img.shields.io/badge/Postman-Collection-orange?style=for-the-badge&logo=postman)](https://www.postman.com/rodman-1o4fwe9oqcsfx/workspace/endpoint-testing-afternoon/collection/34720226-c7d2a42f-49ef-49f6-a196-a59d8b3ab5a6?action=share&creator=34720226)

---

## 🎯 Conclusion
Through this project, I gained valuable hands-on experience in API endpoint testing, validating responses, handling errors, and ensuring API reliability using Postman.

Feel free to reach out if you have any questions or need further clarification! 🤝
