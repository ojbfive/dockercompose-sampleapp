# dockercompose-sampleapp
A demo on how to use docker-compose to create a Web Service connected to a load balancer and a Redis Database.




# Getting Started - Installation

We would use an exampled on the lines of the one used by Docker to illustrate basic Compose functionality. This is a simple Python App that sets up a simple webpage displaying the number of hits to that page and and uses Redis backend to store the number of hits that page.

Step 1 : Go ahead and install Docker and Docker Compose on your machine. 

Install Docker :            [Docker](https://docs.docker.com/installation/) and 
Install Docker Compose :    [Docker Compose](https://docs.docker.com/compose/install/)

After installing Docker and Docker Compose we would now get stated by cloning this project onto our dcoker host machine. 


# Cloning Git Repository

In order to get started be sure to clone this project onto your Docker Host. Create a directory on your host. Please note that the demo webservices will inherit the name from the directory you create. If you create a folder named test. Then the services will all be named test-web, test-redis, test-lb. Also, when you scale your services it will then tack on a number to the end of the service you scale.

git clone https://github.com/Jay-Wani/dockercompose-sampleapp.git

