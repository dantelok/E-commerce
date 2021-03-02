# E-commerce
Simple Ecommerce website with Paypal / Dabit / Credit Card payment


## Setup
Ensure you have python 3.6+ installed.

`pip install -r requirements.txt`

## Build up the database
`cd ecommerce`
`python manage.py createmigrations`
`python manage.py migrate`

## Create Superuser
`python manage.py createsuperuser`
Take a username and password

## Run the server
`python manage.py runserver`

## Handle data in database
go to https://localhost:8000/admin/
login and check the tabs
You can create and handle the items, order, new user information
