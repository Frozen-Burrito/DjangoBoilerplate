# Django Project Boilerplate

> Still in development

 A standard boilerplate for django projects that includes the [Django Debug Toolbar](https://django-debug-toolbar.readthedocs.io/en/latest/), special settings, commands & configuration. I wrote all the code following a tutorial. 

## How to start

1. In the **Django_Boilerplate** directory, activate the virtual environment by running ```env\Scripts\activate``` on windows
2. If needed, run ```python manage.py makemigrations``` and ```python manage.py migrate``` if migrations need to be applied.
3. Finally, in the **Django_Boilerplate** directory run ```python manage.py runserver```. This will provide the localhost address, which can be introducer in the browser's searchbox to open the boilerplate.

## Special commands

* ```python manage.py rename project_name new_project_name``` can be used to rename the project. By default, **project_name** is "demo". Replace **new_project_name** with the new name.