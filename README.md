# 🛒 UrbanCart – Modern E-Commerce Shopping App

**UrbanCart** is a modern and responsive e-commerce web application built with **React.js and Vite**. It provides a clean shopping interface where users can browse products, filter products by category, manage quantities, add items to a shopping cart, view the cart total, and proceed through a checkout form.## 🎨 Styling & Responsive Design

<div align="center">

# 🛒 UrbanCart – Modern E-Commerce Shopping App

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

*A modern and responsive e-commerce web application built with React.js, Vite, and CSS3.*

</div>

---
---


<section class="features-section">
  <h2>✨ Features</h2>
  <ul class="features-list">
    <li>🛍️ Browse featured products</li>
    <li>🔎 Product search interface</li>
    <li>🏷️ Category-based product filtering</li>
    <li>💰 Product pricing and discount display</li>
    <li>⭐ Product ratings</li>
    <li>📦 Stock availability information</li>
    <li>➕➖ Product quantity controls</li>
    <li>🛒 Add products to cart</li>
    <li>🧾 Dynamic cart and subtotal calculation</li>
    <li>💳 Checkout form</li>
    <li>📱 Responsive and modern user interface</li>
    <li>⚡ Fast development and build environment using Vite</li>
  </ul>
</section>


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
