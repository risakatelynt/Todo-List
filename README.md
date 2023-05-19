README

# Todo List App

This repository contains a Todo List application built using React and Django.

## Features

- Create, update, and delete tasks.

## Technologies Used

- React: JavaScript library for building user interfaces.
- Django: Python web framework for building backend applications.
- SQLite: Relational database management system.
- CSS for web design.

## Installation

1. Clone the repository:

```
git clone <repository-url>
```

2. Install the required dependencies:

```
npm install   # Install React dependencies
```

3. Setup and activate a virtual environment:

```
python3 -m venv env
source env/bin/activate   # For Unix/Linux
env\Scripts\activate   # For Windows
```

4. Install the Python dependencies:

```
pip install -r requirements.txt
```

5. Set up the database:

```
python manage.py migrate
```

6. Start the development server:

```
python manage.py runserver
```

7. Access the application in your browser:

```
http://localhost:3000
```

## Configuration

To configure the application, modify the following files:
- `backend/todo/settings.py`: Configure the database settings.
