# Product Microservice

## Dev

1. Repository Clone
2. Install Dependency
3. Create `.env` 
4. Prisma Migration  `npx prisma migrate dev`
5. 
```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```
6. `npm run start:dev`