# Book API Postman Project

This is a professional Postman collection for the **Book API** project. It includes all the essential API requests—**POST, GET, PATCH, DELETE**—to perform CRUD operations on book data.  
The collection is cleanly organized and ready for testing, showcasing, or including in your portfolio.

---

## 📦 Project Overview

This Postman collection demonstrates:

| HTTP Method | API Endpoint                           | Description                       |
|-------------|---------------------------------------|-------------------------------------|
| POST        | `https://api.example.com/books`        | Create a new book                  |
| GET         | `https://api.example.com/books`        | Retrieve all books                 |
| GET         | `https://api.example.com/books/{id}`   | Retrieve a single book by ID       |
| PATCH       | `https://api.example.com/books/{id}`   | Update a book’s details by ID      |
| DELETE      | `https://api.example.com/books/{id}`   | Delete a book by ID                |

---

## 🚀 Features

✅ Full CRUD API operations  
✅ Ready-to-use Postman requests (no environment variables required)  
✅ Organized structure for easy navigation  
✅ Includes headers, body, and example responses for each API call  
✅ Perfect for API testing, demos, and portfolio projects  

---

## 📖 API Request Details

### 1️⃣ Create a New Book (POST)

- **Endpoint:** `https://api.example.com/books`  
- **Method:** POST  
- **Headers:** `Content-Type: application/json`  
- **Body Example:**
```json
{
  "title": "The Alchemist",
  "author": "Paulo Coelho",
  "publishedYear": 1988,
  "genre": "Fiction"
}
