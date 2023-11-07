# HOWTO:  interact with files using minio with docker and docker-compose

## Requirements
have docker and docker-compose installed on your computer or server

## Run the demo

### Step - run containers.
at the root of the directory, run :

``` bash
docker-compose up -d 
```

### Step - check everything is correct and give it a try
- by using the web interface (http://localhost:9000 if you runned the containers on your computer)
you should be able to add buckets and file and have it persisted

### remove the containers (but not the data)
at the root of the directory, run :
``` bash
docker-compose down
```

