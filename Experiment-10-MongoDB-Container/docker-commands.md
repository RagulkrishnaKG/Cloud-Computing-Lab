# MongoDB Docker Commands

```bash
docker pull mongo
docker run --name mongodb-container -d -p 27017:27017 mongo
docker ps
docker exec -it mongodb-container mongosh
docker stop mongodb-container
docker rm mongodb-container
```
