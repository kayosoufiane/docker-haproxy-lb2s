# HAProxy load balancer between 2 servers Docker image

## Usage
```
docker run -it -p 5050:80 --link web.a:my-app1 -e APP1=my-app1 --link web.b:my-app2 -e APP2=my-app2 -e PORT=5004 --name lb.a ykandrirody/docker-haproxy-lb2s
```

