
Django Virtual Environment Setup
The virtual environment is an environment which is used by Django to execute an application. It is recommended to create and execute a Django application in a separate environment. Python provides a tool virtualenv to create an isolated Python environment. We will use this tool to create a virtual environment for our Django application.

To set up a virtual environment, use the following steps.

1. Install Package

First, install python3-venv package by using the following command.

$ apt-get install python3-venv  
djanjo virtual environment setup install package
2. Create a Directory

$ mkdir djangoenv  
After it, change directory to the newly created directory by using the cd djangoenv.

djanjo virtual environment setup Create a directory
3. Create Virtual Environment

$ python3 -m venv djangoenv  
4. Activate Virtual Environment

After creating a virtual environment, activate it by using the following command.

$ source djangoenv/bin/activate  
djanjo virtual environment setup activate virtual environment
Till here, the virtual environment has started. Now, we can use it to create Django application.

Install Django
Install Django in the virtual environment. To install Django, use the following command.

$ pip install django  
djanjo virtual environment setup install django
Django has installed successfully. Now we can create a new project and build new applications in the separate environment.

