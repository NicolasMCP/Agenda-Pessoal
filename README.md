# Agenda-Pessoal
Agenda Pessoal em Python 3.13.1

## Historico

uv init Agenda-Pessoal

cd Agenda-Pessoal

uv venv --python 3.13

source .venv/bin/activate

uv add django

uv add pillow

django-admin startproject core .

rm -r hello.py

* rodando o servidor
uv run manage.py runserver

* criando um app django
uv run manage.py startapp diario

* migrations (criar /migrations/0001_initial.py)
uv run manage.py makemigrations

* cria as db
uv run manage.py migrate

* com as db Criadas, poso criar um Admin para usar o django.admin
uv run manage.py createsuperuser

