Hey there, 
Today as a part of learning Docker, I Executed an exciting project on AWS.
Let me walk through all the steps :

1. I Created a simple node.js web application that display some message.
2. Create a docker file with all dependencies and build the image accordingly.
3. Then Push the image over AWS ECR. (here I faced an error message called "AWS CLI not found' ) 
4. AWS ECS here we create one simple cluster with service and attach a test case to it.
5. The test case defines the port mapping with several load balancers. 
 The Test cases have two replicas in service.
6. Now Health check is done every 30 seconds that checks every activity of running containers. 
I have also performed some error operations on top of that to check the reaction for the EC Services. 

Key Understanding :
AWS ECR, AWS ECS, Load balancing, docker integration with ECR and ECS 

Moving forward to learn more about such implementations. 😊
