- django-admin startproject todo_webapp_project

Things to do:
- https://www.youtube.com/watch?v=ovql0Ui3n_I
11:40

then use https://djangoforbeginners.com/pages-app/
to make a seccond page


peresonal_webapp_proj - idk
1peresonal_webapp_proj - idk
2peresonal_webapp_proj - 2 pages that work... used tutorial (need to delete)
3peresonal_webapp_proj - coppied the last one so i could push to github
4peresonal_webapp_proj - this one.. usisng the todo list youtuve tutoria;

commands to set up venv and django (first navigate to the folder you want to work in)
- py -m venv env
- .\env\Scripts\activate
- python -m pip install Django
- py -m django --version

command to run server
- python manage.py runserver

sites
- https://stackoverflow.com/questions/7594348/i-want-a-button-on-my-website-that-will-execute-a-python-script

- https://djangoforbeginners.com/pages-app/
(but I subbed out "pages" for "options")

__condensing what I learned__
To add a new webpage you need...
- create a .html file under 'templates'
- fill that in with sime html
- in options/views.py add a new class with a new tamplate_name
- under options/urls.py, add the new view you want to import (after 'from .views import...'). also add a new path()
- yay! you have a new page!! to access it, run 'python manage.py runserver' and go to http://127.0.0.1:8000/NewPageName

