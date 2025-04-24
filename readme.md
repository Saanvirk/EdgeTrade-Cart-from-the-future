Edge Trade - ISDN 3150 Mid Term Mini Project

A React-based product showcase app offering an immersive and futuristic shopping experience tailored for mobile devices. This app features interactive 3D product models, detailed product pages, and a fully functional shopping cart, all optimized for an iPhone 14 Pro viewport.

Project Overview

Edge Trade is designed as a virtual souvenir shop where users can explore products through interactive 3D visuals and easily manage their purchases. The app combines modern web technologies to deliver smooth animations, intuitive navigation, and a sleek AI-enhanced interface.

Main Features

3D Product Viewer
Users can interact with 3D models of products, including auto-rotation and zoom controls, powered by @react-three/fiber and @react-three/drei.

Dynamic Product Details

Each product page displays comprehensive information such as name, price, availability, and description, with options to add items to the cart.

AI Chat Interface (Coming Soon)

A placeholder for an AI-driven chat feature aimed at assisting users with shopping inquiries and recommendations.

Animated Splash and Branding

The app launches with an engaging animated splash screen and brand introduction before entering the main shopping interface.

Shopping Cart System

Users can add products to their cart, view cart contents with item counts, and proceed towards checkout.

Technologies Used

React for building the user interface

Vite as the development server and build tool for fast reloads

React Three Fiber and Three.js for rendering 3D models

React Spring for smooth animations and transitions

JavaScript and CSS for app logic and styling

Getting Started
Installation
Clone the repository:
bash
git clone https://github.com/your-username/edge-trade.git
cd ISDN_3150_Mid-Term
Install the dependencies:

bash
npm install
Launch the development server:

bash
npm run dev
Open the app in your browser at http://localhost:3000. 

For the best experience, enable mobile device emulation in your browser’s developer tools and set the viewport to iPhone 14 Pro dimensions (430 x 932).

Folder Structure
src/components/ — Contains reusable UI components such as product pages and shopping cart

src/3DModels/ — Stores .glb files for 3D product models

src/ProductPage.js — Handles product display and 3D model interaction

src/App.js — Main app component managing routing, state, and rendering

How to Use
1.) Launch the app and tap the "Start" button to begin.

2.) Navigate through the splash and brand introduction screens.

3.)Browse products and tap any item to view its details and interact with its 3D model.

4.)Use zoom and rotation controls to examine products closely.

5.)Add desired products to your shopping cart.

6.)Access the cart to review selected items and their quantities.

7.)(Future) Use the AI chat feature to get shopping assistance.



Contributors
Jimmy Wu — Lead Developer

Saanvi — Prompt Engineer
