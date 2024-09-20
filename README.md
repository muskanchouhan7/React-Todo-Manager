# Todo List Web Application

This is a simple Todo List web application built using React and Vite. It allows users to add, view, and manage tasks. The app is structured using modern front-end technologies and is designed to be fast and user-friendly.

## Features
- Add new tasks
- Mark tasks as completed
- Update tasks
- Delete tasks
- Simple and intuitive UI

## Technologies Used
- **Frontend**: React, CSS
- **Backend**: Node.js 
- **Bundler**: Vite

## Getting Started

### Prerequisites
- **Node.js** installed on your local machine.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/todo-list-app.git
    ```

2. Navigate to the project directory:
    ```bash
    cd todo-list-app
    ```

3. Install the dependencies:
    ```bash
    npm install
    ```

4. To run the project locally:
    ```bash
    npm run dev
    ```

5. Open your browser and navigate to `http://localhost:3000`.

## Project Structure
```bash
📦todo-list-app
 ┣ 📂Server                # Backend code
 ┃ ┣ 📂Models              # Database models 
 ┃ ┣ 📜index.js            # Server entry point
 ┣ 📂todo-list             # Frontend code
 ┣ 📂public                # Static files (SVGs, images, etc.)
 ┣ 📂src                   # Source code
 ┃ ┣ 📂assets              # Assets like images, fonts, etc.
 ┃ ┣ 📜App.jsx             # Main application component
 ┃ ┣ 📜Create.jsx          # Task creation page/component
 ┃ ┣ 📜Home.jsx            # Home page/component
 ┃ ┣ 📜main.jsx            # Entry point for React
 ┃ ┣ 📜index.css           # Global CSS
 ┣ 📜.gitignore            # Ignored files for Git
 ┣ 📜index.html            # Root HTML file
 ┣ 📜vite.config.js        # Vite configuration
 ┗ 📜README.md             # Project documentation
