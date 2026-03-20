# 🛍️ Frontend — Tienda Online (E-Commerce SPA)

> Modern single-page application for a full e-commerce platform built with React and Vite. Consumes a production REST API with PayPal payment integration.

![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=flat)

🌐 **Live demo:** [https://frontend-zlkp.onrender.com](https://frontend-zlkp.onrender.com)  
🌍 **Production site:** [www.interconectadosweb.es](https://www.interconectadosweb.es)  
⚙️ **Backend API:** [https://tienda-online-backend-xu3j.onrender.com](https://tienda-online-backend-xu3j.onrender.com)

---

## 📌 Overview

React + Vite SPA for a complete e-commerce platform. Features a full shopping experience including product browsing, cart management, user authentication and PayPal checkout — all connected to a production Node.js/PostgreSQL backend.

---

## 📸 Screenshots

> 📸 *Add your screenshots to the `/docs` folder and uncomment the lines below*

<!--
![Home page](docs/home.png)
![Products](docs/products.png)
![Cart](docs/cart.png)
![Checkout](docs/checkout.png)
-->

---

## ⚙️ Features

- ✅ Product catalog with search and filtering
- ✅ Shopping cart with real-time item count
- ✅ User registration and login (JWT auth)
- ✅ PayPal checkout integration
- ✅ Order history and tracking
- ✅ Responsive design — mobile and desktop
- ✅ Protected routes for authenticated users
- ✅ Global state management with Context API (auth + cart)

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React 18 | UI component library |
| Vite | Build tool and dev server |
| JavaScript (ES6+) | Application logic |
| Context API | Global auth and cart state |
| Axios / apiClient | HTTP layer for API communication |
| CSS Modules / CSS | Component styling |
| Render | Cloud deployment |

---

## 🏗️ Project Structure

```
tienda-online-frontend/
├── src/
│   ├── components/      # Reusable UI components
│   │   └── WhatsAppButton.jsx
│   ├── pages/           # Route-level pages
│   │   ├── Home.jsx     # Landing page (hero, services, pricing, testimonials)
│   │   ├── Products.jsx
│   │   └── Checkout.jsx
│   ├── context/         # Global state
│   │   ├── AuthContext.jsx   # useAuth — isAuthenticated, user
│   │   └── CartContext.jsx   # useCart — itemCount, addToCart
│   ├── api/
│   │   └── apiClient.js # Centralized HTTP client
│   └── main.jsx         # App entry point
├── public/
│   └── index.html
├── .env                 # Environment variables (VITE_ prefix)
└── vite.config.js
```

---

## 🚀 Getting Started

### Prerequisites

```bash
Node.js 18+
```

### Installation

```bash
# Clone the repository
git clone https://github.com/david323902/tienda-online-frontend.git
cd tienda-online-frontend

# Install dependencies
npm install

# Configure environment variables
cp .env.example .env
# Edit .env — set your backend API URL
```

### Environment Variables

```env
VITE_API_URL=https://tienda-online-backend-xu3j.onrender.com
VITE_FALLBACK_WHATSAPP_NUMBER=your_whatsapp_number
```

### Run in development

```bash
npm run dev
# App runs at http://localhost:5173
```

### Build for production

```bash
npm run build
```

---

## 🔗 Related Repository

- **Backend API:** [backend-de-tienda-online](https://github.com/david323902/backend-de-tienda-online) — Node.js + Express.js + PostgreSQL REST API

---

## 👤 Author

**Johan David Toro Ortiz** — full-stack development, React SPA architecture, API integration, state management, deployment  
📧 davidortiz634@gmail.com · [LinkedIn](https://www.linkedin.com/in/TU-URL-AQUI) · [GitHub](https://github.com/david323902)

---

## 🇪🇸 Descripción en español

Aplicación React + Vite para una tienda online completa, desplegada en Render y accesible en producción en [interconectadosweb.es](https://www.interconectadosweb.es). Incluye catálogo de productos, carrito de compras, autenticación de usuarios con JWT, integración de pagos con PayPal y gestión de estado global con Context API. Se comunica con una API REST en Node.js/PostgreSQL desplegada por separado.
