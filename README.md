# Flask App With DB

Exemplo simplificado de uma aplicação web usando o Flask que menipula dados de um banco de dados (Postgres).
É possível ver a criação completa dessa aplicação na postagem [Criando uma Aplicação CRUD com Flask, PostgreSQL e Docker](https://programero.blogspot.com/2025/01/criando-uma-aplicacao-crud-com-flask.html)

## Configuração do Ambiente

### Requisitos
- Docker
- Docker Compose

### Passos para Rodar a Aplicação

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/app_flask_with_db.git
   cd xxx
   ```
2. Inicie os contêiners usando o Docker Compose:
   ```bash
   docker-compose up --build
   ```

3. A aplicação estará disponível em `http://localhost:5000`.

