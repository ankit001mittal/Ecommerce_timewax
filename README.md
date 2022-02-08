
# E-commerce
Basic ecommerce platform built on the Django Web Framework for Timewax assignment

## Installation

**1.clone Repository & Install Packages**
```sh
git clone 
```
**2.Setup Virtualenv**
```sh
virtualenv env
source env/bin/activate

pip install -r requirements.txt
```
**3.Migrate & Start Server**
```sh
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py createsuperuser
python3 manage.py runserver 8080
```