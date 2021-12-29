![image](https://user-images.githubusercontent.com/96166776/147625857-f78a557f-62d3-47b2-8413-5331f24f4509.png)

# php-nginx-server
configurations to run php on an nginx server using a single Dockerfile. 

nginx can be used to run php files. This project includes all the neccesary steps to run php files in an nginx server using a single dokcker file. Many articles explains this process using docker swarm or some other orchestration tool. If you are not using any orchestration tool follow these steps to create an up and runnig nginx server to serve php applications

## Follow below steps  

1. Include all the php files in /build directory 

2. Use the depoly.sh to easily deploy the docker file in your server. This script kill the previous process and start the current process on the same port 

3 .Required configurations can be found in the /config directory 


If you need to enable https, upload relavant certificates to the /cert directory.  you can install self signed certificates for testing purposes



Read more on installing nginx server from source : https://medium.com/@dahamne/installing-nginx-from-source-e13517ba0e9c

### Enjoy!!
