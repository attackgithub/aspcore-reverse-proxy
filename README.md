# Asp.NET Core 2 + Load Balancer

Allow load balancer with reverse proxy.

### Build

```
docker build -t aspcore2 .
docker run -d -p 80:80 -e REDIS_CONNECTION=redis --name app aspcore2 
```
