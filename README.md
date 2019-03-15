# kibana-dev-env

## Overview
Docker Compose for Elasticsearch (6.5.4) and Kibana (Open Source 6.5.4) for development purposes.

## Requirements
1. Docker
2. Docker-compose

### Start Stack in Daemon Mode
```
docker-compose up -d
```

### Check status of docker-compose cluster
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
