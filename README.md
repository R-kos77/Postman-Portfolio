# Reqres Advanced Portfolio Tests

**Advanced Postman Collection** for demonstrating API testing skills using the [Reqres](https://reqres.in/) mock API.  

This collection covers dynamic CRUD operations, authentication, pagination, and negative testing scenarios—ideal for showcasing automated API tests in a professional portfolio.

---

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation / Import](#installation--import)
- [Collection & Environment Structure](#collection--environment-structure)
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
- Uses **API key authentication** (`x-api-key: reqres-free-v1`)

---

## Prerequisites
- [Postman](https://www.postman.com/downloads/) installed
- Internet connection (Reqres is a hosted API)
- Optional: Git for version control

---

## Installation / Import
1. Download this repository.
2. Import the Postman collection JSON:
   - Open Postman → Click **Import** → Select `Reqres_Advanced_Portfolio_Tests.json`
3. Import the environment JSON:
   - Open Postman → Click **Import** → Select `Reqres_Advanced_Portfolio_Environment.postman_environment.json`
4. Select the environment in Postman before running requests.

---

## Collection & Environment Structure
### Collection: `Reqres Advanced Portfolio Tests`
- **User Workflow**
  - `Create User`, `Get Existing User`, `Update Existing User`, `Delete Existing User`
- **Authentication**
  - `Login Success`, `Login Failure`
- **List & Pagination**
  - `List Users Page 2`
- **Negative Tests**
  - `Get Non-existing User`

### Environment: `Reqres Advanced Portfolio Environment`
- Variables:
  - `baseURL` – API base URL
  - `token` – Authentication token
  - `randomName` – Dynamic name for user creation
  - `randomJob` – Dynamic job for user creation/update
  - `x-api-key` – Reqres API key

---

## How to Run
1. Ensure the environment is selected in Postman.
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
