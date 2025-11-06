book-review-app/
│
├── 📄 package.json
├── 📄 server.js              # Entry point (starts Express server)
│
├── config/                   # Configuration files
│   └── db.js                 # Database connection (if you add one later)
│
├── routes/                   # Route definitions
│   ├── general.js            # Public routes (Tasks 1–5, 10–12)
│   └── auth.js               # Authenticated routes (Tasks 6–9)
│
├── controllers/              # Business logic for routes
│   ├── bookController.js     # Handles book queries (ISBN, author, title, reviews)
│   └── authController.js     # Handles register, login, JWT
│
├── models/                   # Data models
│   └── booksdb.js            # Book data object (your current JSON)
│   └── userModel.js          # User schema (if you move to DB later)
│
├── middleware/               # Reusable middleware
│   └── authMiddleware.js     # JWT authentication check
│
├── services/                 # External API or helper services
│   └── bookService.js        # Axios calls for async tasks (Tasks 10–12)
│
├── utils/                    # Utility functions
│   └── logger.js             # Example: logging helper
│
└── tests/                    # Unit/integration tests
    └── book.test.js
    └── auth.test.js
