## LINK
https://hub.docker.com/repository/docker/sutjipot/reactproj
my attempt on dockerizing a front end application


## USAGE
1. Pull the image ```docker pull sutjipot/reactproj```
2. Run the container ```docker run -p  5173:5173 reactproj``` or ```docker run -p  5173:5173 -v "$(pwd):/app" -v /app/node_modules reactproj```
3. See the react app in ```http://localhost:5173/```
