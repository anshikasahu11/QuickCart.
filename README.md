# QuickCart - A simple eCommerce website

A modern, web-based platform to search, book, and shop for electronic gadgets efficiently. Built with React, Next.js, Tailwind CSS, and Node.js. Designed to mimic a real shopping workflow: browse products, add items to cart, manage quantities, and review your order — all inside a modern, responsive interface.


---

## Features

-   Responsive design for mobile, tablet, and desktop
-   Product listing with images, pricing, and details
-   Add to cart, remove, and quantity update
-   Customizable layouts and colors
-   Real-time cart state using React Context
-   Smooth page transitions and clean UI interactions
-   Deployed on Vercel for fast load times
-   Backend with Node.js + Express + MongoDB (for product data)


---
---

## 🚀 Live Demo

[Visit QuickCart](https://quick-cart-noms.vercel.app/)

---
---

## 🛠 Tech Stack

- Frontend: React.js, Next.js, Tailwind CSS  
- Backend: Node.js, Express.js  
- Database: MongoDB
- State Management: React Context
- Version Control: Git & GitHub  
- Deployment: Vercel

---
## Project Structure

QuickCart/
│
├── app/                # Next.js pages & routes
├── components/         # UI components
├── context/            # Cart context & provider
├── models/             # MongoDB models
├── server/             # Express backend
├── public/             # Static assets
├── styles/             # Global styles
└── README.md

---
## Getting Started

1. Clone the repo

    ```bash
    git clone https://github.com/anshikasahu11/QuickCart.
    cd QuickCart
    ```

2. Install dependencies

    ```bash
    npm install
    ```

3. Run locally

    ```bash
    npm run dev
    ```
    ---
   ## How the Cart Works (Short Technical Breakdown)
   The cart uses a global CartContext that stores:
   - Items in the cart
   - Total price
   - Adjustments to quantity
   - Remove item
   - Clear cart

   This ensures:
   - No prop-drilling
   - Instant updates across the app
   - Clean, predictable state logic
   ---
##  Improvements & Future Plans
- Add authentication (NextAuth / JWT)
- Add checkout with payment gateway
- Add admin panel to manage products
- Add wishlist & order history
- Improve Lighthouse performance scores
---


---

