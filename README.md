This is to setup Elasticsearch and Kibana cluster stack on Ubuntu server.  
Utilizing Docker Compose to build Elasicsearch container, Kibana container, and
Nginx container.

Setup Intruction:
  
1.  Install Docker and Dock-compose:
        Follow this link to install Docker:  https://docs.docker.com/engine/install/ubuntu/

2.  Download the ES directory to server and copy it to the /apps directory.
3.  Change to es directory:
       cd /apps/es
4.  Check to make sure Docker is running:
       systemctl status docker.service
5.  Start the Docker Compose:
       docker compose up
       Note: Check to make sure everything is running okay.
6.  Stop the Docker compose by pressing " Control C" together at the same time.
    You shall get prom command now.
7.  We want Docker Compose to run in the detach mode or in the backgroup now.  Run this command:
        docker compose start
8.  Log on to the page now:  https://hostname:443
       Note: Please replace the hostname with the name of your server.



    
