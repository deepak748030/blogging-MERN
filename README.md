# Blogging Website (MERN Stack)

Welcome to the **MERN Blogging Website** repository! This project is a full-stack blogging platform built with the **MERN** stack (MongoDB, Express, React, Node.js). It allows users to create, edit, delete, and view blog posts.

## Features

- **User Authentication**: Users can register and log in using JWT-based authentication.
- **CRUD Operations**: Users can create, read, update, and delete blog posts.
- **Responsive Design**: Fully responsive layout optimized for mobile, tablet, and desktop screens.
- **Commenting System**: Users can add comments to blog posts.
- **Private Routing**: Certain routes are protected and only accessible to logged-in users.

## Technologies Used

- **MongoDB**: NoSQL database for storing blog posts and user information.
- **Express.js**: Web application framework for Node.js to build the backend API.
- **React.js**: Frontend framework for building the user interface.
- **Node.js**: JavaScript runtime for the server-side application.
- **JWT (JSON Web Token)**: For handling secure user authentication.
- **Bcrypt.js**: For password hashing and security.

## Installation

Follow these steps to set up and run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/deepak748030/blogging-MERN.git
```

### 2. Navigate to the Project Directory

```bash
cd blogging-MERN
```

### 3. Install Backend Dependencies

Go to the backend folder and install dependencies:

```bash
cd backend
npm install
```

### 4. Set Up Environment Variables

Create a `.env` file in the backend folder and add the following environment variables:

```env
MONGO_URI=your_mongo_db_connection_url
JWT_SECRET=your_jwt_secret_key
```

### 5. Install Frontend Dependencies

Go to the frontend folder and install dependencies:

```bash
cd ../frontend
npm install
```

### 6. Run the Development Servers

#### Run the backend server:

```bash
cd ../backend
npm run dev
```

#### Run the frontend server:

```bash
cd ../frontend
npm start
```

The frontend will now be accessible at `http://localhost:3000`, and the backend at `http://localhost:5000`.

## Usage

- **Register & Log In**: Users can register or log in to the platform.
- **Create Blog Posts**: Logged-in users can create and edit blog posts.
- **View Blog Posts**: Users can view all blog posts and their associated comments.
- **Commenting**: Users can add comments to any blog post.

## Demo

Since the website is not hosted yet, please follow the above instructions to run it locally.

## Contributing

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push the branch to your forked repository (`git push origin feature-name`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Key Details:
- **Demo Section**: Since the website isn't hosted, it includes instructions on how to run it locally.
- **Installation Instructions**: Clear steps on setting up the backend and frontend, as well as setting up environment variables.
- **Technologies**: Listed the main technologies you're using.
- **Contributing**: A standard guide for contributing to the project.
