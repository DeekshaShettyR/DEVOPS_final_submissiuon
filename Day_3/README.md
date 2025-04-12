Day 3 terraform
Install terraform for windows

Go to cdrive, program files,create new folder called terraform,extract downloaded file to created folder,double click on path add it to system variable path -edit-ok.


Install AWS commandline on windows

Powershell-   aws --version


Login to AWS account 

Menu

Security identify and compliancea

Iam

Users

Create user

Name 

Next

Next

Attach(add permissions)

EC2

SelectAmazon...

Vpc

SelectAmazon...

Next

Create user

Open users

Security credentials 

Create access keystone 

Commandline

Checkbox

Go to powershell

AWS version

AWS confiqure

Copy access id

Paste here

Secret key

Region 

Terraform script folder inside c 

load it into vs code

Open folder

Create file terraform script

Go to extension search for 
terraform
Install
EC2.tf
Code
Take ami key name from AWS account

Go to terminal -terrform init
terraform validate
terraform plan
terraform apply
Yes
Apply complete
Goto AWS can't
Instances 
Click on created instances
Go terminal 
terraform destroy
Aws
Terraform state
terraform apply







Note;
While writing terraform we use blocks such as provider-dedines which cloud doing automation
We hav to write resource block -what kind of resource we want to create on cloud 
Output.ta file-if we want to print op in console 

When u creating instance using terraform script make sure to pass 5 parameters
Amazon id
Keypair name
Storage
Instance name

Terraform destroy automatically delete all the resources we created .
DOCKER is a contenerization tool which can help us to create portabile application   to use resources effectively to create platform independent applications we are going with the docker .
Docker is going to perform os level virtualization technique.
We are going to use docker to reduce the cost of the server and to run the application wherever we want.
Application will divide into the modules called as microservices each and every microservices will have separate docker container.
Every microservice application will deploy in a container .
Monolithic docker is a single tier rchitecture which means webserver application server database server we are combine together and we are deploying in a single Server issues with the monolithic application 
If any module go down complete application goes down bcz tightly coupled nature
If any service  go down complete application goes down so go for microservices.
Microservices breakdown application into the independent services that's called loosely coupled application.
If any service goes down only customer will not able to access that particular service others can .
There are some issues each microservice requires single server so high costing.
To reduce the cost to create a platform independent applications to create portability (build once run anywhere) of the application
