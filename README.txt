Deploy a high-availability web app using CloudFormation

In this project, I have deployed a dummy application to the Apache Web Server running on an EC2 instance.

The files included are:
Diagram.png - Visual aid to understand CloudFormation Script
create.sh - shell script to create CloudFormation stack
update.sh - Shell script to update CloudFormation stack
network.yml - Network CloudFormation script
network-parameters.json - Network CloudFormation parameters script
server.yml - Servers CloudFormation script
server-parameters.json - Servers CloudFormation parameters script


Load Balancer URL:
http://Proje-WebAp-199WJW3XFQNIG-961963603.us-east-1.elb.amazonaws.com
Note: Will be removed once project has been reviewed.

To recreate the Project run the following command:
./create.sh Projectname network.yml network-parameters.yml
./create.sh Projectname2 server.yml server-parameters.yml