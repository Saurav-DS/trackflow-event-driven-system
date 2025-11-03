# Kafka & Docker Setup Verification

Follow these steps to confirm your Kafka stack is running correctly.

---

## 1. Verify Docker Installation
```bash
docker --version
docker compose version
docker info
```

## 2. Start Kafka Stack
```bash
cd docker
docker compose up -d
```
This starts:
- Zookeeper → localhost:2181
- Kafka Broker → localhost:9092
- Kafka UI Dashboard → http://localhost:8085

This stops:
- docker compose down
- or
- docker stop <CONTAINER ID>