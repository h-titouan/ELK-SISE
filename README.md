# ELK-SISE
ElasticSearch workshop for the SISE master

## Purpose of the repository

This repository present how to set ELK Stack using docker. 

## How to use this repository

### Mandatory
If you want to try it, you have to :

* Get Docker Desktop and run it
* Get the files from the "docker" folder and save them in the folder you will use.

### Setup 

```
$ cd 'path/to/repository/folder'
$ docker-compose up -d
```

### Run application with localhost

If the mandatory points was check, you can acces Elasticsearch and Kibana using these links : 

* [Elasticsearch] :localhost:9200
* [Kibana] : localhost:5601

### .env error :

If the file .env isn't save in the right folder you will have this error : 

```
$ WARN[0000] The "ES_PORT" variable is not set. Defaulting to a blank string. 
$ WARN[0000] The "STACK_VERSION" variable is not set. Defaulting to a blank string. 
$ WARN[0000] The "STACK_VERSION" variable is not set. Defaulting to a blank string. 
$ WARN[0000] The "KIBANA_PORT" variable is not set. Defaulting to a blank string. 
$ Error response from daemon: no such image: docker.elastic.co/elasticsearch/elasticsearch:: invalid reference format
```

You just have to save it in the right folder and it will run.
