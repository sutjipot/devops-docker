## backend:
``` shell
 docker build -t backend .
 docker run -p 8080:8080 backend
```
output:
```shell
[Ex 2.4+] REDIS_HOST env was not passed so redis connection is not initialized
[Ex 2.6+] POSTGRES_HOST env was not passed so postgres connection is not initialized
[GIN-debug] [WARNING] Creating an Engine instance with the Logger and Recovery middleware already attached.

[GIN-debug] [WARNING] Running in "debug" mode. Switch to "release" mode in production.
 - using env:   export GIN_MODE=release
 - using code:  gin.SetMode(gin.ReleaseMode)

[GIN-debug] GET    /ping                     --> server/router.pingpong (4 handlers)
[GIN-debug] GET    /messages                 --> server/controller.GetMessages (4 handlers)
[GIN-debug] POST   /messages                 --> server/controller.CreateMessage (4 handlers)
[GIN-debug] Listening and serving HTTP on :8080
[GIN] 2024/04/15 - 18:53:35 | 200 |  282.995495ms |      172.17.0.1 | GET      "/ping"
[GIN] 2024/04/15 - 18:53:51 | 200 |    7.546063ms |      172.17.0.1 | GET      "/ping"
```

## frontend:
```shell
docker build -t frontend .
 docker run -p 5000:5000 frontend
```

## localhost:5000
Exercise 1.14 shows "Success! Great job!"
