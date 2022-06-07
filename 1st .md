# Django-beginner
Welcome to the Django-beginner wiki!

## Install Python on your machine.
1. go to https://www.python.org/downloads/. 
1. Download the executable installer and run it. 
1. Check the boxes next to “Install launcher for all users (recommended)” 
1. then click “Install Now”.

After installation, open the command prompt and check that the Python version matches the version you installed by executing:

**`py --version`**

If Python is installed, you will get a result with the version number, like this

> Python 3.9.2

## Setting up a virtual environment

To install Virtual environment, use the following command on the command prompt. 

**`pip install virtualenv`**

### Create a virtual Python Environment for your Project

change directory to the place where you want your Django project to be. Use the cd command on your command prompt to move to the said directory as follows:

> **`cd first_project`**

Create a virtual Python Environment (you can change `project-name` as you like )

**`py -m venv project-name`**

activate the environment

**`project-name\Scripts\activate`**

## Create the django project

### 1.Setup Django

Remember to install Django while you are in the virtual environment!

**`py -m pip install Django`**

### 2. Creating a project

You can change the project name `studybud` if you like.

**`django-admin startproject studybud`**

### 3. Run django server

Change into the outer “studybud” directory

**`cd studybud`**

Run the following commands:

**`python manage.py runserver`**

Now that the server’s running, 
visit http://127.0.0.1:8000/ with your web browser. You’ll see a “Congratulations!” page, with a rocket taking off. It worked!

image:: ![image](https://user-images.githubusercontent.com/33391568/172283416-885a5cda-bbe3-4489-aad0-c1d607adc5ec.png)
 [Django runserver]

Now that your environment – a “project” – is set up, you’re set to start doing work.







