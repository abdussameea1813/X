# 🐦 X Clone: A Modern Social Networking Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/abdussameea1813/X/graphs/commit-activity)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/en/)
[![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)

**This repository contains a full-stack web application that aims to replicate the core functionalities of the popular social networking platform, X (formerly Twitter). Built with the MERN stack (MongoDB, Express.js, React, Node.js), this project showcases a modern approach to building interactive and real-time social media experiences.**

## ✨ Core Features

* **User Authentication:** Secure user registration and login using JWT for session management.
* **Post Creation & Management:** Users can create, read, and delete their own posts.
* **Like System:** Users can like posts, providing a way to engage with content.
* **Comment System:** Users can add and view comments on posts, fostering discussions.
* **Basic Feed Display:** A timeline displaying posts from all users.
* **Responsive Design:** The application is designed to be accessible and functional across various devices.
* **Clean and Intuitive UI:** A user interface built with React, aiming for a familiar and engaging experience.

## 🛠️ Tech Stack

* **Frontend:**
    * [React](https://react.dev/) - For building a dynamic and interactive user interface.
    * [React Router](https://reactrouter.com/en/main) - For client-side routing and navigation.
    * [Axios](https://axios-http.com/docs/intro) - For making HTTP requests to the backend API.
    * [CSS Modules](https://github.com/css-modules/css-modules) - For modular and maintainable styling.
* **Backend:**
    * [Node.js](https://nodejs.org/en/) - As the runtime environment for the server.
    * [Express.js](https://expressjs.com/) - For building the RESTful API.
    * [MongoDB](https://www.mongodb.com/) - As the NoSQL database to store user data and posts.
    * [Mongoose](https://mongoosejs.com/) - For MongoDB object modeling and interaction.
    * [jsonwebtoken](https://jwt.io/) - For creating and verifying JSON Web Tokens for authentication.
    * [bcrypt](https://www.npmjs.com/package/bcrypt) - For securely hashing user passwords.
    * [dotenv](https://www.npmjs.com/package/dotenv) - To manage environment variables.
    * [CORS](https://expressjs.com/en/resources/middleware/cors.html) - To handle Cross-Origin Resource Sharing.

## 🚀 Live Demo

Experience the application live:

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Now-brightgreen)](https://x-clone-xdca.onrender.com/login)

## 💻 Getting Started

Follow these steps to run the project locally:

### Prerequisites

* [Node.js](https://nodejs.org/en/) (version 18 or higher recommended)
* [npm](https://www.npmjs.com/) (usually comes with Node.js) or [yarn](https://yarnpkg.com/)
* [MongoDB](https://www.mongodb.com/try/download/community) - Ensure MongoDB is installed and running.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/abdussameea1813/X.git](https://github.com/abdussameea1813/X.git)
    cd X
    ```

2.  **Install backend dependencies:**
    ```bash
    cd backend
    npm install
    # or
    yarn install
    ```

3.  **Install frontend dependencies:**
    ```bash
    cd frontend
    npm install
    # or
    yarn install
    ```

4.  **Configure environment variables:**
    * Create a `.env` file in the `backend` directory.
    * Add the following environment variables (replace with your actual values):
        ```env
        PORT=5000
        MONGO_URI=your_mongodb_connection_string
        JWT_SECRET=your_secret_jwt_key
        ```

5.  **Run the backend server:**
    ```bash
    cd ../backend
    npm run dev
    # or
    yarn dev
    ```
    The backend server should start on port 5000 (or the port you specified).

6.  **Run the frontend development server:**
    ```bash
    cd ../frontend
    npm start
    # or
    yarn start
    ```
    The frontend application should be accessible in your browser (usually at `http://localhost:3000`).

## 🖼️ Screenshots

*(Consider adding a few screenshots here to visually showcase the application's UI. This significantly enhances the README's appeal.)*

### Login Page
*(Insert a screenshot of the login page)*

### Feed Page
*(Insert a screenshot of the main feed displaying posts)*

### Post Creation
*(Insert a screenshot showing the post creation interface)*

## 🚀 Future Enhancements

This project has the potential for further development. Here are some ideas for future enhancements:

* **Real-time Updates:** Implement WebSockets for real-time updates on new posts, likes, and comments.
* **Following System:** Allow users to follow other users and see their posts in a personalized feed.
* **User Profiles:** Create dedicated profile pages for users to showcase their information and posts.
* **Search Functionality:** Implement a search feature to find users and posts.
* **Image and Video Uploads:** Enable users to include media in their posts.
* **Notifications:** Implement a notification system for likes, comments, and follows.
* **Direct Messaging:** Allow users to send private messages to each other.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements

* [MERN Stack Documentation](https://www.mongodb.com/mern-stack) - For the foundation of this project.
* [React Documentation](https://react.dev/) - For the excellent UI library.
* [Node.js and Express.js Documentation](https://nodejs.org/en/) and [https://expressjs.com/](https://expressjs.com/) - For the powerful backend framework.
* [MongoDB and Mongoose Documentation](https://www.mongodb.com/) and [https://mongoosejs.com/](https://mongoosejs.com/) - For the robust database solution.
* The vibrant open-source community for their invaluable resources and support.

## 🧑‍💻 Author

[Abdussameea Patel](https://github.com/abdussameea1813)

---

Contributions are welcome! If you have ideas for improvements or find any issues, feel free to open a pull request or submit an issue. Let's build a great social networking experience together!
