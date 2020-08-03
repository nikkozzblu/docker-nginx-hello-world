# allure-test

A NGINX webserver that serves a simple page containing its hostname, IP address and port as wells as the request URI and the local time of the webserver.

How to run:

- You must have docker and docker-compose installed. If not run in a terminal
```
$ sudo apt install docker.io docker-compose
```

- Clone this repository:
```
$ git clone https://github.com/nikkozzblu/docker-nginx-hello-world
```
- Start the container:
```
$ cd docker-nginx-hello-world
$ sudo docker-compose up -d
```

Now, assuming we found out the IP address and the port that mapped to port 83 on the container, in a browser we can make a request to (http://localhost:83) and get the page below: 

![hello_world](./hello_world.png)

- Make a screenshot of the browser screen, similar to the one above, and save it as a JPG file on the Desktop with your name as filename.

- Stop the container:
```
$ sudo docker-compose down
```

- Delete the repository folder from the machine
- Your are good to go :)

