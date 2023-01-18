# devcontainer-template



## Start rabbitmq-server

```
docker compose build
docker compose up -d
```

## Scale service

```docker compose up --scale rpc-consumer=3 -d```

## Test

```python3 producer.py```
