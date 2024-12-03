## Requisitos

* Python 3 ou superior - Conferir a versão: python --version
* Django 5 ou superior - Conferir a versão: django-admin --version
* MySQL 8 ou superior - Conferir a versão: mysql --version

## Como rodar o projeto baixado

Alterar no arquivo "settings.py" as credenciais do banco de dados.
´´´
'ENGINE': 'django.db.backends.mysql',
'NAME': 'nome-do-banco-de-dados',
'USER': 'usuario-do-banco-de-dados',
'PASSWORD': 'senha-do-usuario-do-banco-de-dados',
'HOST': 'localhost',
'PORT': '3306'
´´´

Executar as migrations para criar as tabelas.
´´´
python manage.py migrate
´´´

Rodar o projeto.
´´´
python manage.py runserver 
´´´

Acessar a página padrão criada com Django.
´´´
http://127.0.0.1:8000
´´´

Criar o super usuário.
´´´
python manage.py createsuperuser
´´´
´´´
Username (leave blank to use 'cesar'): admin
Email address: cesar@celke.com.br
Password: 123456A#
Password (again): 123456A#
´´´

Acessar o sistema administrativo padrão do Django.
´´´
http://127.0.0.1:8000/admin
´´´

Usuário: admin<br>
Senha: 123456A#

## Sequencia para criar o projeto
Instalar o Django.
´´´
pip install Django
´´´

Criar o projeto com Django.
´´´
django-admin startproject admin .
´´´

Rodar o projeto.
´´´
python manage.py runserver 
´´´

Acessar a página padrão criada com Django.
´´´
http://127.0.0.1:8000
´´´

Instalar o conector MySQL.
´´´
pip install mysqlclient
´´´

Criar a base de dados.
´´´
CREATE DATABASE celke CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
´´´

Alterar no arquivo "settings.py" as credenciais do banco de dados.
´´´
'ENGINE': 'django.db.backends.mysql',
'NAME': 'nome-do-banco-de-dados',
'USER': 'usuario-do-banco-de-dados',
'PASSWORD': 'senha-do-usuario-do-banco-de-dados',
'HOST': 'localhost',
'PORT': '3306'
´´´

Executar as migrations para criar as tabelas.
´´´
python manage.py migrate
´´´

Criar o super usuário.
´´´
python manage.py createsuperuser
´´´
´´´
Username (leave blank to use 'cesar'): admin
Email address: cesar@celke.com.br
Password: 123456A#
Password (again): 123456A#
´´´

Acessar o sistema administrativo padrão do Django.
´´´
http://127.0.0.1:8000/admin
´´´

## Como usar o GitHub
Inicializar um novo repositorio GIT.
´´´
git init
´´´

´´´
´´´

´´´
´´´

´´´
´´´

´´´
´´´

´´´
´´´