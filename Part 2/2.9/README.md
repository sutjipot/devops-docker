## Changes:
1. nginx.conf
The previous nginx configuration sends all API requests to backend, but the new one have different paths
 for different parts of the backend.

2. Frontend Dockerfile
specifically this line
```ENV REACT_APP_BACKEND_URL=http://localhost/api```

4. Backend Dockerfile
specifically this line
```ENV REQUEST_ORIGIN=http://localhost```

## Results:
As expected, when we go to ```localhost```, all buttons are good.
```shell 
Exercise 1.14 Success! Great job!
```
```shell 
Exercise 2.4 Nice! The exercise is complete!
```
```shell 
Exercise 2.6 Working! Messages below also work.
```
```shell 
Exercise 2.8 Nice! The exercise is complete!
```
