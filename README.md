# 🎓 E-Learning Platform

A full-stack E-Learning platform built using the MERN stack that enables users to explore online courses, purchase learning resources, and access educational content through a user-friendly interface.

## 📌 About the Project

The E-Learning Platform is a web application designed to simplify online education by providing course discovery, user authentication, and payment functionality. It combines a React-based frontend with a Node.js and Express backend, using MongoDB to manage application data.

The platform also integrates Razorpay for payment processing and email notifications to support account verification and course-related updates.

## ✨ Features

- 🔐 **User Authentication:** Secure registration and login with JWT-based authentication and authorization.
- 📚 **Course Management:** Organizes course information and supports course-related operations.
- 💳 **Online Payments:** Integrates Razorpay for course purchases and payment processing.
- 🛠️ **Admin Dashboard:** Supports administrative management of courses, users, and enrollments.
- 📧 **Email Notifications:** Sends account verification, enrollment, and order-related emails.
- 📱 **Responsive Interface:** Provides a user-friendly experience across different screen sizes.
- 🔄 **RESTful APIs:** Connects the frontend and backend through structured API endpoints.

## 🛠️ Tech Stack

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js
- REST APIs
- JSON Web Tokens (JWT)

### Database
- MongoDB

### Integrations
- Razorpay Payment Gateway
- Email notification service

### Tools
- Git and GitHub
- npm

## 🏗️ Application Architecture

The application follows a client-server architecture:

1. **Frontend:** React.js provides the user interface for interacting with the platform.
2. **Backend:** Node.js and Express.js handle requests, authentication, and application logic.
3. **Database:** MongoDB stores user accounts, course information, and other application data.
4. **Authentication:** JWT tokens are used to authenticate users and protect authorized routes.
5. **Payments:** Razorpay handles the payment workflow for course purchases.
6. **Email Service:** Sends relevant account and transaction notifications.

## 🚀 Getting Started

Follow these steps to run the project locally.

### Prerequisites

Install the following tools before starting:

- [Node.js](https://nodejs.org/)
- npm
- [MongoDB](https://www.mongodb.com/)
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/rishikumarsingh123/E-learning.git
cd E-learning
```

### 2. Install Dependencies

Check the project directory for the frontend and backend folders and install dependencies in each directory containing a `package.json` file.

```bash
npm install
```

If the frontend and backend have separate `package.json` files, run `npm install` separately in each directory.

### 3. Configure Environment Variables

Create a `.env` file in the appropriate backend directory and configure the environment variables required by the application.

Example:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
```

Add the required email-service configuration according to the email provider used in the project.

**Security:** Never commit real API keys, database credentials, email passwords, or other secrets to GitHub.

### 4. Run the Application

Start the backend using the development script defined in its `package.json`. Start the React frontend using its configured development script.

For example:

```bash
npm run dev
```

The exact commands and ports depend on the scripts configured in the project.

## 🔒 Security Considerations

- Protect private routes using authentication middleware.
- Validate payment responses on the server.
- Store passwords securely using an appropriate password-hashing mechanism.
- Keep API keys and secrets in environment variables.
- Validate user input before processing requests.

## 🎯 Learning Outcomes

This project demonstrates practical experience with:

- Full-stack web application development using the MERN stack.
- REST API design and frontend-backend integration.
- Authentication and authorization using JWT.
- MongoDB data management.
- Third-party payment gateway integration.
- Email notification workflows.

## 🔗 Repository

GitHub: [E-Learning Platform](https://github.com/rishikumarsingh123/E-learning)

## 👨‍💻 Author

**Rishi Kumar Singh**

GitHub: [@rishikumarsingh123](https://github.com/rishikumarsingh123)

---
