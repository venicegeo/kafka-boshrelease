# kafka-boshrelease

BOSH release for kafka broker

This deployment starts one node with zookeeper and two nodes with brokers.

## Deploy

```
  bosh upload release releases/kafka/kafka-4.yml
  bosh deployment manifests/kafka.yml
  bosh deploy
```

## Current Versions

* kafka - 0.9.0.1 (2.10)
* zookeeper - 3.4.9
* openjdk - 1.8-u111
