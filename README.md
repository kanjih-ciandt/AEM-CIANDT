# CI&T AEM IN DOCKER

## Steps to Setup Developer environment

### Author 

To build image

```
cd aem-author
docker build -t aem-author .
```

To Run
```
cd aem-author
docker run -p 4502:4502 aem-author
```

### Publisher

To build image

```
cd aem-publisher
docker build -t aem-publisher .
```

To Run
```
cd aem-publisher
docker run -p 4503:4503 aem-publisher
```

### Dispacher

To build image

```
cd aem-dispacher
docker build -t aem-dispacher .
```

To Run
```
cd aem-author
docker run -p 80:80 aem-dispacher
```

## Setup docker compose

```
docker-compose up
```



-----------


Thanks: Prabhu Vignesh Kumar Rajagopal (https://digitalvarys.com/create-aem-in-docker-with-docker-compose/)