# Projeto Flask no Google Colab

Este projeto consiste em uma API desenvolvida utilizando o framework Flask, hospedada no ambiente de desenvolvimento colaborativo Google Colab. A API lê uma planilha de dados no formato JSON e a disponibiliza através de um endpoint acessível via navegador.

## Pré-requisitos

Antes de iniciar, é necessário ter o Python e o pip instalados no seu ambiente. Recomenda-se também ter o ambiente do Google Colab configurado.

## Instalação

1. Clone este repositório no seu ambiente do Google Colab:

```bash
git clone <URL_DO_REPOSITÓRIO>
````
2. Instale as dependências necessárias:
```bash
pip install flask pandas
````

## Uso

1. Execute o arquivo app.py para iniciar o servidor Flask:
````
python app.py
````
2. Acesse a API em seu navegador usando o URL fornecido pelo Colab, seguido por /index, por exemplo:
````
http://localhost:5000/index
````
Isso retornará os dados da planilha JSON no formato JSON.

## Estrutura do Projeto

├── app.py                # Arquivo principal da aplicação Flask
├── sua_planilha.json     # Planilha de dados no formato JSON
└── README.md             # Este arquivo README

