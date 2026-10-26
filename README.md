# 🍕 Fast React Pizza Co. — Pizza Ordering App

A modern, interactive pizza ordering application built with React. The project provides a complete pizza ordering experience, allowing users to explore a dynamic menu, manage their cart, place orders, and track their order status through a clean and responsive interface.

Fast React Pizza Co. combines reusable UI components with client-side routing, centralized state management, and asynchronous API integration.

## 🌐 Live Demo

[View Live Demo](YOUR_LIVE_DEMO_URL)

## 📸 Project Preview
<img width="1355" height="628" alt="Image" src="https://github.com/user-attachments/assets/60c7a453-4d1f-4e85-be86-9d94ee6a6b2b" />

----------
<img width="1362" height="630" alt="Image" src="https://github.com/user-attachments/assets/64888d07-91f3-4af0-8312-c24d2d13207c" />

----------
<img width="1354" height="632" alt="Image" src="https://github.com/user-attachments/assets/b1899ca9-3e5b-40a2-a779-952519ef9c5a" />

----------
<img width="1352" height="630" alt="Image" src="https://github.com/user-attachments/assets/dd7832b5-000a-4d34-ae55-bbf63ebaecda" />


## ✨ Key Features

- **Dynamic Pizza Menu:** Browse available pizzas and their details fetched from an external API.
- **Interactive Shopping Cart:** Add pizzas, remove items, adjust quantities, and view the total price.
- **Order Placement:** Submit orders with customer information and phone number validation.
- **Automatic Address Detection:** Retrieve the user's location using browser geolocation and convert coordinates into a readable address.
- **Order Tracking:** View order details and check order status using an order ID.
- **Priority Orders:** Upgrade an existing order to priority handling for an additional 20% charge.
- **Responsive Interface:** Navigate and interact with the application across different screen sizes.
- **Loading and Error States:** Handle asynchronous operations and provide feedback during data fetching and order processing.

## 🛠️ Technologies & Tools

- **React 18** — Building interactive user interfaces with reusable components and hooks.
- **JavaScript (ES6+)** — Application logic and data manipulation.
- **Vite** — Development server and production build tooling.
- **React Router DOM** — Client-side routing, data loading, form actions, and navigation.
- **Redux Toolkit** — Managing shared application state.
- **React Redux** — Connecting React components to the Redux store.
- **Tailwind CSS** — Styling the interface with utility-first CSS classes.
- **Fetch API** — Communicating with external APIs.
- **ESLint & Prettier** — Code linting and formatting.

## 💡 React Concepts & Implementation

- **Component-Based Development:** Organizing the interface into reusable components.
- **State Management:** Managing cart items, quantities, totals, and user information with Redux Toolkit.
- **Routing & Navigation:** Implementing routes for the menu, cart, order creation, and order details.
- **Data Loading & Form Actions:** Using React Router loaders, actions, and related hooks to handle route data and form submissions.
- **Asynchronous JavaScript:** Fetching remote data and handling asynchronous operations.
- **API Integration:** Retrieving menu data, submitting orders, and accessing geocoding services.
- **Form Handling & Validation:** Collecting customer details and validating phone numbers before order submission.
- **Geolocation:** Using the browser's Geolocation API and reverse geocoding to obtain a readable address.

## 🔄 Application Workflow

1. Users explore the available pizzas on the menu.
2. They add their preferred items to the cart and adjust quantities.
3. They proceed to checkout and enter their contact information.
4. The application creates the order and returns an order ID.
5. Users can view their order details, track its status, or upgrade it to priority handling.

## 🔌 API Integration

The application communicates with external services to retrieve pizza menu data, process orders, and convert geographic coordinates into readable addresses.

- **Pizza Ordering API:** Provides menu data and order-related operations.
- **BigDataCloud Reverse Geocoding API:** Converts geographic coordinates into a readable address.

## 📌 Project Scope

The application focuses on the client-side pizza ordering experience and integration with external APIs. Cart and user information are managed through Redux Toolkit, without persistent storage configured for the Redux state.

---

Built as a hands-on React project to practice modern front-end development, routing, state management, form handling, and API integration.
