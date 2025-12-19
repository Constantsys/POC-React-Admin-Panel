# React Admin Dashboard – CRUD Panel

## About
This project is a **complete React Admin Dashboard application** designed to handle **CRUD (Create, Read, Update, Delete)** operations for multiple modules.

The dashboard is built with **React**, **Material UI**, and **Redux**, and includes modern features such as **Data Grid tables**, **light & dark theme modes**, **protected routes**, and a scalable folder structure suitable for enterprise applications.

---

## Tech Stack
- **ReactJS** – Frontend framework
- **Material UI (MUI)** – UI components & theming
- **MUI Data Grid** – Advanced tables
- **Redux Toolkit** – State management
- **React Router DOM** – Routing
- **CSS / SCSS** – Styling
- **JavaScript (ES6+)**

---

## Key Features
- Full CRUD operations
- Admin authentication (login & register)
- Protected routes
- Light & Dark theme mode
- Reusable Data Grid tables
- Dashboard analytics (charts & stats)
- Modular and scalable architecture
- Responsive UI

---

## Project Structure

│
├── src/
│ ├── data/
│ │ └── Static/mock data for tables & charts
│ │
│ ├── pages/
│ │ ├── DashboardAdmin.jsx
│ │ ├── LoginAdmin.jsx
│ │ ├── Login.css
│ │ ├── RegisterAdmin.jsx
│ │ └── Register.css
│ │
│ ├── ProtectedRoute/
│ │ └── RoutesProtect.jsx
│ │
│ ├── redux/
│ │ ├── slices/
│ │ │ ├── category/
│ │ │ │ └── categorySlice.js
│ │ │ ├── tab/
│ │ │ │ └── tabSlice.js
│ │ │ └── store/
│ │ │ └── store.js
│ │
│ ├── scenes/
│ │ ├── bar/
│ │ ├── calendar/
│ │ ├── category/
│ │ ├── contacts/
│ │ ├── dashboard/
│ │ ├── faq/
│ │ ├── global/
│ │ ├── invoices/
│ │ ├── line/
│ │ ├── pie/
│ │ ├── productList/
│ │ ├── team/
│ │ └── users/
│ │
│ ├── App.js
│ └── index.js
│
├── package.json
├── README.md
└── .gitignore


---

## Folder Details

### `pages/`
Authentication and main admin pages:
- Login
- Register
- Admin Dashboard

---

### `ProtectedRoute/`
Handles route protection:
- Restricts unauthorized users
- Ensures only authenticated admins access dashboard routes

---

### `redux/`
State management using Redux Toolkit:
- Feature-based slices
- Centralized store configuration

---

### `scenes/`
Main dashboard modules:
- Users management
- Product list
- Categories
- Invoices
- Calendar
- Charts (bar, line, pie)
- Team & contacts

Each scene represents a CRUD-capable module or dashboard view.

---

### `data/`
Contains mock/static data for charts and tables.

---

## Light & Dark Mode
- Theme switching implemented using **Material UI theming**
- Global theme control via Redux or context
- Fully responsive to user preference

---
