1. Check Python version:
```
python3 --version
```
Make sure Python 3 is installed and running correctly.

2. Install pip (Python package manager):
```
sudo apt install python3-pip
```
This command installs pip for Python 3.

3. Install virtual environment package:
```
sudo apt install python3-venv
```
This command installs the Python virtual environment package.

4. Create a virtual environment:
```
python3 -m venv venv
```
This command creates a new virtual environment named 'venv'.

5. Activate the virtual environment:
```
source venv/bin/activate
```
This command activates the virtual environment. You should see '(venv)' in your terminal prompt.

6. Install Django:
```
pip3 install django
```
This command installs the Django framework inside the virtual environment.

7. Verify Django installation:
```
django-admin --version
```
This command checks the installed Django version.

8. Start a new Django project:
```
django-admin startproject new_project
```
This command creates a new Django project named 'new_project'.

9. Navigate to the project directory:
```
cd new_project/
```
This command changes the current directory to the project directory.

10. Run the Django development server:
```
python3 manage.py runserver
```
This command starts the Django development server, allowing you to access your project in a web browser.

Please note that these instructions assume you are using a Debian/Ubuntu-based Linux distribution. If you are using a different distribution, some package manager commands may differ slightly.

11. Create apps
```
python3 manage.py startapp appname
```