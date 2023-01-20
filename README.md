If errors like 

```
export DOCKER_BUILDKIT=0
export COMPOSE_DOCKER_CLI_BUILD=0

$env:DOCKER_BUILDKIT = 0
$env:$COMPOSE_DOCKER_CLI_BUILD = 0
```

https://www.envoyproxy.io/docs/envoy/latest/configuration/overview/examples

https://stackoverflow.com/questions/64221861/an-error-failed-to-solve-with-frontend-dockerfile-v0


sudo ./envoy -c envoy.yaml --log-level trace
