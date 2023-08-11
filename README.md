# Automating-tagging-an-EC2
This progam will work by automating an alert that an EC-2 instance has been created on AWS and subsequently using eventbridge and a lambda function to find that EC2 server and tag it so that each resource created is easily identifiable. 
The process requires an eventbridge to activate the lambda function and logs eachtime a resource is created thus allowing it to tag each resource with the name of the account user.
