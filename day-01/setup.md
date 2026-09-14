## Setup

There are two ways to set up Kafka.

1. Kafka + Zookeeper (Traditional)
2. Kafka with Kraft (Modern)

---

### Kafka + Zookeeper (Traditional)

- Run below command to use Kafka + zookeeper with docker container.

```bash
sudo docker compose -f ./day-01/docker-kafka-zookeeper.yaml up -d
```

- Run below command to stop docker container.

```bash
sudo docker compose -f ./day-01/docker-kafka-zookeeper.yaml down
```

---

### Kafka with Kraft (Modern)

- Run below command to use Kafka + no zookeeper with docker.

```bash
sudo docker compose -f ./day-01/docker-kafka-kraft.yaml up -d
```

- Run below command to stop docker container.

```bash
sudo docker compose -f ./day-01/docker-kafka-kraft.yaml down
```