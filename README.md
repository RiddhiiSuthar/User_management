# Django User Login/Register with Email Activation Feature

## Description

This Django application provides a user authentication system with email activation functionality. Users can register for an account, activate it via email, login, and logout. The activation link is sent to the user's provided email address upon registration.

## Installation

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/RiddhiiSuthar/User_Management.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd User_Management
    ```

3. **Install the required dependencies:**
    
    ```bash
    pip install -r requirements.txt
    ```
   
4. **Apply migrations:**
    
    ```bash
    ./manage.py migrate
    ```

5. **Start the development server:**

    ```bash
    ./manage.py runserver
    ```



## Features

Once the server is running, you can access the application via your browser at `http://localhost:8000`.

### Register

- Navigate to `http://localhost:8000/user-manage/register/`.
- Fill out the registration form with your details.
- An activation link will be sent to the provided email address.
- Click on the activation link in the email to activate your account.

### Login

- Navigate to `http://localhost:8000/user-manage/login/`.
- Enter your username and password.
- Click on the "Login" button.

### Logout

- If you're logged in, you can logout by navigating to `http://localhost:8000/user-manage/logout/`.

### Home

- Access the home page by visiting `http://localhost:8000`.
- From the home page, you can easily navigate to login, register, or logout functionalities.

## Configuration

- Email configuration settings can be modified in the `settings.py` file to match your email server credentials.
- You may want to set the `EMAIL_BACKEND` to your preferred email backend (e.g., SMTP backend).
- Make sure to configure your email server to allow sending emails from Django.
