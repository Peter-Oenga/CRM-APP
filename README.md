# Django Customer Relationship Management (CRM) App with Python and MySQL

Welcome to our Django Customer Relationship Management (CRM) App! This application is designed to help you manage your customer relationships efficiently using Django, Python, and MySQL. With this app, you can perform various tasks such as registration, login, adding, viewing, updating, and deleting customer records.

## Features
- **Registration:** Users can create new accounts to access the system.
- **Login and Logout:** Registered users can log in and out securely.
- **Add Records:** Users can add new customer records to the database.
- **View Records:** Users can view existing customer records.
- **Update Records:** Users can update information in existing customer records.
- **Delete Records:** Users can delete customer records.

## Installation
To run this Django CRM application, follow these steps:

1. **Clone the Repository:**
    ```bash
    git clone
    ```
2. **Install Dependencies:**
    Navigate to the project directory and install the necessary Python packages using pip:
    ```bash
    pip install -r requirements.txt
    ```
3. **Database Configuration:**
    - Make sure you have MySQL installed on your system.
    - Create a MySQL database for the application.
4. **Database Settings:**
    - Open the `settings.py` file in the project's directory.
    - Configure the database settings to connect to your MySQL database.
5. **Run Migrations:**
    Apply migrations to create database tables:
    ```bash
    python manage.py migrate
    ```
6. **Run the Application:**
    Start the Django development server:
    ```bash
    python manage.py runserver
    ```
7. **Access the Application:**
    Open your web browser and go to [http://localhost:8000/](http://localhost:8000/) to access the application.
