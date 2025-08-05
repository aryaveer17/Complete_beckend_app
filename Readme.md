# 🎥 VideoHub – YouTube-like Backend System
made by - Aryan.

VideoHub is a robust backend system built to simulate the core functionalities of a YouTube-like platform. It supports video uploads, streaming, user authentication, content interactions (like, dislike, comments), and playlist management — all backed with secure and scalable architecture.

---

## 🚀 Features

- 🔐 **Authentication & Authorization**  
  - User registration & login using **JWT**
  - Secure routes with middleware-based protection
  - **Role-based access control** for admin & users

- 🎞️ **Video Handling**
  - Upload videos via **Multer**
  - Store & serve media efficiently via **Cloudinary**
  - Stream videos securely

- 💬 **User Interactions**
  - Like/Dislike system
  - Comments on videos
  - Playlist creation & management

- 📡 **RESTful API Architecture**
  - Well-structured API endpoints built with **Express.js**
  - Follows **MVC design pattern**

- 🧠 **Scalable Structure**
  - Modular, maintainable codebase
  - Middleware-driven request handling
  - Easy integration with frontend or mobile apps

---

## 🛠 Tech Stack

| Tech         | Usage                                |
|--------------|--------------------------------------|
| Node.js      | JavaScript runtime                   |
| Express.js   | Backend framework                    |
| MongoDB      | NoSQL Database                       |
| Mongoose     | ODM for MongoDB                      |
| Multer       | File upload handling                 |
| Cloudinary   | Cloud storage for videos/images      |
| JWT          | Authentication mechanism             |
| Dotenv       | Environment variable management      |
| Bcrypt       | Password hashing                     |
| CORS         | Cross-origin resource sharing        |

---

## 🧩 Folder Structure
videohub/
├── config/ # Database and cloudinary configs
├── controllers/ # Route logic and business operations
├── middlewares/ # Auth, error handling, role checks
├── models/ # Mongoose schemas
├── routes/ # API route declarations
├── utils/ # Helper functions
├── uploads/ # Temp uploads (optional)
├── .env.example # Sample env variables
├── server.js # Main server entry point
└── README.md # Project documentation


---

## 🔧 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone (https://github.com/aryaveer17/Complete_beckend_app)
   cd videohub-backend
Install dependencies
npm install

Create a .env file

PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
