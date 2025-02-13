# 📌 **Postman API Testing Collection - Evaluation**  
📖 Overview
This repository contains a Postman Collection for testing APIs using DummyJSON, a mock API service. It includes various GET, POST, PATCH, and DELETE requests for products and authentication.

📂 Included Endpoints
The collection covers the following API requests:


 📄 API Endpoints
| 🆔 | Method | Endpoint | Description |
|----|--------|----------|-------------|
| 1️⃣ | **GET** | `/products` | Get all products |
| 2️⃣ | **GET** | `/products/1` | Get a single product |
| 3️⃣ | **GET** | `/products/search?q=phone` | Search products |
| 4️⃣ | **GET** | `/products?limit=10&skip=10` | Paginate products |
| 5️⃣ | **GET** | `/products?sortBy=title&order=asc` | Sort products |
| 6️⃣ | **POST** | `/products/add` | Add a new product |
| 7️⃣ | **PATCH** | `/products/1` | Update a product |
| 8️⃣ | **DELETE** | `/products/1` | Delete a product |
| 9️⃣ | **POST** | `/auth/login` | User login authentication |

💡 **Note:** The API uses `https://dummyjson.com` as a test server.  


