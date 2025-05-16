# ДЗ Тема: Основи технології  Docker

Ensure your .env file exists in the project root with:

```env
POSTGRES_USER=postgres
POSTGRES_PASSWORD=567234
POSTGRES_DB=hw02
```

Run the application:
```bash 
docker-compose up --build
```

Remove all stopped containers and volumes:
```bash
docker-compose down -v
docker system prune -af
```
