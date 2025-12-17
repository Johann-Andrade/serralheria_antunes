# Abrir o site
- clique no botão verde escrito "<> code"
- clique em "baixar ZIP"
- descompacte ele na área de trabalho (de preferência)
- e abra o arquivo "index"
- ligue o server de alguma das duas formas abaixo

# Ligar o server pela primeira vez
- instale o python no computador https://www.python.org/downloads/
- abra o console de comando
- cd desktop "entra na area de trabalho"
- cd serralheria_antunes-main "entra na pasta do site"
- cd backend "entra na pasta de beackend"
- Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope Process
- python -m venv venv "cria uma nova pasta que serve de server"
- venv\Scripts\activate "ativa o server"
- pip install django "instalação para o server"
- pip install django djangorestframework "instalação para o server"
- pip install django-cors-headers "instalação para o server"
- cd serralheria_api "entra na pasta de configuração do server"
- python manage.py runserver "faz ele rodar"

# Ligar o server depois da primeira vez
- abra o console de comando
- cd desktop "entra na area de trabalho"
- cd serralheria "entra na pasta do site"
- cd backend "entra na pasta de beackend"
- venv\Scripts\activate "ativa o server"
- cd serralheria_api "entra na pasta de configuração do server"
- python manage.py runserver "faz ele rodar"
