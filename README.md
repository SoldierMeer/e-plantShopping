# 🌿 e-plantShopping - Paradise Nursery

## 📌 Project Name
e-plantShopping

## 🌱 Overview
e-plantShopping is a React-based e-commerce web application for selling indoor plants.  
It is designed as a practice project to understand React, Redux Toolkit, and state management in real-world applications.

The application allows users to browse plants, add them to a shopping cart, update quantities, and view total cost dynamically.

---

## 🚀 Features

### 🛒 Product Listing Page
- Displays multiple categories of houseplants
- Each plant shows:
  - Image thumbnail
  - Name
  - Price
- "Add to Cart" functionality
- Button disables after adding item
- Dynamic cart update

### 🧺 Shopping Cart Page
- Shows all selected products
- Increase / decrease quantity
- Remove items from cart
- Displays:
  - Unit price
  - Total price per item
  - Grand total amount
- Checkout button (Coming Soon)
- Continue Shopping button

### 🔢 Cart System
- Fully managed using Redux Toolkit
- Supports:
  - Add item
  - Remove item
  - Update quantity

---

## 🧠 Tech Stack

- React.js
- Redux Toolkit
- React Redux
- JavaScript (ES6+)
- CSS3
- Vite

---

## 🏗️ Project Structure
src/
│
├── Components/
│ ├── AboutUs.jsx
│ ├── CartItem.jsx
│ ├── CartSlice.jsx
│ ├── ProductList.jsx
│
├── App.jsx
├── App.css
├── main.jsx
├── store.js


---

## 🌐 Live Demo
https://SoldierMeer.github.io/e-plantShopping/

---

## 📦 Installation & Setup

```bash
git clone https://github.com/YOUR_USERNAME/e-plantShopping.git
cd e-plantShopping
npm install
npm run dev
