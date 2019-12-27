# Shop
![Python Versions](https://img.shields.io/pypi/pyversions/django.svg?style=flat)
<br>
![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)<br>


## Contribution guidelines
Kindly follow [contributing.md](contributing.md), if you want to lend a hand in making this project better.

## Build Setup

```bash
#creating virtual env
mkdir project
cd project
virtualenv env
source env/bin/activate

#clone the directory
git clone https://github.com/kulkarni-rajas/django_basic

#change directory
cd django_basic

#Install dependencies
pip install -r requirements.txt

#Do migrations
python manage.py makemigrations
python manage.py migrate

#Run server
python manage.py runserver
```
