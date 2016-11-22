kafka-boshrelease
=================

BOSH release for kafka broker

This deployment starts one node with zookeeper and two nodes with brokers. If you need more brokers just change the
instances properties on the yml file.

```
  bosh upload release releases/kafka/kafka-1.yml
  bosh deployment manifests/kafka.yml
  bosh deploy
```

Current Versions:
kafka - 0.8.1.1 (2.9.2)
zookeeper - 3.4.6
openjdk - 1.7.0
