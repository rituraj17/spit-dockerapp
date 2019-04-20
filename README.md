# SPIT-dockerapp
Sample For SPIT-Docker-Demo


# Steps to deploy:

git clone the repo

cd into the clone repo

sudo docker build -t sample-image:v1 .

sudo docker images                                                  
[Note: list the image that you have created]

sudo docker run -it -d -p 8080:8080 --name=demo_app sample-image:v1  
[Note: Run the Application image with name demo_app]

sudo docker ps -a      
[Note: check if the container has been deployed and for other details like started,running,exited]


# Test your Application

write the below http link after changing the localhost or IP address on a web browser

http://[localhost or IP address]:8080


# Output:

You will get the below output on the output after the requesting


Flask Dockerized

 
# For more Details of Docker example:
  
https://likegeeks.com/docker-tutorial/

https://medium.com/the-andela-way/docker-for-beginners-61e8e0ce6a19

https://towardsdatascience.com/learn-enough-docker-to-be-useful-b7ba70caeb4b

https://www.katacoda.com/
