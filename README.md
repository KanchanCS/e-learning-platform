# Setting up the e-learning project
First, create a virtual environment for your new project within the env/ directory:
```diff
+ python -m venv env/educa
```
Install Django virtual environment:
```diff
+ pip install Django~=4.1.0
```
manage image uploads in your project, so you also need to install Pillow: 
```diff
+ pip install Pillow==9.2.0
```
Create a new project using:
```diff
+ django-admin startproject educa
```
Enter the new educa directory and create a new application
```diff
- cd educa
+ django-admin startapp courses
```
Edit the settings.py file of the educa project and add courses to the INSTALLED_APPS setting
