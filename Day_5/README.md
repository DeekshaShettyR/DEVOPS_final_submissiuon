DAY 5
PROBLEM WITH CONTENERIZATION 
containers will not support autoscaling 
Scaleup:whenever traffic increases towards the application we have to increase the number of server .
Vertical scaling:we have to increase the system resources 
Horizontal autoscaling:we have to add additional server to existing infrastructure 
What is scale down?
Whenever traffic goes slow towards the application we have to remove additional servers.
Advantage : containers Wiill not support load balancing 
If the container is down we are going to get application down time .
Containers will not support  self healing feature
To overcome the problems we are moving towards the orchestration tool 

What is kubernetes?
Is a container management tool .
It is going to manage All the containers 
Kubernetes performs the automatic deployment of the application 

Kubernetes features:
Orchistration 
Autoscaling
Load balancing 
Self healing 
Kubernets is a platform independent we can run it over any cloud 

To perform the automation kubernetes we are going to write the manifestation file 
Create a jump server or



Launch instance 
Name 
Keypair
Create instance
Instance
Click on instance id
 connect 
Ssh client
Copy the id(ubuntu....)
Create putty using that
In putty terminal 
Vi cluster.sh
Right click(b4 right click msocial123 ,evernorth,in files select install eksct,copy the code)
Escape
Shift : wq
Sudo su
Ls
Sh cluster.sh



In AWS search iam
Iam
User
Create user
Name: Deeksha-k8s
Next
Attach policy
Administrator access(2nd one
Next
Create
Gotouser
Security credentials 
Create access key
Cli
Checkbox
Next
craete accesskey
Download CSV

Goto Server(putty)
AWS configure
Take secretkeys from downloaded file
And region (check by clicking on instance)
Leave fourth one empty
Enter
eksctl
Enter

●

Snap install kubectl --classic 

AWS eks update-kubeconfig --name Deeksha--cluster --region us-east-1

Kubectl get nodes 
Drive new folder
Open in vscode





Note:
Kubernetes will manage the application in cluster 
What is cluster ?
Group of nodes it contains master node and worker node 
Master node: is a hero of the cluster which is going to take care cluster healt
Worker node:where we are going to dploy the the node 
In the cluster atleast we should have 1 worker and 1 master node .
Types of cluster
1 On-premise cluster:
We have to manage this by ourself.
If anything goes wrong in appln we are responsible for that
2 Cloud management cluster


In a master node we have 4 components
1 api server-hero of the cluster
Whenever we perform autoscaling loadbalancing it plays a  crucial role.
2 etcd component-it is a distributed database where we storing info about our cluster appln in the form of key value pairs 
3 controllers: responsible for monitoring the health of the application .this is always  to check if desired status is equal to actual date 
4 scheduler is a component it is is going to scheduling a pod in a node.
In kubernetes we run the appln in pod.pod  contains containers which are sensitive .
Pod is the smallest deployable unit in a kubernetes 



Worker node components
1 Kubelet is responsible for creating pods it is going to act as a agent something goes wrong in the application it communicates to the master node .
We have container run time is nothing but docker is responsible for pulling the docker image creating containers starting the container .it is responsible for managing the container lifecycle 
2 kube proxy:is a networkimg component in the worker load .responsible for creating deployments exposing application over the internet





