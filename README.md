# To Do List Using Python-Django

## Overview

This project is a simple To Do List application built using Python and Django. It allows users to create, view, and manage their tasks. The application provides a form to add new tasks and displays a list of tasks with options to mark them as complete or delete them.

## Features

- Create new tasks with a title and description.
- View a list of tasks with their details.
- Mark tasks as complete.
- Delete tasks.

*Data Model*

- ID (Auto-incremented)
- Title
- Description
- Action
  
## Prerequisites

Before you begin, ensure you have met the following requirements:

Setup:
- Django installed (you can install it using `Install Django and Django REST Framework:`)
- A basic understanding of Django and how to run Django projects
  
```bash
pip install django djangorestframework
```
Create a new Django project and app:

```bash
django-admin startproject mytodo
cd mytodo
django-admin startapp mytodo
```

**Apply Migrations**

Apply the initial migrations to set up the database schema:

```bash
python manage.py makemigrations
python manage.py migrate
```
Run the Development Server

Start the Django development server:

```bash
python manage.py runserver
```

## Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Piyushraj7982/To-Do-Application-Django.git
   cd To-Do-Application-Django
   ```

Now you can access the API at `http://127.0.0.1:8000/todo/` to see the To Do List application in action.
Access the Application

## Usage

- **Add a Task**: Use the form on the main page to enter a title and description for a new task and click "Submit".
- **Complete a Task**: Click the "Complete" button next to a task to mark it as completed.
- **Delete a Task**: Click the "Delete" button next to a task to remove it from the list.

## Project Structure

- **HTML Template**: Contains the layout and structure of the To Do List page, including the form for adding tasks and the table displaying existing tasks.
- **Django Views and URLs**: Manages the logic for creating, completing, and deleting tasks.
- **Django Models**: Defines the database schema for storing tasks.

## Contributing

If you’d like to contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a Pull Request.

## Acknowledgements

- Bootstrap for styling.
- Django for the web framework.

