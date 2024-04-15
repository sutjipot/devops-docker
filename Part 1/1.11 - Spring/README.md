## First:
clone repo then go to material-applications/spring-example-project
```shell
git clone https://github.com/docker-hy/material-applications.git
cd material-applications/spring-example-project
```
then make Dockerfile through VSCode

## Next
after Dockerfile is made, build the image, then run
```shell
docker build -t spring .
docker run -p 8080:8080 spring
```

