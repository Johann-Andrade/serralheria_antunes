# Abrir o site
- clique no botão verde escrito "<> code"
- clique em "baixar ZIP"
- descompacte ele na área de trabalho (de preferência)
- e abra o arquivo "index"
- ligue o server de alguma das duas formas abaixo

# Ligar o server pela primeira vez
- instale o python no computador https://www.python.org/downloads/
- abra o console de comando e digite os comandos abaixo (não digite o que estiver entre aspas e eles devem estar do jeito que estão, então desative a tradução automatica do google)
- cd desktop "entra na área de trabalho"
- cd serralheria_antunes-main "entra na pasta do site"
- cd backend "entra na pasta de beackend"
- Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope Process "permite que comandos do python sejam executados"
- python -m venv venv "cria uma nova pasta que serve de server"
- venv\Scripts\activate "ativa o server"
- pip install django "instalação para o server"
- pip install django djangorestframework "instalação para o server"
- pip install django-cors-headers "instalação para o server"
- cd serralheria_api "entra na pasta de configuração do server"
- python manage.py migrate "cria o banco de dados"
- python manage.py runserver "faz ele rodar"

# Ligar o server depois da primeira vez
- abra o console de comando e digite os comandos abaixo (não digite o que estiver entre aspas)
- cd desktop "entra na area de trabalho"
- cd serralheria_antunes-main "entra na pasta do site"
- cd backend "entra na pasta de beackend"
- Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope Process "permite que comandos do python sejam executados"
- venv\Scripts\activate "ativa o server"
- cd serralheria_api "entra na pasta de configuração do server"
- python manage.py runserver "faz ele rodar"
