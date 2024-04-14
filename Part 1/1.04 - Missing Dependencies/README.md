
## Commands:
```shell
docker run -it ubuntu sh -c "while true; do echo 'Input website:'; read website; echo 'Searching..'; sleep 1; curl http://$website; done"
```

## Fixing:
```shell
docker exec -it practical_hopper bash
apt update && sudo apt upgrade
apt install curl
Y
```

## then:
```shell
Input website:
helsinki.fi
Searching..
<html>
<head><title>301 Moved Permanently</title></head>
<body>
<center><h1>301 Moved Permanently</h1></center>
<hr><center>nginx/1.22.1</center>
</body>
</html>
```
