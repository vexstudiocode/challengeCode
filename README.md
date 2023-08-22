# steps:

## first: create node dir:volumes
```
mkdir node0 node1 node2
```

## second: startup of the nodes to startup the services.
uncomment lines:
```
docker-compose up
```

## third: validate Service startup:
```
curl http://localhost:26657/status
```