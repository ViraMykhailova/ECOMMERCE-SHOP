# Ecommerce-store Product Page + Cart

An Ecommerce Website With React JS And Tailwind CSS using Fake Store API

## Setup
To install the application, please run two commands:
```bash
npm i
npm run start
```

## Pages
#### **Home Page:**
- Fetches the Products from Fake store API (consumes Product Context).
- Clicking on the logo redirects to the home page.
- Includes a button in the header leading to the order cart.
- Allows adding the product to the cart by clicking the "+" button.
- Product details Page opens when clicking on an eye button.
  
#### **Product Detail Page:**
- Displays information about the Product.
- Allows adding the Product to the cart.
  
#### **Cart Component:**
- Displays the quantity of items added to the cart.
- If there are orders in the cart, allows increasing, decreasing, and removing items.
- Shows the total amount for the order.
- After clicking the "Checkout" button, clears the cart and redirects to the home page.

## Tech Stack

- **Library:** ReactJS
- **Visual:** Tailwind
- **State manager:** Context
- **Navigation:** React Router