# 📚 Book Management REST API

This is a simple **Node.js + Express** REST API for managing a list of books, supporting basic **CRUD** operations (Create, Read, Update, Delete).  
Data is stored in-memory (no database required).

---

## 🚀 Features

- View all books (`GET /books`)
- Add a new book (`POST /books`)
- Update a book by ID (`PUT /books/:id`)
- Delete a book by ID (`DELETE /books/:id`)

---

## 🛠️ Tools & Technologies

- Node.js
- Express
- Postman (for testing)

---

## 📂 Installation & Setup

1️⃣ Initialize the project:
npm init -y

2️⃣ Install dependencies:
npm install express

3️⃣ Start the server:
node index.js

Server will run on:
http://localhost:3000


---

📬 API Endpoints
1️⃣ Get All Books
GET /books

Response: JSON array of all books

2️⃣ Add a New Book
POST /books

Request Body (JSON):

{
  "title": "Book Title",
  "author": "Author Name"
}

3️⃣ Update a Book by ID
PUT /books/:id

Request Body (JSON):
{
  "title": "Updated Title",
  "author": "Updated Author"  
}

4️⃣ Delete a Book by ID
DELETE /books/:id

---

🚀 Future Enhancements
Add input validation

Connect to a database (e.g., MongoDB)

Add user authentication

Deploy the API on a cloud platform
