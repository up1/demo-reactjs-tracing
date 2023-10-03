# Distributed tracing with Frontend
* ReactJS
* NodeJS -> express
* Tracing server with [Jaeger](https://www.jaegertracing.io/)

## How to run
```
$docker-compose up  -d --build
$docker-compose ps
$docker-compose logs --follow
```

## Testing
* URL = http://localhost:3000

Check the result in Jaeger UI (http://localhost:16686/)

