# Ligar o server pela primeira vez
- abra o console de comando
- cd desktop "entra na area de trabalho"
- cd serralheria "entra na pasta do site"
- cd backend "entra na pasta de beackend"
- python -m venv venv "cria uma nova pasta que serve de server"
- venv\Scripts\activate "ativa o server"
- pip install django "instalação para o server"
- pip install django djangorestframework "instalação para o server"
- pip install django-cors-headers "instalação para o server"
- cd serralheria_api "entra na pasta de configuração do server"
- python manage.py runserver "faz ele rodar"

# Ligando o server depois da primeira vez
- abra o console de comando
- cd desktop "entra na area de trabalho"
- cd serralheria "entra na pasta do site"
- cd backend "entra na pasta de beackend"
- venv\Scripts\activate "ativa o server"
- cd serralheria_api "entra na pasta de configuração do server"
- python manage.py runserver "faz ele rodar"
