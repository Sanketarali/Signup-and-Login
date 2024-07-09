# Signup-and-Login
This is a simple Django project that demonstrates user authentication with signup, login, and logout functionalities. The project uses Django's built-in authentication system.

# Features
User Signup<br>
User Login<br>
User Logout<br>
Protected Home Page (accessible only after login)<br>

# Technologies Used
Django<br>
HTML/CSS<br>
Bootstrap<br>
Font Awesome<br>

# Project Setup
<h3>Prerequisites</h3>
Make sure you have the following installed:

Python (3.6 or higher)<br>
Django (3.0 or higher)<br>

# Installation
Clone the repository:<br>
git clone<br>

<h3>Navigate to the project directory:</h3>
cd django-authentication-project<br>

# Apply migrations:
python manage.py migrate<br>

# Create a superuser:
python manage.py createsuperuser<br>

# Run the development server:
python manage.py runserver<br>

# URL Patterns
/ - Signup Page<br>
/login/ - Login Page<br>
/home/ - Home Page (requires login)<br>
/logout/ - Logout<br>

# Views
SignupPage - Handles user signup<br>
LoginPage - Handles user login<br>
HomePage - Protected home page (requires login)<br>
LogoutPage - Handles user logout<br>

# Usage
Open the browser and navigate to http://127.0.0.1:8000/.<br>
Signup with a new account.<br>
Login with the created account.<br>
Access the home page.<br>
Logout using the logout button.<br>

# Screenshots
<h3>Signup Page</h3>

![Screenshot 2024-07-09 230653](https://github.com/Sanketarali/Signup-and-Login/assets/110754364/e3f25c10-a71e-46ff-a056-acc89e5fbcce)
