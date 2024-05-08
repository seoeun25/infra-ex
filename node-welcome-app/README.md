# node-welcome-app

## Docker build

```
$ cd node-welcome-app
$ docker build . -t node-welcome-app

## run a container
$ docker run -d -p 3000:3000 node-welcome-app

## docker 내부 확인 
$ docker exec -ti 46630657d1e0 /bin/bash 
root@46630657d1e0:/app# pwd
/app

```
웹서버 확인
```
curl -X GET "http://localhost:3000"
```

