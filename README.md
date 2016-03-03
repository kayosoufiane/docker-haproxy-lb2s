#Présentation :
Rapide équilibreur de charge (Load Balancer), pré-paramétré pour 2 serveurs.

## Demo Load Balancer :
```
docker run -it -p 5050:80 --link web.a:my-app1 -e APP1=my-app1 --link web.b:my-app2 -e APP2=my-app2 -e PORT=5004 --name lb.a ykandrirody/docker-haproxy-lb2s
```

