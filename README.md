# Desafio Docker – Gestão Acadêmica Simplificada

Este projeto foi desenvolvido como parte da atividade de **Ambiente de Software (ADS - IFCE)**.  
O objetivo é criar um ambiente padronizado com **Docker** e **Docker Compose**, que execute uma aplicação web Flask e um banco de dados MySQL, simulando um sistema interno de gestão acadêmica.

---

## Tecnologias utilizadas

- **Python 3.11 (Flask)**
- **MySQL 8**
- **Docker & Docker Compose**

---

## Estrutura do projeto

gestao-academica/
├── app/
│ ├── app.py
│ ├── requirements.txt
│ └── Dockerfile
├── docker-compose.yml
└── README.md


## Como executar o projeto

1 Clonar o repositório 
```bash
git clone https://github.com/SEU-USUARIO/ambiente-software-desafio-docker.git
cd ambiente-software-desafio-docker 

2 Subir os containers
docker compose up --build

3 Acessar a aplicação
http://localhost:5000

Deve aparecer a mensagem:

Gestão Acadêmica Simplificada – Ambiente inicial configurado com Docker Compose ✅