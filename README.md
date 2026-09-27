# TaskManager

Sistema para gerenciamento e organizacao de tarefas.

## Conclusão de tarefas

## Definição de prioridade das tarefas

## Versão 1.0.0

## Versão 1.1.0 - Containerização com Docker

## Como executar

### Pré-requisitos

- Docker instalado
- Docker Compose instalado (já incluso no Docker Desktop)

### 1. Clonar o repositório

git clone https://github.com/Caio-Silva455/taskmanager.git
cd taskmanager


### 2. Construir e subir o container

docker compose up -d --build


### 3. Acessar a aplicação

Abra o navegador em: http://localhost:8080

### 4. Ver os logs do container

docker compose logs -f


### 5. Parar o container

docker compose down


### 6. Reconstruir após alterações

docker compose up -d --build


## Estrutura do projeto

taskmanager/
├── public/
│ └── index.html
├── Dockerfile
├── docker-compose.yml
├── .dockerignore
└── README.md
