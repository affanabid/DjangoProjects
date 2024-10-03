# Django Projects Repository

Welcome to the Django Projects Repository! This repository contains a collection of Django-based web applications that showcase different features and functionalities built using the Django framework.

## Projects Overview

### 1. **Blog Application**
A simple web application where users can create, view, edit, and delete blog posts. Users can also comment on existing posts. This project demonstrates basic CRUD (Create, Read, Update, Delete) operations with Django models and forms.

- **Features**:
  - User authentication (sign up, login, logout)
  - Create, edit, and delete blogs
  - Comment on blogs
  - Pagination for blog lists

[View Blog Application Code](https://github.com/affanabid/django-projects/tree/main/BlogApplication)

### 2. **Little Lemon Restaurant Application**
A restaurant management application that allows users to view menus, make reservations, and leave feedback. This project highlights database relationships, form handling, and template rendering in Django.

- **Features**:
  - Display restaurant menu
  - User reservations system
  - Collect feedback and reviews

[View Little Lemon Restaurant Application Code](https://github.com/affanabid/django-projects/tree/main/LittleLemonRestaurantApplication)

### 3. **Study Chat Space**
A chatroom-based web application where users can join chat spaces relevant to their interests, interact with participants, and comment on posts. This project utilizes Django Channels for real-time communication and chat functionality.

- **Features**:
  - Real-time messaging with Django Channels
  - Join and create chat spaces
  - Comment on discussions

[View Study Chat Space Code](https://github.com/affanabid/django-projects/tree/main/StudyChatSpace)

### 4. **To-Do List Application**
A task management web application that allows users to create, edit, and delete daily tasks. This project emphasizes basic CRUD functionality, user authentication, and the use of Django forms.

- **Features**:
  - User authentication
  - Task creation, editing, and deletion
  - Task filtering (completed, incomplete)

[View To-Do List Application Code](https://github.com/affanabid/django-projects/tree/main/ToDoListApplication)

## How to Run the Projects

1. Clone the repository:
    ```bash
    git clone https://github.com/affanabid/django-projects.git
    ```

2. Navigate to the project directory:
    ```bash
    cd BlogApplication  # or any other project
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Django development server:
    ```bash
    python manage.py runserver
    ```

5. Open the browser and go to `http://127.0.0.1:8000/` to view the project.

## Tech Stack

- **Backend**: Django
- **Database**: SQLite (default), but can be configured to use other databases
- **Frontend**: HTML, CSS, JavaScript
- **Real-Time**: Django Channels (for Study Chat Space)

## Contributing

Contributions are welcome! If you have suggestions for improvements or encounter any issues, feel free to open an issue or create a pull request.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

