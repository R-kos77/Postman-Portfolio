# Reqres Advanced Portfolio Tests

**Advanced Postman Collection** for demonstrating API testing skills using the [Reqres](https://reqres.in/) mock API.  

This collection covers dynamic CRUD operations, authentication, pagination, and negative testing scenarios—ideal for showcasing automated API tests in a professional portfolio.

---

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation / Import](#installation--import)
- [Collection Structure](#collection-structure)
- [Variables](#variables)
- [How to Run](#how-to-run)
- [Author](#author)

---

## Features
- **User Workflow**
  - Create a user (dynamic name and job generation)
  - Retrieve an existing user
  - Update an existing user
  - Delete an existing user
- **Authentication**
  - Login success scenario (retrieves and stores a token)
  - Login failure scenario (validates error response)
- **List & Pagination**
  - Retrieve users from page 2 with validations
- **Negative Tests**
  - Retrieve non-existing user and validate 404 response

- Includes **pre-request scripts** for dynamic data generation
- Includes **test scripts** for status codes and response validation
- Demonstrates **Postman environment variables** usage

---

## Prerequisites
- [Postman](https://www.postman.com/downloads/) installed
- Internet connection (Reqres is a hosted API)
- Optional: Git for version control

---

## Installation / Import
1. Download this repository or copy the JSON file `Reqres_Advanced_Portfolio_Tests.json`.
2. Open Postman → Click **Import** → Select the JSON file.
3. The collection will appear in your workspace.

---

## Collection Structure
- **User Workflow**
  - `Create User`, `Get Existing User`, `Update Existing User`, `Delete Existing User`
- **Authentication**
  - `Login Success`, `Login Failure`
- **List & Pagination**
  - `List Users Page 2`
- **Negative Tests**
  - `Get Non-existing User`

---

## Variables
| Variable      | Description                                    | Example                     |
|---------------|-----------------------------------------------|-----------------------------|
| `baseURL`     | Base URL of the API                             | `https://reqres.in/api`    |
| `token`       | Stores authentication token after login       | `abc123`                    |
| `randomName`  | Dynamic name for user creation                 | `User1234`                  |
| `randomJob`   | Dynamic job for user creation/update           | `Job5678`                   |

---

## How to Run
1. Ensure variables are correctly set in your environment.
2. Run individual requests or the entire collection.
3. Observe tests passing in Postman’s **Tests** tab.
4. Dynamic data and validations are applied automatically via scripts.

---

## Author
- Robel Kiros – API Tester / QA Engineer  
- Portfolio-ready collection demonstrating advanced Postman testing

---

**Collection Link (for Postman workspace reference):**  
[Open in Postman](https://shambelsost-8852409.postman.co/workspace/Shambel-Sost's-Workspace~59fca43a-70ed-4c06-8673-79fb94e6bef6/collection/49560745-786764fe-57c3-4728-b2ee-da86f6353849?action=share&source=collection_link&creator=49560745)
