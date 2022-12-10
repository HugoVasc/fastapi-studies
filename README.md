# Repositório para estudos do Python Fast API

## Instalando os requisitos

* Recomenda-se o uso de ambiente virtual (virtualenv) para a instalação e execução das diferentes seções

``pip install requirements.txt``

## Executando a aplicação

1. Execução simples: ``python main.py``
2. Execução multithread: ``gunicorn main:app -w 4 -k uvicorn.workes.UvicornWorker``
