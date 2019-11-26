# Demo_site
This is sample demo_site for CICD automation testing with git,jenkins,docker

## Creating Virtual Environment

I have folder on my desktop called demo-site, 
I will create my virtual environment in this folder, On my terminal, 
I will navigate to demo-site folder and run the following command: 
```
py -m venv onlineshop
```
The above command created a python virtual environment with the name onlineshop. To use our virtual environment, we actually need to activate it. To activate our virtual environment run the following command: source onlineshop/bin/activate At the beginning of the line on your terminal, you will see the name of your virtual environment and that is how you know that your environment is active. To deactivate your virtual environment simply type deactivate and hit enter.

NB: Every time you work on your virtual environment, always remember to activate it.

Now that our virtual environment is activated, let’s install Django web framework by running the following command: 
```
pip install Django 
```
The above command install latest Django web framework. In our case is Django 2.0.1

To start our e-commerce project run the following command: 
```
django-admin startproject ecommerce 
```
this command creates a our django project called ecommerce. On your terminal, 
navigate to our project folder by typing the following command:  or clone this complete code (Clone this complete project
https://github.com/s-naidu/Demo_site.git)

cd ecommerce To run our development server run the following command: 
```
python manage.py runserver 
```
Now that our server is up and running, 
on your browser navigate to: http://127.0.0.1:8000/ 

## Followng things complete
creating a shopping cart project.

## created a virtual environment.
installed Django web framework in our virtual environment.
created our project and run the development server.

you can start using this demosite for practicing



