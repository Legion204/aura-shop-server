## Backend Repository (Node.js + Express + MongoDB)

### Project Title

Aura Shop server

### Introduction

This is the backend repository of the project, built with Node.js and Express. It handles the application's server-side logic, including API endpoints and database interactions with MongoDB.

### Table of Contents

* [Installation](#installation)
* [Running Locally](#running-locally)
* [API Documentation](#api-documentation)
* [Configuration](#configuration)
* [Dependencies](#dependencies)
* [Contributors](#contributors)

### Installation

To set up the backend locally, follow these steps:

1. **Clone the repository**:

```bash
git clone https://github.com/Legion204/aura-shop-server.git
cd backend-repo
```

2. **Install dependencies**:

```bash
npm install
```

3. **Set up MongoDB**:

Ensure MongoDB is installed and running on your machine. Create a database for the project.

### Running Locally

To start the backend server:

1. **Set up environment variables**: Create a `.env` file in the root of the project with the following contents:

```plaintext
PORT=5000
MONGO_URI=mongodb://localhost:27017/yourdbname
```

2. **Start the server**:

```bash
npm run dev
```

The server will start on `http://localhost:3000`.

### Configuration

The backend requires the following environment variables:

* `PORT`: The port on which the server will run.
* `MONGO_URI`: The MongoDB connection string.

### Dependencies

This project uses several key dependencies, including:

* **Express**: A minimal and flexible Node.js web application framework.
* **Mongoose**: An Object Data Modeling (ODM) library for MongoDB and Node.js.
* **Dotenv**: For managing environment variables.

For a full list of dependencies, see the `package.json` file.

### Contributors

* **Riyad** - [GitHub Profile](https://github.com/legion204)