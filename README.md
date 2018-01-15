# sample_java8
sample project of Java

## Usage

### Create Image

```
$ docker build -t sample_java8 .
```

### Create Container

```
$ docker run -it -v <HOST DIR>:<GUEST DIR> sample_java8:latest /bin/bash
```

### Build Java Project

```
$ docker exec -it <CONTAINER ID> mvn test
```
