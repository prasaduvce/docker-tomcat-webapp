# docker-tomcat-webapp


Clone this repo


#### Build docker image: 
````
docker build -t mywebapp .
````
#### Check whether docker image is created: 
````
docker image ls

REPOSITORY                    TAG              IMAGE ID       CREATED          SIZE
mywebapp                      latest           4852d2037c4b   24 seconds ago   147MB
````
#### Docker run the image:
````
docker run -p 80:8080 mywebapp
````

#### Verify the browser URL
```
http://localhost/docker-tomcat-webapp/
```
