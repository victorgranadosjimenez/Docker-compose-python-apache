##create multi container for each service in a web site through docker compose

#we create a folder to keep all files

#we create a folder with a python file "api.py"




## we install docker-compose, give permission and chech is working

sudo curl -L "https://github.com/docker/compose/releases/download/1.25.3/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

sudo chmod +x /usr/local/bin/docker-compose

docker-compose --version



##we type "docker-compose up" to spin up the containers

in localhost:5000 we s#hould be able to see the website server


##CONTROl+C to stop docker-compose
