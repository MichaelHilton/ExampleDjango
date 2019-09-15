
# ExampleDjango
This repo has the code for the inclass exercise introducing Django apps and the ORM.
To run the code, you should follow these steps from the command line: 
* clone repo 
* change directory into ExampleDjango Directory
* Initiate the Virtual Enviroment (on mac this is done with: 

    python3 -m venv .
  
    source ./bin/activate
* pip install Django
* change directories into todoapp/
* run server with the following command: 

   ./manage.py runserver 8100
   
   
 # Creating a new Django Project.
This repo is ready to run. For reference, the following steps were the ones we followed in class to configure this repo to its current state.

* python3 -m venv .
* source ./bin/activate
* pip install Django
* django-admin startproject todoapp
* cd todoapp/
* django-admin startproject todoapp
* make changes to files (these are the actual code changes). 
* ./manage.py makemigrations
* ./manage.py migrate
* ./manage.py createsuperuser
* ./manage.py runserver 8100


# Extra Resources:
The Django website has some great documentation on these topics. For further reading we recommend:
* https://docs.djangoproject.com/en/2.2/intro/tutorial01/
* https://docs.djangoproject.com/en/2.2/topics/db/



