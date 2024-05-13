# Kafka-Connect-Timestamp-Converter

## Mysql kafka connector: 
    - debezium-connector-mysql
    - version: 2.4.1.Final
    - timestamp converter: oryanmoshe.kafka.connect.util.TimestampConverter

### Usage:
Basic configuration for timestamp converter:
```yaml
    converters: timestampConverter
    timestampConverter.type: oryanmoshe.kafka.connect.util.TimestampConverter
```

Advanced configuration for timestamp converter:
```yaml
    timestampConverter.format.datetime: "YYYY-MM-dd'T'HH:mm:ss.SSSSSS'Z'"
    timestampConverter.format.date: "YYYY-MM-dd"
    timestampConverter.format.time: "HH:mm:ss.SSSSSS"
    timestampConverter.debug: "true"
    timestampConverter.exclude.list: "field1,field2,field3"
```

## Postgres kafka connector: 
    - debezium-connector-postgres
    - version: 2.5.0.Final
    - timestamp converter: oryanmoshe.kafka.connect.util.TimestampConverter

### Usage:
Basic configuration for timestamp converter:
```yaml
    converters: timestampConverter
    timestampConverter.type: oryanmoshe.kafka.connect.util.TimestampConverter
```

Advanced configuration for timestamp converter:
```yaml
    timestampConverter.format.datetime: "YYYY-MM-dd'T'HH:mm:ss.SSSSSS'Z'"
    timestampConverter.format.date: "YYYY-MM-dd"
    timestampConverter.format.time: "HH:mm:ss.SSSSSS"
    timestampConverter.debug: "true"
```
