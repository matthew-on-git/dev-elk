# dev-elk
dev elasticsearch instance for tem tasks
from: https://medium.com/@TimvanBaarsen/how-to-run-an-elasticsearch-7-x-single-node-cluster-for-local-development-using-docker-compose-2b7ab73d8b82

Bring up detached local elk stack: \
kibana: http://localhost:5601 \
elasticsearch: http://localhost:9200

``` bash
docker-compose up -d
```

To shut down Elasticsearch and Kibana run:
``` bash
docker-compose down
```

To wipe out the docker volume while shutting down run:
``` bash
docker-compose down -v
```