# 🛍️ ShopMe E-Commerce

**ShopMe** is a modern, scalable, and secure e-commerce platform developed using React for the frontend and AWS serverless services for the backend. It supports user authentication, product browsing, cart management, and order placement.

---

## 📌 Features

- 🔐 **User Authentication** with AWS Cognito
- 🛒 **Product Catalog** with filtering and search
- 🧾 **Cart & Checkout** functionality
- 📦 **Order Management**
- ⚡ **Serverless Backend** using AWS Lambda & API Gateway
- 🌐 **CI/CD & Hosting** via AWS Amplify
- 🔐 **Secure Access** using IAM policies

---

## 🚀 Live Demo

The application is hosted on AWS Amplify.  
👉 **Live Site:** _[Provide URL once hosted]_

---

## 🏗️ Project Structure




shopMe-ECommerce/ ├── public/ ├── src/ │ ├── assets/ │ ├── components/ │ ├── pages/ │ ├── redux/ │ ├── App.js │ └── index.js ├── .gitignore ├── package.json └── README.md



---

## 🛠️ Technologies Used

### Frontend:
- **React.js**
- **Redux Toolkit**
- **React Router**
- **Tailwind CSS**

### Backend (via AWS):
- **AWS Amplify** – Hosting & CI/CD
- **Amazon Cognito** – User authentication
- **Amazon API Gateway** – API endpoint management
- **AWS Lambda** – Serverless business logic
- **AWS IAM** – Role-based access control

---

## ☁️ AWS Deployment Architecture




Commands:
npm install -g @aws-amplify/cli
amplify configure
amplify init
amplify add auth
amplify push
npm start



