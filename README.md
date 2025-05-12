# TáSeguro

{insira algo aqui}

## Tecnologias

- **Frontend:** React + Vite  
- **Backend:** Django REST Framework  
- **Banco de Dados:** PostgreSQL  
- **Orquestração:** Docker Compose

---

## Como rodar o projeto

### 1. Pré-requisitos

- [Docker](https://www.docker.com/)  
- [Docker Compose](https://docs.docker.com/compose/)

---

### 2. Clonando o repositório

```bash
git clone https://github.com/(...)
cd taseguro
```

### 3. Estrutura esperada
```bash
taseguro/
├── frontend/         
│   ├── Dockerfile
│   └── ...
├── api/              
│   ├── core/         
│   ├── taseguro/     
│   ├── Dockerfile
│   ├── manage.py
│   ├── requirements.txt
│   └── .env
└── docker-compose.yml
```

### 4. Subindo os containers
```bash
docker-compose up --build
```
Aguarde até ver que tanto o backend (api) quanto o frontend (frontend) estão rodando. Você pode fazer isso tanto quanto pela interface do VSCode, quanto pelo Docker Desktop ou simplesmente dando o seguinte comando no terminal:
```bash
docker ps
```

## Endpoints e Acessos
| Serviço      | URL                                                          |
| ------------ | ------------------------------------------------------------ |
| Frontend     | [http://localhost:3000](http://localhost:3000)               |
| Backend API  | [http://localhost:8000/api](http://localhost:8000/api)       |
| Admin Django | [http://localhost:8000/admin/](http://localhost:8000/admin/) |
### ⚠️ Use as credenciais do .env para acessar o banco! ⚠️

## Licença
MIT License

Copyright (c) 2025 - Equipe TáSeguro