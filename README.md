# django-blogs-website
This is a Django Framweork Python based project where we build a web application for blogging. The signed in users can create the posts, update or delete them on the fly. The users can also retrieve their password if forgotten through email. There is also a admin for managing the overall structure and viewing all the user information. SQLLite database is used and since this is ORM based framework, the developer don't have to worry about querring in the database.__

Instructions on how to run the website:__
1.Use the Anaconda prompt to run the project.__
To run the project, type 'python manage.py runserver'__
2. When you change the database schema, run 'python manage.py makemigrations' and then 'python manage.py migrate'__


Overall structure of the framework:__
templates folder: stores the HTML pages__
static folder : stored the CSS code__
models.py file : Model is a Python class mapped to a database table__
urls.py file : contains the routes to different web pages__
view.py file : function that takes web request and returns a web response__
signals.py file : Acts as a trigger function(for eg. to create Profile model automatically after a new user is registered)
