# [Django Application Repository](https://github.com/obaidhoque/django_analytics_app)
With Django, you can take Web applications from concept to launch in a matter of hours and I found it very intuitive and straight-forward. You can click on the linked header for checking the repo. Additionally, you can also click this video [link](django_app_flexmonster.mov) to download and see the deployment process on my desktop server. 

![Analytics App](django_app_flexmonster.gif) 

# Creating a Django virtual environment
1. Create a dedicated directory for virtual environment in terminal or powershell\
    `mkdir project_name `
2. Go to the created folder\
    `cd project_name`
3. Activate the virtual environment (make sure to install python package bundler `pipenv`)\
    `pipenv shell`
4. Make sure to install Django only after activating the virtual environment\
    `pipenv install django==3.0.3`
5. Create Django Project After Django is installed\
    `pipenv run django-admin startproject project_name .`
6. To run the Django development server, execute the following command:\
    `python manage.py runserver`
7. Next, open the following URL in your browser:\
    `http://127.0.0.1:8000/project_name/`

# Flex monster Web Reporting
Flexmonster is an amazing JS framework for deploying web reporting tools such as pivot tables, pie charts etc. I am only beginning to learn JS and have found it to be quite flexible and interesting

# Future projects using Django
1. Use plotly's graphing library (`graph_objects`) to create an analytics dashboard
2. Incorporate a machine learning application onto the Django framework
3. Create a data collection application using python libraries such as `selenium`, `request` etc


