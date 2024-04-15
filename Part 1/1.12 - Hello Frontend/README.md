## First
cloning the project was actually already done in 1.11 - Spring, so I will use that. But now I will go to /example-frontend
```shell
cd material-applications/example-frontend
```

## Next
Make the Dockerfile, then
```shell
docker build -t frontend .
docker run -p 5000:5000 frontend
```
Output:
```shell
 INFO  Accepting connections at http://localhost:5000
```



