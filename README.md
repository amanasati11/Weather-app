# Weather App
[![](https://img.shields.io/pypi/pyversions/Django.svg)](https://python.org/downloads/)
[![](https://img.shields.io/badge/django-2.0%20%7C%202.1%20%7C%202.2-success.svg)](https://djangoproject.com/)

This repository implements a weather app that uses Open Weather API and Django as a backend framework to get live weather status.

## Screenshots
![d](https://user-images.githubusercontent.com/69810375/94898101-970d8b80-04ae-11eb-8bb0-7f89aef27c3c.PNG)

## Features 

- Get Real-Time Weather Information of a City!

How To Use
=
## Clone project & Install Requirements
> Make sure you have already installed python3 and git.
```
$ git clone https://github.com/amanasati11/Weather-app.git && cd Weather-app
$ pip install -r requirements.txt
```
## Migrate & Collect Static
```
$ cd src && python manage.py migrate
$ python manage.py collectstatic
```
## Create Admin User
```
$ python manage.py createsuperuser
```
## Run Server
```
$ python manage.py runserver
```
> Enter your browser http://localhost:8000/. You can login via admin in http://localhost:8000/admin/.

## Project Structure
```
├───.idea
│   └───inspectionProfiles
├───the_weather
│   └───__pycache__
└───weather
    ├───migrations
    │   └───__pycache__
    ├───templates
    │   └───weather
    └───__pycache__
