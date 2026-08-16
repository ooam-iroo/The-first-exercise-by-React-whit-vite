<div align="center">

# 🛒 React Ecommerce Platzi

### E-Commerce Application with React & Platzi API

<p>
  <img src="https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/Vite-5-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/Tailwind_CSS-3-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/MUI-6-007FFF?style=for-the-badge&logo=mui&logoColor=white" alt="Material UI">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

</div>

---

## 📌 About

**React Ecommerce Platzi** is an e-commerce application built with **React** and **Vite**, using the **Platzi Fake Store API** for product data.

The project focuses on building a complete frontend shopping experience while practicing modern React ecosystem tools.

---

## ✨ Features

* 🛍️ Product browsing
* 🔎 Product discovery
* 🛒 Shopping cart
* 🔐 Authentication flow
* 👤 User management
* 🧭 Client-side routing
* 📝 Form handling and validation
* 🔔 Toast notifications
* 💾 Global state management
* 📡 API data fetching and caching

---

## 🧰 Tech Stack

| Technology                  | Purpose                     |
| --------------------------- | --------------------------- |
| ⚛️ **React 18**             | UI development              |
| ⚡ **Vite 5**                | Development & build tooling |
| 🎨 **Tailwind CSS 3**       | Styling                     |
| 🖼️ **Material UI 6**       | UI components & icons       |
| 🔄 **TanStack React Query** | Server-state management     |
| 🌐 **Axios**                | HTTP requests               |
| 🧭 **React Router DOM**     | Routing                     |
| 🐻 **Zustand**              | Global state management     |
| 📝 **React Hook Form**      | Form management             |
| ✅ **Zod**                   | Schema validation           |
| 🍪 **js-cookie**            | Cookie handling             |
| 🔐 **JOSE**                 | JWT / token handling        |
| 🔔 **React Toastify**       | Notifications               |

---

## 🏗️ Architecture

```text
                         ┌─────────────────┐
                         │   React App     │
                         └────────┬────────┘
                                  │
              ┌───────────────────┼───────────────────┐
              │                   │                   │
              ▼                   ▼                   ▼
       ┌─────────────┐     ┌─────────────┐     ┌─────────────┐
       │   Routing   │     │    State    │     │     Forms   │
       │ React Router│     │   Zustand   │     │ RHF + Zod   │
       └─────────────┘     └─────────────┘     └─────────────┘
                                  │
                                  ▼
                         ┌─────────────────┐
                         │ React Query     │
                         └────────┬────────┘
                                  │
                                  ▼
                         ┌─────────────────┐
                         │     Axios       │
                         └────────┬────────┘
                                  │
                                  ▼
                         ┌─────────────────┐
                         │   Platzi API    │
                         └─────────────────┘
```

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/ooam-iroo/The-first-exercise-by-React-whit-vite.git
```

Enter the project:

```bash
cd The-first-exercise-by-React-whit-vite
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

---

## 🏭 Production Build

Create a production build:

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

---

## 🧹 Lint

Run ESLint:

```bash
npm run lint
```

---

## 📂 Project Structure

```text
React-Ecommerce-Platzi
│
├── public/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── services/
│   ├── store/
│   └── ...
│
├── index.html
├── package.json
├── vite.config.js
├── tailwind.config.js
├── postcss.config.js
└── eslint.config.js
```

---

## 🔗 API

The application is designed around the **Platzi Fake Store API** for retrieving e-commerce data.

API requests are handled through **Axios**, while **TanStack React Query** manages server-side data and caching.

---

## 🎯 Learning Goals

This project focuses on practicing:

* React component architecture
* API integration
* Server-state management
* Global state management
* Client-side routing
* Authentication
* Form validation
* Modern frontend tooling

---

<div align="center">

### ⚛️ React · 🛒 E-Commerce · ⚡ Vite

**Building modern interfaces, one component at a time.**

</div>
