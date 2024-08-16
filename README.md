# Django CRM App

Welcome to the Django CRM (Customer Relationship Management) App! This project is a web-based CRM system built using Django, Python, and MySQL. The app provides basic CRM functionalities such as user registration, authentication, and CRUD operations on customer records. This project is inspired by and takes references from [FreeCodeCamp](https://www.freecodecamp.org/).

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Features

- **User Authentication**: Register, Log In, and Log Out.
- **Customer Management**: Add, View, Update, and Delete customer records.
- **Database**: Uses MySQL for data storage.
- **Responsive Design**: Built with Bootstrap for a responsive and user-friendly interface.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Python 3.x** installed on your machine.
- **MySQL** installed and configured.
- **pip** (Python package installer).
- **Virtualenv** (optional but recommended).

## Installation

Follow these steps to get the CRM app running on your local machine:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/django-crm.git
    cd django-crm
    ```

2. **Create a virtual environment** (optional but recommended):
    ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up the MySQL database**:
    - Create a new database in MySQL:
      ```sql
      CREATE DATABASE crm_db;
      ```
    - Update the `DATABASES` configuration in `settings.py` with your MySQL credentials.

5. **Run migrations**:
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

6. **Create a superuser** (to access the Django admin):
    ```bash
    python manage.py createsuperuser
    ```

7. **Run the development server**:
    ```bash
    python manage.py runserver
    ```

8. **Access the application**:
    - Open your web browser and navigate to `http://127.0.0.1:8000/`.

## Usage

- **Register** a new user or **log in** with existing credentials.
- Once logged in, you can **add new customer records**.
- **View** details of any customer by clicking on the record.
- **Edit** or **delete** any customer record.
- **Log out** when you are done.


## Technologies Used

- **Django**: Python web framework
- **Python**: Programming language
- **MySQL**: Relational database management system
- **Bootstrap**: CSS framework for responsive design

## Acknowledgements

This project is inspired by the tutorial on [FreeCodeCamp](https://www.freecodecamp.org/). A big thank you to the FreeCodeCamp community for providing invaluable resources and support.

