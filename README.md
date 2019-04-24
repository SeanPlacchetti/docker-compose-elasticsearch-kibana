# kibana-dev-env

## Overview
Docker Compose for a two node Elasticsearch cluster (7.0.0) and Kibana (7.0.0) for development purposes.

## Requirements
1. Docker (Make sure your docker config is set to handle a high enough amount of resources or the containers will fail to load.)
2. Docker-compose

### Start Stack in Daemon Mode
```
docker-compose up -d
```

### Check status of docker-compose cluster (if not using kinematic)
```
docker-compose ps -a
```

### Cluster Node Info
```
curl http://localhost:9200/_nodes?pretty=true
```

### Access Kibana
```
http://localhost:5601
```

### Access Elasticsearch
```
http://localhost:9200
```

### Originally Forked from
```
https://github.com/maxyermayank/docker-compose-elasticsearch-kibana
```
