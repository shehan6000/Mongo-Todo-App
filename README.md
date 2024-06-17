# Mongo Todo App

A simple Todo application with a MongoDB backend, built using Express for the backend and React for the frontend.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [API Endpoints](#api-endpoints)
- [Technologies Used](#technologies-used)
- [License](#license)

## Features

- Add new todos
- Mark todos as completed
- Delete todos
- Fetch all todos

## Installation

### Prerequisites

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

### Steps

1. **Clone the repository:**

    ```sh
    git clone https://github.com/your-username/mongo-todo.git
    cd mongo-todo
    ```

2. **Install backend dependencies:**

    ```sh
    npm install
    ```

3. **Start MongoDB:**

    Ensure MongoDB is running on your system. By default, it runs on `mongodb://localhost:27017`.

4. **Start the backend server:**

    ```sh
    npm start
    ```

    The backend server will start on `http://localhost:3001`.

5. **Navigate to the `src` directory and install frontend dependencies:**

    ```sh
    cd src
    npm install
    ```

6. **Start the frontend server:**

    ```sh
    npm start
    ```

    The frontend server will start on `http://localhost:3000`.

## Usage

1. **Open the app in your browser:**

    Go to `http://localhost:3000`.

2. **Interact with the Todo List:**

    - Add new todos using the input field and the "Add Todo" button.
    - Toggle the completion status of a todo by clicking the checkbox.
    - Delete a todo by clicking the "Delete" button next to it.

## Project Structure

