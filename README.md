Emergency Contacts API
======================

This is an API developed with Django to manage emergency contacts.

Prerequisites
-------------

*   Python 3.12.6
    
*   Virtualenv
    

Setting Up the Development Environment
--------------------------------------

1.  bashCopy codegit clone cd emergency\_contacts\_api
    
2.  bashCopy codepython -m venv venv
    
3.  **Activate the virtual environment:**
    
    *   bashCopy codevenv\\Scripts\\activate
        
    *   bashCopy codesource venv/bin/activate
        
4.  bashCopy codepip install -r requirements.txt
    
5.  By default, this project is configured to use SQLite, which requires no additional setup.
    
6.  bashCopy codepython manage.py makemigrationspython manage.py migrate
    
7.  bashCopy codepython manage.py createsuperuser
    
8.  bashCopy codepython manage.py runserverThe API will be available at http://localhost:8000.
    

Usage
-----

Once the server is running, you can access the following routes:

*   /admin/: Django's administrative interface.
    
*   /api/contacts/: Endpoints to manage emergency contacts.
    

API Documentation
-----------------

To view the API documentation, navigate to the /api/docs/ endpoint while the server is running.

Project Structure
-----------------

*   **manage.py**: Script to manage the Django project.
    
*   **emergency\_contacts\_api/**: Main project directory.
    
*   **contacts/**: Django application containing the emergency contacts logic.
    

Technologies Used
-----------------

*   Django
    
*   Django REST Framework
    
*   SQLite (default database)
