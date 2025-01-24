INSTALLATION MANUAL:

- Installing Python on Your Computer:
Ensure that Python is installed on your system. To verify, open a terminal and run the following command:

python --version

If Python is not installed, you can download it from python.org.

--------

- Creating a Virtual Environment (venv)
It is recommended to create a virtual environment. To do so, open the terminal in your project directory and run the following command:

python -m venv venv

If needed, activate the virtual environment:
On Windows:

.\venv\Scripts\activate
On macOS/Linux:

source venv/bin/activate

Once activated, you will see the name of the virtual environment appear at the beginning of your terminal line.

--------

- Navigating to the Correct Directory:
After creating the virtual environment, navigate to the correct directory. Use the following command:

cd ProyectoTiendaWeb

If necessary, locate the correct directory path and use:

cd …/ProyectoTienda/ProyectoTiendaWeb

--------

- Installing Dependencies:
Install the required dependencies using the requirements.txt file. This file contains all the necessary dependencies for the project to work:

pip install -r requirements.txt

This command will install all the libraries listed in the requirements.txt file.

--------

- Running and Applying Django Migrations:
To create migrations, run:

python manage.py makemigrations

To apply the migrations (this should suffice for the application to work):

python manage.py migrate

--------

- Running the Development Server:
Once everything is installed, you can run the development server:

python manage.py runserver

This will start the server, and you can access the application through a web browser at the indicated address (by default, http://127.0.0.1:8000/).
