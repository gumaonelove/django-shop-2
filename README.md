# e-commerce

Прототип интернет магазина

## Используемые технологии:
- python django
- js jquery

## Installation

```sh
sudo apt-get install python3-venv
python3 -m venv venv
source venv/bin/activate
git clone https://github.com/gumaonelove/django-shop-2.git
```

## Development
```sh
cd django-shop-2
mkdir media
python manage.py makemigrations
python manage.py migrate
python manage.py collectstatic
python manage.py runserver
```
