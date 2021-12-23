# php-nginx-server
configurations to run php on an nginx server using a single Dockerfile. 

nginx can be used to run php files. This project includes all the neccesary steps to run php files in an nginx server using a single dokcker file. Many articles explains this process using docker swarm or some other orchestration tool. If you are not using any orchestration tool follow these steps to create an up and runnig nginx server to serve php applications

1.Include all the php files in /build directory 
2.Use the depol.sh to easily deploy the docker file in your server. This script kill the previous process and start the current process on the same port 
3.Required configurations can be found in the /config directory 
