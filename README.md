# Advanced API Workflow Automation with Postman

This repository contains a comprehensive Postman collection designed to automate advanced API testing scenarios. The collection is focused on **CRUD operations**, **Dynamic Data Handling**, and **Performance/Load Testing** across different APIs. Describes how to use advanced scripting features in Postman to automate complex API workflows. This includes chaining requests, dynamically generating data, managing environment variables, and leveraging collection runners for end-to-end test scenarios.

---

## 📌 Features

### 1. CRUD Operations with GoRest API
- **Create Users**:
  - Positive and negative test cases for creating users.
  - Scenarios include creating users with valid data, special characters, maximum length fields, and invalid or missing fields.
- **Read Users**:
  - Tests for fetching specific users, applying filters, and testing pagination.
  - Negative cases include invalid IDs and non-existent users.
- **Update Users**:
  - Scenarios to update user details with valid and invalid data.
- **Delete Users**:
  - Positive tests for deleting valid users and verifying their deletion.
  - Negative cases for deleting non-existent or already deleted users.

### 2. Dynamic Data Handling with ReqRes API
- **Add Products**:
  - Dynamic data-driven tests using CSV files for product addition.
  - Tests ensure API stability and scalability by simulating multiple data inputs.

### 3. Performance and Load Testing
- **ReqRes API**:
  - Includes performance benchmarks for response times and load capacity.
  -  simulate multiple concurrent requests to test how the Reqres API handles high traffic and multiple users simultaneously.
  - Validates API behavior under varying loads.

---

## 🚀 How to Use

### 1. Prerequisites
- **Postman Installed**: [Download Postman](https://www.postman.com/downloads/)
- **APIs**: Access to GoRest API and ReqRes API.
- **Environment Setup**:
  - Create environment variables for eg:
    - `{{url}}`: Base URL of the API.
    - `{{access_token}}`: Bearer token for authentication.

### 2. Clone the Repository
- Clone this repository to your local machine using the following command:
  ```bash
  https://github.com/NidhiYadav726/AdvancedPostmanTemplate.git

---

## 🔄 Run Collection Locally

### a. Manual Execution
Use Postman Collection Runner for manual runs:
1. Open the Postman app.
2. Import the `.json` files:
   - Collection: `<collection-file.json>`
   - Environment: `<environment-file.json>`
3. Go to **Collection Runner**:
   - Select the imported collection.
   - Choose the environment.
   - Configure settings like iterations or attach a data file (e.g., `data.csv`).
4. Click **Run** to execute the collection.



### b. Command-Line Execution with Newman

1. Prerequisites
   Ensure Newman is installed:
   
```bash

npm install -g newman

```
2. Run the collection using the following command:
   
```bash
newman run <collection-file.json> -e <environment-file.json>

```
3. Generate Reports

```bash
npm install -g newman-reporter-htmlextra
--reporters cli,htmlextra
```

---

## 🔧 Tools and Technologies
- **Postman**: For API testing and automation.
- **Postman Scripts**: Pre-request and test scripts for dynamic and automated validations.
- **Environment Variables**: For managing API configurations and data.
- **CSV Integration**: For data-driven testing.
- **Newman**: For command-line execution and CI/CD automation

---

## 📂 Resources
- [GoRest API Documentation](https://gorest.co.in/)
- [ReqRes API Documentation](https://reqres.in/)
- [Postman Documentation](https://learning.postman.com/)

---

