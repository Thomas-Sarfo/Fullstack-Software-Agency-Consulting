# 🌐 Fullstack Software Agency Consulting  

![React](https://img.shields.io/badge/Frontend-React-blue?logo=react)  
![Node.js](https://img.shields.io/badge/Backend-Node.js-green?logo=node.js)  
![MongoDB](https://img.shields.io/badge/Database-MongoDB-brightgreen?logo=mongodb)  
![Firebase](https://img.shields.io/badge/Auth-Firebase-orange?logo=firebase)  
![Stripe](https://img.shields.io/badge/Payments-Stripe-blueviolet?logo=stripe)  


A **fullstack software agency web application** built with React, Node.js, MongoDB, and Firebase.  
It includes authentication, payments, and an admin dashboard — providing a scalable foundation for modern web applications.  

---

## 🚀 Features  

- 🎨 Responsive UI (React-Bootstrap + Material-UI)  
- 🔑 Firebase Authentication (login, signup, reset email, OTP, subscription)  
- 🗄️ MongoDB + Express backend  
- 💳 Stripe payments (future expansion planned)  
- 📝 Job Portal (apply, review, manage jobs)  
- ⭐ Reviews & Purchases (users can purchase services and leave feedback)  
- 👤 User Dashboard (purchase history, profile, order status)  
- 🧑‍💻 Admin Dashboard (CRUD operations, manage orders, assign admin)  
- ⚡ Optimized build with Webpack & FileSaver  
- 🚀 Future plans: **Redux**, **GraphQL**, and **TypeScript**  

---

## 🧰 Tech Stack  

| Category       | Technologies |
|----------------|-------------|
| **Frontend**   | React, JavaScript (ES6), Context API, React Router v6 |
| **UI Library** | Material-UI (MUI), React-Bootstrap |
| **Backend**    | Node.js, Express |
| **Database**   | MongoDB, Firestore |
| **Auth**       | Firebase Authentication |
| **Payments**   | Stripe |
| **Build Tools**| Webpack, FileSaver |
| **Other**      | ESLint, Prettier |

---

## ⚙️ Installation & Setup  

## Install dependencies
npm install
# or
yarn install


## Setup Firebase & Stripe

1. Create a Firebase Console project for authentication.

2. Setup MongoDB for your database.

3. Setup Stripe for payments.

## Add Environment Variables

Create a .env file in the root folder:

REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_STRIPE_KEY=your_stripe_key
MONGO_URI=your_mongodb_connection_string

## Firebase Config

Create a firebaseConfig.jsx file in the root and add your Firebase config.

## Start the project

npm start
# or
yarn start

🤝 Contributing

Contributions are welcome! 🎉

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

Don’t forget to ⭐ this repo if you found it helpful!
