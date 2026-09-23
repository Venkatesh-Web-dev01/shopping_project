# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

# 🛒 UrbanCart – Modern E-Commerce Shopping App

**UrbanCart** is a modern and responsive e-commerce web application built with **React.js and Vite**. It provides a clean shopping interface where users can browse products, filter products by category, manage quantities, add items to a shopping cart, view the cart total, and proceed through a checkout form.

## ✨ Features

* 🛍️ Browse featured products
* 🔎 Product search interface
* 🏷️ Category-based product filtering
* 💰 Product pricing and discount display
* ⭐ Product ratings
* 📦 Stock availability information
* ➕➖ Product quantity controls
* 🛒 Add products to cart
* 🧾 Dynamic cart and subtotal calculation
* 💳 Checkout form
* 📱 Responsive and modern user interface
* ⚡ Fast development and build environment using Vite

## 🧰 Technologies Used

* **React.js** – UI development
* **Vite** – Development server and build tool
* **JavaScript (ES6+)** – Application logic
* **HTML5** – Structure
* **CSS3** – Styling and responsive layout
* **ESLint** – Code quality and linting

The project is configured with React and the Vite React plugin.

## 🛍️ Products

The application currently demonstrates products across categories such as:

* Electronics
* Fashion
* Accessories

Example products include:

* Wireless Earbuds
* Running Shoes
* Smart Watch
* Bluetooth Speaker
* Leather Backpack
* Travel Mug

Each product includes information such as price, previous price, category, rating, stock, discount, and product image.

## 🛒 Shopping Cart

Users can add products to the cart and increase or decrease the quantity of each item.

The cart dynamically calculates the total based on:

**Product Price × Quantity**

Users can also remove products by reducing their quantity to zero.

## 🔎 Product Filtering

UrbanCart provides category filters including:

* All
* Electronics
* Fashion
* Accessories

Selecting a category dynamically updates the displayed products.

## 💳 Checkout

The application includes a checkout section where users can enter:

* Full Name
* Email
* Shipping Address
* Payment Method

A cart drawer displays the selected products and calculated total before placing an order.

## 📂 Project Setup

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project

```bash
cd YOUR_PROJECT_FOLDER
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

The project uses Vite as its development server.

### 5. Build for production

```bash
npm run build
```

### 6. Preview the production build

```bash
npm run preview
```

## 🏗️ Project Structure

```text
UrbanCart/
│
├── src/
│   ├── App.jsx
│   ├── main.jsx
│   └── ...
│
├── public/
│
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
├── eslint.config.js
├── .gitignore
└── README.md
```

## ⚡ Development

Vite provides a fast development environment with Hot Module Replacement (HMR), allowing changes to appear quickly during development.

The ESLint configuration includes recommended JavaScript rules along with React Hooks and React Refresh rules.

## 🎯 Project Objective

The objective of UrbanCart is to demonstrate the development of a modern e-commerce interface using React. The project focuses on component-based UI development, dynamic state management, product filtering, cart operations, and a responsive shopping experience.

## 🚀 Future Improvements

Possible future enhancements include:

* User authentication
* Backend API integration
* MongoDB/d
