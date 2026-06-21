# 🚀 DummyJSON API Testing Project

## 📌 Project Overview

This project showcases end-to-end REST API Testing using Postman on DummyJSON APIs. The objective was to validate API functionality, verify request-response behavior, perform CRUD operations, and ensure proper status code and data validation across multiple modules.

The project was developed to gain hands-on experience in API Testing and strengthen practical knowledge of REST APIs, JSON payloads, HTTP methods, and Postman scripting.

---

## 🎯 Project Objectives

- Understand REST API architecture and workflows.
- Validate API requests and responses.
- Perform CRUD operation testing.
- Verify HTTP status codes and response payloads.
- Execute positive and negative test scenarios.
- Create reusable Postman collections.
- Document test cases and test results.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|--------|----------|
| Postman | API Testing |
| DummyJSON | REST API Provider |
| JSON | Request & Response Data |
| Excel | Test Case Documentation |
| GitHub | Version Control & Project Hosting |

---

## 📂 Modules Tested

### 🔐 Authentication
- User Login
- Get Authenticated User

### 📦 Products
- Get All Products
- Get Product By ID
- Search Products
- Add Product
- Update Product
- Delete Product

### 🛒 Carts
- Get All Carts
- Get Cart By ID
- Add Products to Cart
- Update Cart
- Delete Cart

### 📝 Posts
- Get All Posts
- Get Post By ID
- Search Posts
- Create Post
- Update Post
- Delete Post

### 💬 Comments
- Get All Comments
- Get Comment By ID
- Get Comments By Post ID
- Add Comment
- Update Comment
- Delete Comment

---

## ✅ Testing Activities Performed

- Functional Testing
- API Testing
- CRUD Operations Testing
- Response Validation
- Status Code Validation
- JSON Schema Validation
- Positive Testing
- Negative Testing
- Postman Test Scripting

---

## 📋 Sample Endpoints Tested

### Authentication

```http
POST /auth/login
GET /auth/me
```

### Products

```http
GET /products
GET /products/{id}
GET /products/search?q=phone
POST /products/add
PUT /products/{id}
DELETE /products/{id}
```

### Posts

```http
GET /posts
GET /posts/{id}
GET /posts/search?q=love
POST /posts/add
PUT /posts/{id}
DELETE /posts/{id}
```

### Comments

```http
GET /comments
GET /comments/{id}
GET /comments/post/{id}
POST /comments/add
PUT /comments/{id}
DELETE /comments/{id}
```

---

## 📊 Validations Performed

✔️ Status Code Validation

✔️ Response Body Validation

✔️ JSON Data Verification

✔️ CRUD Operation Validation

✔️ Error Response Validation

✔️ Content-Type Verification

✔️ Response Time Validation

---

## 📁 Project Deliverables

- Postman Collection
- API Test Cases (Excel)
- Project Documentation
- Execution Screenshots
- GitHub Repository

---

## ⚠️ Observations

DummyJSON is a mock REST API service. Data created using POST requests is not permanently stored. Therefore, retrieval, update, or deletion of newly created records may return **"not found"** responses. These scenarios were documented and validated as negative test cases.

---

## 🎓 Key Learning Outcomes

- Hands-on experience with REST API Testing
- Understanding of HTTP Methods (GET, POST, PUT, DELETE)
- API Request & Response Validation
- Postman Collection Creation
- Test Case Design and Documentation
- Positive & Negative Testing Techniques

---

## 📈 Project Outcome

Successfully tested Authentication, Products, Carts, Posts, and Comments APIs using Postman. Validated API functionality, response structures, status codes, and CRUD operations while building practical API Testing skills aligned with Software Testing industry standards.

---

## 👨‍💻 Author

### Sarode Maruthi Rao

Software Testing Enthusiast | Manual Testing | API Testing | Postman | SQL | Git & GitHub

📧 Email: Your Email

🔗 LinkedIn: Your LinkedIn Profile

🔗 GitHub: Your GitHub Profile
