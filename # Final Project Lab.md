# Final Project Lab 

# Final Project Part 1:
## VPC Setup:
Under Name tag:
* Add a name for the vpc like “FinalProjVPC”
## Under IPv4 CIDR:
* Add the subnet address which is “10.10.0.0/16” this will be used for both the public and private route tables.
![VPC Settings](https://github.com/liamb8/CloudAdmin-Deploy/blob/main/Photos/VPCSettings.JPG)

## Under Name tag:
* Add a name to identify the Internet Gateway like “FinalProjGateway”
![Internet Gateway](https://github.com/liamb8/CloudAdmin-Deploy/blob/main/Photos/InternetGateway.JPG)

## Route Table Setup:
Under Name:
* Add a name to label the Route Table like “PubRouteTable” and “PrivRouteTable”
* Then select the VPC created earlier as “FinalProjVPC”
* Click “Create Internet Gateway”
* Under Actions 
* Select Edit subnet associations
Select “PubSubnet” or “PrivSubnet” this will associate the route table with that specific subnet
