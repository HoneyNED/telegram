# Pushshift Telegram Ingest API

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSXG_xMmYM2H-3aA23-yLirD5s20cVBC-VtbnCQQt-jEbDld7lp)

## Description

The Pushshift Telegram Ingest API ingests data from numerous Telegram channels / groups and stores that data in Postgres and Elasticsearch and provides an easy to use API that can be used to search for data across numerous channels.

The goal of this project is to consume data from publicly available channels and groups and give researchers the ability to quickly search and filter data.


## config.yaml

Example config:
```yaml
api_id: 000000
api_hash: 000000000000000000000000000000
db_password: xxxxxxx
es_host: http://localhost:9200
es_index: telegram
sql_debug: false
```
