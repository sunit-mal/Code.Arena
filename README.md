# Code_Arena
• Code Arena, provides the environment to
execute program in particular language (i.e., C,
C++, PYTHON, JAVA). This web-based project
has a built-in online compiler that allows user to
compile user’s code and run it inan online terminal.
The project can also use to check that theprogram
working properly or not using test case, submitted
by the user.

• Tech Stack: Python, Django Backend, MVT Architecture,
SQLite Database(also mysql and mongodb can we use), HTML, CSS, JavaScript frontend

# Installation Process:

Download File then open Terminal 

# Activate your virtual environment (if you're using one)
`source <path_to_virtualenv>/bin/activate`

# Navigate to your project directory
`cd Code_Arena`

# Install project dependencies from requirements.txt
`pip install -r requirements.txt`

# Create database migrations
`python manage.py makemigrations`

# Apply database migrations
`python manage.py migrate`

# Create a superuser (for administrative access)
`python manage.py createsuperuser`

# Start the Django development server
`python manage.py runserver`

# If any problem related static file
`python manage.py collectstatic`
