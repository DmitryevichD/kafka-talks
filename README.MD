# Main goal of the project show general components of the kafka and they interaction
Current deployment is run by docker-compose and start a Kafka cluster.

Cluster contains:
- ZooKeeper three instances
- Kafka three instances
- ZooKeeper navigator (UI) one instance

# Project structure
- [.env](.env) - variables used into docker-compose 
- [docker-compose file](docker-compose.yaml)


## Run cluster
```bash
  $ docker-compose up
```
## Open ZooKeeper UI [http://localhost:9000](http://localhost:9000)
  + connection string: `localhost:22181`
  + auth username: `zookeeper`
  + auth password: '' (blank)