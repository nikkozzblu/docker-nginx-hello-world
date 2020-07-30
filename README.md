# allure-test

A NGINX webserver that serves a simple page containing its hostname, IP address and port as wells as the request URI and the local time of the webserver.

How to run:

- You must have docker installed, if not
```
$ sudo apt install docker.io docker-compose
```

- Clone this repository:
```
$ git clone https://github.com/nikkozzblu/docker-nginx-hello-world
```
- Start the containers

```
$ docker run -p 8080:80 -d dockerbogo/docker-nginx-hello-world
```

Now, assuming we found out the IP address and the port that mapped to port 80 on the container, in a browser we can make a request to the webserver and get the page below: 

![hello_world](./hello_world.png)
