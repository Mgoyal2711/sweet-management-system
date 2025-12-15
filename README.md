# 🍬 Sweet Shop Management System

A **comprehensive Sweet Shop Management System** built using **TypeScript** for the backend and **vanilla JavaScript** for the frontend.  
This application enables complete inventory management with **CRUD operations**, **advanced search functionality**, and **100% test coverage**.

---

## ✨ Features

- **Add Sweet** – Add new sweets with name, category, price, and quantity  
- **Delete Sweet** – Remove sweets from inventory  
- **Search by Name** – Find sweets using exact name  
- **Search by Category** – Case-insensitive category filtering  
- **Search by Price Range** – Filter sweets within a price range  
- **Purchase Sweet** – Buy sweets with automatic stock reduction  
- **Restock Sweet** – Increase stock quantity  
- **View All Sweets** – Display complete inventory  

---

## 🏗️ Project Structure

Sweet-Shop-Management-System
│
├── README.md
│
├── Backend/
│ ├── src/
│ │ ├── app.ts # SweetShop business logic
│ │ ├── server.ts # Express server setup
│ │ ├── routes/
│ │ │ └── sweetRoutes.ts # API routes
│ │ ├── types/
│ │ │ └── Sweet.ts # Sweet interface
│ │ ├── utils/
│ │ │ └── IdGenerator.ts # Unique ID generator
│ │ └── tests/ # Unit test suite
│ │
│ ├── package.json
│ ├── tsconfig.json
│ ├── jest.config.js
│ └── coverage/ # Test coverage reports
│
└── Frontend/
├── index.html # UI
├── script.js # Frontend logic
└── style.css # Styling

yaml
Copy code

---

## 📋 Prerequisites

- **Node.js** (v14 or higher)
- **npm**

---

## 🔧 Backend Setup

```bash
git clone https://github.com/Mgoyal2711/Sweet-management-system
cd Sweet-management-system/Backend
npm install
npm run dev
📍 Server runs at:
http://localhost:3000

🎨 Frontend Setup
bash
Copy code
cd Frontend
Open index.html directly in a browser OR

Use Live Server in VS Code

Ensure the backend is running on port 3000

🧪 Testing
Run Tests
bash
Copy code
cd Backend
npm test
Run Coverage
bash
Copy code
npm run test:coverage
Watch Mode
bash
Copy code
npm run test:watch
📊 Test Coverage Report
✔ 100% Code Coverage Achieved

Metric	Coverage
Statements	100%
Branches	100%
Functions	100%
Lines	100%

Test Files Include
Add Sweet tests

Delete Sweet tests

Search tests (Name, Category, Price Range)

Purchase Sweet tests

Restock Sweet tests

ID Generator tests

📂 Coverage Report Location:
Backend/coverage/index.html

🌐 API Endpoints
Method	Endpoint	Description
POST	/api/sweets/add	Add a sweet
DELETE	/api/sweets/delete	Delete a sweet
GET	/api/sweets/all	View all sweets
POST	/api/sweets/search	Search by name
POST	/api/sweets/category	Search by category
POST	/api/sweets/price	Search by price range
POST	/api/sweets/purchase	Purchase sweet
POST	/api/sweets/restock	Restock sweet

💻 Frontend Highlights
Responsive design

Card-based dashboard

Real-time user feedback

Client-side validation

Clean and intuitive UI

🛠️ Tech Stack
Backend
TypeScript

Node.js

Express.js

Jest

CORS

Frontend
HTML5

CSS3 (Flexbox & Grid)

Vanilla JavaScript

🎯 Business Logic
The SweetShop class is responsible for:

Input validation

Inventory management

Error handling

Case-insensitive searching

Unique ID generation

👨‍💻 Developer
Mayank Goyal

