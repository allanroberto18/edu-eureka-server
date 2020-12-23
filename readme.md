# Prepare the docker image

```
# Generate jar file
mvn clean install

# Generate docker image
docker build -t image_name:version .
```

### How to run the application from docker image

In terminal run the command below:

```
docker run -d -p 8761:8761 container_name allanroberto18/edu-eureka-server
```

In the browser run http://localhost:8761 
