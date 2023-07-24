# Dev Basic Setup

- Install Docker and docker-compose;
- Setup environment variables in a .env file (see .env.example);
- Run setup:

```bash
docker-compose up -d
```

- Now you have:
  - PostgreSQL (localhost:5432)
  - MongoDB (localhost:27017 with admin web interface at http://localhost:8081)
  - Redis (localhost:6379)
  - DynamoDB local (localhost:8000)
  - MinIO (localhost:9000)
- Happy coding!
