# Nikey — Modern Footwear & E-Commerce Web Platform

![Vercel Deployment](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

A responsive, high-performance frontend Nike shoe e-commerce web application. Built with a dual-interface architecture featuring a customer storefront for product browsing alongside an integrated administrative portal for inventory and layout management.

---

## Visual Tour & Interface Previews

### User Side Experience
Customer storefront for product catalog browsing, detailed item views, and cart management.

| Storefront Landing & Catalog | Product & Cart Showcase |
| :---: | :---: |
| ![User Side Landing Page](https://github.com/user-attachments/assets/ea6a141c-4049-4d86-9345-bb3694a40829) | ![User Side Shopping View](https://github.com/user-attachments/assets/3cf48c97-4235-4a82-b112-ca2d3d3071fe) |

### Admin Side Portal
Administrative dashboard to inspect product inventories, store metrics, and catalog listings.

| Admin Dashboard Overview | Admin profile page |
| :---: | :---: |
| ![Admin Side Dashboard](https://github.com/user-attachments/assets/c5a49f0f-de6e-4945-a941-47c19f8d50c1) | ![Admin Side profile page](https://github.com/user-attachments/assets/42813b90-2c21-4300-9ba4-fd3035676552) |

---

## Features Showcase

### User Experience (Storefront)
- **Dynamic Catalog:** Interactive product grid with category filtering, real-time search, and detailed item models.
- **Cart & Order System:** Client-side cart state management with instant quantity updates and pricing summary calculations.
- **Responsive Layout:** Mobile-first responsive views optimized across handheld, tablet, and desktop viewports.
- **Micro-Interactions:** Smooth UI transitions, hover states, and dynamic view switches.

### Admin Experience (Dashboard)
- **Catalog Navigation:** Dedicated administrative interface (`/admin`) to inspect product inventories.
- **Metric Insights:** Organized dashboard widgets displaying active listings and stock states.
- **Layout Control:** Direct client-side control over store collections and product presentation settings.

---

## Tech Stack

| Domain | Technology / Tool | Badge |
| :--- | :--- | :--- |
| **Frontend Framework** | React.js | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) |
| **Styling** | Tailwind CSS / CSS Modules | ![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) |
| **Routing** | React Router | ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=flat-square&logo=react-router&logoColor=white) |
| **Deployment** | Vercel Platform | ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) |

---

## System Architecture

```text
shoe-nikey-frontend/
├── Storefront Engine (Public Views)
│   ├── Hero Showcase & Trending Collections
│   ├── Dynamic Shoe Filtering & Product Grid
│   └── Shopping Cart & Order Summary
└── Administrative Engine (`/admin`)
    ├── Product Catalog Overview
    └── Inventory Listing Dashboard
