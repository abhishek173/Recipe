# Recipe Management Web Application

This is a full-stack web application built with Django that allows users to register, authenticate, and manage their sessions. The application provides CRUD (Create, Read, Update, Delete) functionality for recipes and includes a search feature for quick access to recipes based on keywords.

## Features

- **User Registration and Authentication:**
  - Users can register for an account.
  - Secure authentication system using Django’s built-in authentication framework.
  - Session management with login and logout capabilities.

- **Recipe Management:**
  - Users can create new recipes.
  - View detailed information about each recipe.
  - Update existing recipes.
  - Delete recipes that are no longer needed.

- **Recipe Search:**
  - Integrated search functionality allowing users to find recipes by keywords.

## Prerequisites

- Docker
- Python 3.x
- Django

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/abhishek173/Recipe.git
    cd your-repository
    ```

2. **Build and start the Docker containers:**

    ```bash
    docker-compose up --build
    ```

3. **List all running Docker containers:**

    ```bash
    docker ps
    ```

4. **Access the running container's bash shell:**

    ```bash
    docker exec -it <container_id> bash
    ```

    Replace `<container_id>` with the ID or name of the running container. You can find the container ID using the `docker ps` command.

5. **Create a Django superuser:**

    Inside the Docker container, run the following command:

    ```bash
    python manage.py createsuperuser
    ```

    Follow the prompts to create the superuser.

## Usage

Once everything is set up, you can access the Django admin panel by navigating to `http://localhost:8000/admin` in your web browser. Log in with the superuser credentials you created.


 


