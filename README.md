# 🍬 Sweet Shop Management System

A comprehensive Sweet Shop Management System built using **TypeScript** for the backend and **vanilla JavaScript** for the frontend. This application allows complete management of sweet inventory with CRUD operations, search functionality, and full test coverage.

## ✨ Features
- **Add Sweet** – Add new sweets with name, category, price, and quantity  
- **Delete Sweet** – Remove sweets from inventory  
- **Search by Name** – Find sweets using exact name  
- **Search by Category** – Case-insensitive category filtering  
- **Search by Price Range** – Filter sweets within a price range  
- **Purchase Sweet** – Buy sweets with automatic stock reduction  
- **Restock Sweet** – Increase stock quantity  
- **View All Sweets** – Display complete inventory
  
## 🏗️ Project Structure
Sweet-Shop-Management-System
├── README.md
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
│ ├── package.json
│ ├── tsconfig.json
│ ├── jest.config.js
│ └── coverage/ # Test coverage reports
└── Frontend/
├── index.html # UI
├── script.js # Frontend logic
└── style.css # Styling

### Prerequisites
- Node.js (v14 or higher)
- npm

### 🔧 Backend Setup
git clone https://github.com/Mgoyal2711/Sweet-management-system
cd Sweet-management-system/Backend
npm install
npm run dev
📍 Server runs at: http://localhost:3000

###🎨 Frontend Setup
cd Frontend
Open index.html in a browser
OR use Live Server in VS Code
Ensure backend is running on port 3000

###🧪 Testing
Run Tests
cd Backend
npm test
Run Coverage
npm run test:coverage
Watch Mode
npm run test:watch

###📊 Test Coverage Report
✔ 100% Code Coverage Achieved
Metric	Coverage
Statements	100%
Branches	100%
Functions	100%
Lines	100%

###Test files include:
Add Sweet tests
Delete Sweet tests
Search (Name, Category, Price)
Purchase tests
Restock tests
ID Generator tests
View report:
Backend/coverage/index.html

###🌐 API Endpoints
Method	Endpoint	Description
POST	/api/sweets/add	Add a sweet
DELETE	/api/sweets/delete	Delete sweet
GET	/api/sweets/all	View all sweets
POST	/api/sweets/search	Search by name
POST	/api/sweets/category	Search by category
POST	/api/sweets/price	Search by price
POST	/api/sweets/purchase	Purchase sweet
POST	/api/sweets/restock	Restock sweet

###💻 Frontend Preview
Main Interface
Sweet Added
UI Highlights
Responsive design
Real-time feedback
Card-based dashboard
Clean & intuitive UX
Client-side validation

###🛠️ Tech Stack
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

###🎯 Business Logic
The SweetShop class handles:
Input validation
Inventory tracking
Error handling
Case-insensitive search
Unique ID generation

###👨‍💻 Developer
Mayank Goyal


