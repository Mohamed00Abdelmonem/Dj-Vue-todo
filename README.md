# Dj-Vue-todo

Dj-Vue-todo is a web application that integrates Django, Vue.js, and the Django REST framework to create a powerful todo list application. This project demonstrates the seamless interaction between the Django backend, Vue.js frontend, and the RESTful API.

## Getting Started

Follow these steps to set up and run the project locally:

### Prerequisites

Make sure you have the following installed on your system:

- Python 3.x
- Django
- Django REST framework
- Node.js
- npm

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Mohamed00Abdelmonem/Dj-Vue-todo.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Dj-Vue-todo
    ```

3. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Install the required JavaScript packages:

    ```bash
    cd frontend
    npm install
    ```

### Usage

1. Run the Django development server:

    ```bash
    python manage.py runserver
    ```

   This will start the server at `http://127.0.0.1:8000/`.

2. In a separate terminal, navigate to the `frontend` directory and run the Vue.js development server:

    ```bash
    npm run serve
    ```

   This will start the Vue.js development server at `http://localhost:8080/`.

3. Open your web browser and go to `http://localhost:8080/` to access the todo list application.

## Features

- **CRUD Operations**: Perform create, read, update, and delete operations on todo items using the Django REST framework.
- **Vue.js Components**: Utilizes Vue.js components for a modular frontend structure.
- **Django Backend**: Backend powered by Django for handling data and business logic.
- **RESTful API**: Uses Django REST framework for building a RESTful API to communicate between the frontend and backend.

## Contributing

Feel free to contribute to the project by creating issues, submitting pull requests, or providing feedback. Contributions are welcome and appreciated!
