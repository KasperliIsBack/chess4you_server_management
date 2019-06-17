# chess4you_server_management
Tools for the server management
## Source

#### ElasticSearch and Kibana
Resource Type  | URL
-------------- | -------------
Article        | https://alysivji.github.io/elasticsearch-kibana-with-docker-compose.html

#### Filebeat
Resource Type  | URL
-------------- | -------------
Article        | https://medium.com/@bcoste/powerful-logging-with-docker-filebeat-and-elasticsearch-8ad021aecd87
Git            | https://github.com/bcoste/sample-filebeat-docker-logging

#### Mongo DB
Resource Type  | URL
-------------- | -------------
Article        | https://hub.docker.com/_/mongo/

----
#### Command
Program       | Command       | Action
------------- | ------------- | -------------
ElasticSearch and Kibana  | sudo docker-compose up -d | must be run in the folder ./elasticsearch_kibana
Mongo Db  | sudo docker-compose up -d | must be run in the folder ./mongodb

----
#### Ports usage
Port       | Program | Forwared
------------- | ------------- | ------------- |
27017 | mongo db | []
9200 | elasticsearch | []
5601 | kibana | [x]
8080 | jenkins | [x]
8081 | gameserver | [x]
8082 | lobbyserver | [x]
8083 | mongo express | [x]
