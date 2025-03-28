# Django_blog_App_with_Crud functionality

A project built with Python, Django web framework and Bootstrap 5

###  Project Goals

* Users can register or login  to the website to create blogs. user must be a registered user to be able to create, update or delete a blog or comment.

* Users can Create, Read, Update and Delete the blog comments they've created form the website.

* Once logged in, Users can access a REST API on the website, which also allows them to use CRUD (Create, Read, Update and Delete) operations.(currently Work in progress!!)

### Project Functionalities:

* Only logged in users can add blog content on the website or the API (when implemented).

* The list todo blogs/comments page of the website and the API will only show the content that the logged in user created. Meaning, Only the author of the blog/comments can perform CRUD operations.

* If one user tried to test URLs to reach another user's blog or comment a 403 Forbidden page is displayed.

* Once logged in Users can access a REST API which has a filtering framework built with django-filter package, which allows the user to filter the blog or comment by their state (completed or not completed).


### Project Preview


### Libraries and Packages used

* [Django Web Framework](https://www.djangoproject.com/)

* [Django Rest Framework](https://www.django-rest-framework.org/) package

* [django-filter](https://github.com/carltongibson/django-filter/tree/main)

* UI components from the official Bootstrap 4.6 website documentation.
-------------------------------------------------------------------------------

### To get started with this project

* Clone the repository: git clonehttps://github.com/NLugner2025/cstar_blog.git



* Open the terminal or CMD to create a virtual environment like Python virtual environment (venv) or pipenv and activate it.

    * ``` python -m venv venv ```           *Create the venv*

    * ``` source venv/bin/activate ```      *On Linux*

    * ``` venv/Scripts/activate ```         *On Windows*

    * ``` source venv/Scripts/activate ```  *Git Bash on Windows*

* Install requirements.txt: ``` python -m pip install -r requirements.txt ```

* Change directory to backend ``` cd backend ```

* Create the database by running the following commands:
``` python manage.py makemigrations todos ```
``` python manage.py migrate ```

* Create a super user: ``` python manage.py createsuperuser ```

* Run the project: ``` python manage.py runserver ```

