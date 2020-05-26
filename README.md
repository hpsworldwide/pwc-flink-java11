# PWC-FLINK-JAVA11

Flink docker image for Java 11

## Docker Compose Support

- To start Apache Flink cluster:

```console
$ docker-compose -f flink.yml up -d
```

- To access Apache Flink cluster UI browse to [http://localhost:8081/](http://localhost:8081/)

- To scale (up/down) **TaskManagers**:

```console
$ docker-compose -f flink.yml scale taskmanager=[scale-number]
```

- To stop Apache Flink cluster:

```console
$ docker-compose -f flink.yml down
```