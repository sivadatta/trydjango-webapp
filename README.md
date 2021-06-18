# trydjango-webapp
Creating web application using django

To start, you should have python installed on your machine.

Type the below command to see the python version , if already installed.

``` python -V or python3 -V ```

Follow the below steps if python is not installed on Mac OS

# Installation Setup

*  Download python from [Downloads](https://www.python.org/downloads/)

*  Install python by extracting the dmg file

## Installing pip

pip is the reference Python package manager. It’s used to install and update packages.

``` python3 -m pip install --user --upgrade pip ```

You should have the newest version installed.

``` python3 -m pip --version ```

## Installing virtualenv

virtualenv is used to manage Python packages for different projects. Using virtualenv allows you to avoid installing Python packages globally which could break system tools or other projects. You can install virtualenv using pip

``` python3 -m pip install --user virtualenv ```

Check ``` pip freeze ```  to see only required packages  seperate

## Creating virtual environment

To create virtual environment, go to your project directory and run the below command 

``` python3 -m venv env ```

In my case, ..../trydjango-webapp


## Activating virtual environment

Before you can start installing or using packages in your virtual environment you’ll need to activate it. Activating a virtual environment will put the virtual environment-specific python and pip executables into your shell’s PATH.

Run the below command in current project directory

``` source env/bin/activate ```


## Install Django

``` pip install django ```


To create a blank Django project. Lets create inside the src folder

``` mkdir src ```
```  cd src ```
``` django-admin startproject  trydjangoweb . ```


To run the server

``` python manage.py runserver ```

And you are good to go to start Django project with python

Reference - [Python](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)












