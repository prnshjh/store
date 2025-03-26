# Store MERN Application

A full-stack e-commerce application built using the MERN stack (MongoDB, Express, React, Node.js). This project allows users to manage products, including creating, updating, and viewing product details.

## Features

- **Frontend**: Built with React and Chakra UI for a responsive and modern user interface.
- **Backend**: Built with Node.js and Express for handling API requests.
- **Database**: MongoDB for storing product data.
- **Routing**: React Router for navigation.
- **State Management**: React hooks for managing state.
- **Styling**: Chakra UI for consistent and customizable design.

---
# Folder Structure
store-MERN/
├── backend/
│   ├── config/          # Database connection configuration
│   ├── models/          # Mongoose models
│   ├── routes/          # API routes
│   ├── server.js        # Main server file
│   └── .env             # Environment variables
├── frontend/
│   ├── src/
│   │   ├── components/  # React components
│   │   ├── pages/       # React pages
│   │   ├── App.jsx      # Main React app
│   │   └── main.jsx     # React entry point
│   └── public/          # Static assets
├── README.md            # Project documentation
└── [package.json](http://_vscodecontentref_/0)         # Project metadata

## Installation

### Prerequisites
- Node.js (v16 or later)
- MongoDB (local or cloud instance)

### Clone the Repository
```bash


git clone https://github.com/your-username/store-MERN.git
cd store

Folder Structure
store-MERN/
├── backend/
│   ├── config/          # Database connection configuration
│   ├── models/          # Mongoose models
│   ├── routes/          # API routes
│   ├── server.js        # Main server file
│   └── .env             # Environment variables
├── frontend/
│   ├── src/
│   │   ├── components/  # React components
│   │   ├── pages/       # React pages
│   │   ├── App.jsx      # Main React app
│   │   └── main.jsx     # React entry point
│   └── public/          # Static assets
├── README.md            # Project documentation
└── [package.json](http://_vscodecontentref_/0)

cd store
npm install
npm run dev


cd frontend
npm install
npm run dev

Create a .env file in the backend directory and add the following:

MONGO_URI=your-mongodb-connection-string
PORT=5000


