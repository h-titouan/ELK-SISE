# ELK-SISE
ElasticSearch workshop for the SISE master

## Purpose of the repository

This repository present how to set ELK Stack using docker. 

## How to use this repository

### Required
If you want to run it, you have to :

* Get Docker Desktop and run it
* Get the files from the "docker" folder and save them in the folder you will use.

### Setup 

```
$ cd 'path/to/your/repository/folder'
$ docker-compose up -d
```

As soon as you run this command, the docker-compose runs until you stop it from Docker Desktop or from the following command: 

```
$ docker-compose down
```

### Run application with localhost

If the required points was check, you can acces Elasticsearch and Kibana using these links : 

* Elasticsearch : localhost:9200
* Kibana : localhost:5601

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

## References : 

This docker-compose have been made from this source : [Elasticsearch and Kibana installation using Docker Compose](https://blog.devgenius.io/elasticsearch-and-kibana-installation-using-docker-compose-886c4823495e)
