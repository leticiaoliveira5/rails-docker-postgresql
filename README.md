# Descrição

Template de aplicação Rails.

## Principais ferramentas
- Ruby (v4.0.9)
- Rails (v8.0.5)
- PostgreSQL
- GitHub Actions

## Subir o projeto

Para testar, a melhor opção é usar o Docker. Pra isso, é necessário ter instalado na máquina o docker e docker compose.

Agora execute os comandos no terminal:

```
cd rails-docker-postgresql
```

```
docker-compose build
docker-compose up
```

Abra um outro terminal execute:

```
docker compose exec rake db:setup
```

Acesse a aplicação em http://localhost:3000/

