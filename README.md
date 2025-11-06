# 📚 Book Review App

A Node.js + Express application that allows users to register, login, and manage book reviews.  
It also demonstrates asynchronous programming in JavaScript (callbacks, promises, async/await).

---

## 🚀 Features
- View all books, search by ISBN, author, or title
- Register and login with JWT authentication
- Add, modify, and delete reviews (authenticated users only)
- Async programming examples:
  - Task 10: Get all books (Callback)
  - Task 11: Search by ISBN (Promise)
  - Task 12: Search by Author (Async/Await)

---
## 📂 Project Structure

```text
book-review-app/
├── server.js
├── models/
│   └── booksdb.js
├── routes/
│   ├── general.js
│   └── auth.js
├── middleware/
│   └── authMiddleware.js
├── services/
│   └── bookService.js
└── controllers/
    ├── bookController.js
    └── authController.js

