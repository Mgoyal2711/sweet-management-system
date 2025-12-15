🍬 Sweet Store Management System

A full-stack Sweet Store Management application designed to handle inventory operations such as adding, purchasing, searching, and restocking sweets. The backend is built using TypeScript and Node.js, while the frontend uses vanilla JavaScript, HTML, and CSS for a lightweight and responsive experience.

✨ Key Highlights

Clean separation of backend and frontend

Fully tested business logic with complete coverage

Simple UI for managing sweets inventory

RESTful API design

Beginner-friendly and easy to extend

🚀 Functionalities
Inventory Operations

Add new sweets with name, category, price, and quantity

Delete sweets from inventory

Restock existing sweets

Search & Filter

Search sweets by exact name

Filter sweets by category (case-insensitive)

Filter sweets within a price range

Sales

Purchase sweets with automatic stock reduction

View

Display complete inventory at any time

🗂️ Project Structure
Sweet-Shop-Management-System/
├── README.md
├── Backend/
│   ├── src/
│   │   ├── app.ts                  # Core SweetShop business logic
│   │   ├── server.ts               # Express server entry point
│   │   ├── routes/
│   │   │   └── sweetRoutes.ts      # API endpoints
│   │   ├── types/
│   │   │   └── Sweet.ts            # Sweet type definition
│   │   ├── utils/
│   │   │   └── IdGenerator.ts      # Unique ID generator
│   │   └── tests/                  # Unit test cases
│   ├── package.json
│   ├── tsconfig.json
│   ├── jest.config.js
│   └── coverage/                   # Test coverage output
└── Frontend/
    ├── index.html                  # UI layout
    ├── script.js                   # Frontend logic
    └── style.css                   # Styling

⚙️ Setup Instructions
Prerequisites

Node.js (v14+)

npm

🔧 Backend Setup
# Clone repository
git clone https://github.com/anshshr/Sweet-Shop-Management-Incubyte

# Move to backend folder
cd Sweet-Shop-Management-Incubyte/Backend

# Install dependencies
npm install

# Start development server
npm run dev


📍 Server runs on: http://localhost:3000

🎨 Frontend Setup
# Move to frontend folder
cd Frontend


Open index.html directly in browser

OR use VS Code Live Server

Ensure backend is running on port 3000

🧪 Testing & Coverage
Run Tests
npm test

Coverage Report
npm run test:coverage


✔ 100% test coverage achieved

Metric	Coverage
Statements	100%
Branches	100%
Functions	100%
Lines	100%

Open detailed report:

Backend/coverage/index.html

🔗 API Endpoints
Method	Endpoint	Purpose
POST	/api/sweets/add	Add sweet
DELETE	/api/sweets/delete	Delete sweet
GET	/api/sweets/all	View all sweets
POST	/api/sweets/search	Search by name
POST	/api/sweets/category	Search by category
POST	/api/sweets/price	Filter by price
POST	/api/sweets/purchase	Purchase sweet
POST	/api/sweets/restock	Restock sweet
🖥️ Frontend Overview

The UI is designed as a dashboard-style interface:

Card-based actions

Responsive layout

Instant success/error feedback

Clear separation of management, sales, and search

Lightweight (no frontend frameworks)

📸 Screenshots available in the assets/ folder.

🛠️ Tech Stack
Backend

TypeScript

Node.js

Express.js

Jest (Testing)

CORS

Frontend

HTML5

CSS3 (Flexbox, Grid, Gradients)

Vanilla JavaScript

🧠 Core Logic

All business rules are handled by the SweetShop class:

Input validation for every operation

Case-insensitive searching

Automatic quantity management

Centralized error handling

Unique sweet ID generation

🤝 Contribution Guidelines

Fork the repository

Create a feature branch

Make changes with tests

Maintain full test coverage

Submit a pull request

📄 License

This project is licensed under the ISC License.

👩‍💻 Developer

Mayank Goyal 