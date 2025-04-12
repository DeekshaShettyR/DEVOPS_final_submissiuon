Sign into AWS account 

Create instance

Select server

Putty.exe

Font 14

Connection 

60

Ssh Auth browse installed 

instance file 

Save 

Accept

sudo su

Yum install docker -y

service docker status

service docker start

service docker status

Docker create ubuntu /bin/bash

docker ps -a

Copy id

docker start paste

docker ps

docker ps -a


Docker Create -it --name 
webserver amazonlinux /bin/bash

Docker ps -a

docker start webserver

Docker ps

docker exec -it  webserver /bin/bash

Ls

Exit

docker run -it --name sample ubuntu /bin/bash 

Ctrl p q

Docker ps

Docker run -td --name web-app -p 3002:3000 muralisocial123cart-page-test:1.0

docker ps 

Click on instance id

New browser paste:3002

Can't be reachable 

 Soo
 
Instance 

Instanceid

Security

Security group 

Edit inbound

Add rule 

All tcp

Ipv4




Note
(Environment:server
Dev environment:where software developers test the minimal functionalities of the application
Testing environment:where software testing team performs the functional testcases , non functional testcases and performs the performance testing, load testing 
UAT-user accepted test-before release the product into the market we have to show prototype of the application to the customer 
Production environment -where we actually deploy the application and our customer able to access it
Container-container is a server where we actually going to run the application 
Docker file is a text document it contains set of instructions how to run an application in a container 
Docker file/image-is a template it contains what u need to run the application,it contains our source code , dependencies, configuration files,library ,which platform we want to run our application (build once run anywhere)
Docker hub is a registry where we can store all the docker images 
Post port number- is a user choice .range 0 to 65*** 
This port number defines how to access application from the browser port number,

The docker file is a text document it contains set of instructions 
1. FROM instruction-it will define base image or parent image of the application 
2.  Every docker file must start with from instruction
3. COPY to copy a file or directory from localachine into docker image 
4.ADD command is  same as copy ,+downloading package from internet to docker image 
5.RUN command downloads the dependency, packages or install packages in a container 
6. .dockerinfo
7. CMD command which code or which artifat that we have to run
8 ENTRYPOINT  defines entry of the application.cmd insertion will allow run time arguments entrypoint will not allow the runtime arguments
9.EXPOSE it define on which port number we want to run the application 
9.END DEFINES impronment variables of the application.
10. WORKDIR it defines keep the file inside container
11 USER IF WANT TO CREATE A USER ACCOUNT WE ARE USING THE USER INSTRUCTION 

) 

Github.com /msocial123

Fork 

Main/master select master

Copy code url

Go to powershell 

git clone -b master paste url

Task 
Create a project 
Docker


Create a project website using chatgpt
And write a docker file for that application nd 
Build docker image 






