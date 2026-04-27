# read-me-checkpoint
Here's a clean README for your project:

---

# Lyrine Abaya — E-Commerce Web Application

A full-stack e-commerce web application for an abaya clothing brand, built as a final project for a Full Stack Web Development course.

## Tech Stack

**Backend:** Node.js, Express.js, MongoDB (Mongoose)
**Frontend:** React.js (Vite)

## Features

**Customer Side**
- Browse and filter abayas by category
- View product details with size and color selection
- Add products to cart and manage quantities
- Place orders with shipping information
- View order history and status

**Admin Side**
- Secure admin dashboard
- Manage products (add, edit, delete, upload images)
- Manage categories
- View and update order statuses

## Project Structure

```
├── backend/
│   ├── controllers/     # Auth, product, cart, order, category logic
│   ├── models/          # Mongoose schemas
│   ├── middleware/       # Auth & admin protection, file upload
│   └── routes/          # All API routes
└── frontend/
    └── src/
        ├── pages/       # Home, Products, Cart, Orders, Admin, Auth
        └── assets/
```


That's everything a reader needs to understand the project at a glance.
