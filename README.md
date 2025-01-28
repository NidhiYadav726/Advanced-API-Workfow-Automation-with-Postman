# Advanced API Automation Using Postman

This repository contains a comprehensive Postman collection designed to automate advanced API testing scenarios. The collection is focused on **CRUD operations**, **Dynamic Data Handling**, and **Performance/Load Testing** across different APIs.

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
  - Utilizes Postman’s Collection Runner to simulate concurrent requests.
  - Validates API behavior under varying loads.

---

## 🚀 How to Use

### 1. Prerequisites
- **Postman Installed**: [Download Postman](https://www.postman.com/downloads/)
- **APIs**: Access to GoRest API and ReqRes API.
- **Environment Setup**:
  - Create environment variables for:
    - `{{url}}`: Base URL of the API.
    - `{{access_token}}`: Bearer token for authentication.

### 2. Clone the Repository
- Clone this repository to your local machine using the following command:
  ```bash
  https://github.com/NidhiYadav726/AdvancedPostmanTemplate.git

## 🔧 Tools and Technologies
- **Postman**: For API testing and automation.
- **Postman Scripts**: Pre-request and test scripts for dynamic and automated validations.
- **Environment Variables**: For managing API configurations and data.
- **CSV Integration**: For data-driven testing.

---

## 📂 Resources
- [GoRest API Documentation](https://gorest.co.in/)
- [ReqRes API Documentation](https://reqres.in/)
- [Postman Documentation](https://learning.postman.com/)

---

