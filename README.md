# Purpose of this project

This project is built for the coding test of Forecast second round interview.

The aim of this project is to create a TODO SPA. The backend service uses Django in python as primary tool to structure.

The frontend service is connected by RESTful APIs with the backend. You can find out more instrcution about the frontend server [here](https://github.com/ads1029/Forecast-frontend):

## Available Scripts

In the project directory, you can run:

### `python manage.py migrate todo`

It is required as the initial step for running the project.

Migrating all the potential changes in the backend server.

### `python manage.py runserver`

Runs the server.\
Open [http://localhost:8000](http://localhost:8000) to view it in the browser.


# Solved Bugs

## - Backend would not receive frontend requests:
Due to the security setting, CORS whitelist is added to allow backend receives requests.


# TODO
ESlint and Prettier are added to enhance the efficiency, they are also excelent for seting up code standard in team-work.