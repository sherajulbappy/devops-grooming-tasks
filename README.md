Introduction
=================================
In here using 2 cotainer for load balancing through nginx in dokcer.


Installation and deployment steps:
====================================
Step 1
----------------
*install Docker.CE & Docker Compose

`````
sudo apt install docker-ce
sudo systemctl status docker

sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
docker-compose --version
`````

Step 2
---------

Goto /etc/docker then create a folder where you can save the configuration.

`````
mkdir task 4

``````

After that creating 
    * nginx.conf ---- for nginx configuration
    * docker-compose.yml ---- for manage multiple container & define port number and others configuration.
    * ssl certificate --- for encription

Then writedown the configuration on nginx.conf and docker-compose.yml
Then crate ssl certificaate under

Step 3
---------

Run the docker container using this command

````
sudo docker-compose up -d
````

Step 4
----------------
Check the configuration. Goto browser 

'https://localhost/'




