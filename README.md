# AwsBoto3tool
Tool to track AWS active resources.(Boto3 SDK)

Boto is the official AWS SDK for Python.

We have used the following clients:

### [Cost Explorer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ce.html) : Client representing AWS Cost explorer service
   We use the cost explorer to track costs accrued over a specific time period(Cost is calculated individually for every service)
   
####   Method used : get_cost_and_usage()
   
   
   Sample Image displaying some of the costs using the above method
  
![image](https://user-images.githubusercontent.com/46950265/181297014-fa71a14b-37e6-44c3-bc3d-8391ee8ad23e.png)

### [EC2](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ce.html) : Client representing Amazon Elastic Compute Cloud (EC2)
   We use the ec2 to track all the status of EC2 instances
   
####   Method used : describe_instances()
   
   
   Sample Image displaying the EC2 instance using the above method
  
 ![image](https://user-images.githubusercontent.com/46950265/181299629-3cc96374-10f3-4bb3-93e5-fafd8f212977.png)
 
 ####   Method used : describe_addresses()
   
   The method 'describe_addresses' returns all the reserved Elastic Ip's and their associations(With EC2 instances etc)
   
####   Method used : describe_transit_gateway_attachments()

We use the this method to describe one or more attachments between resources and transit gateways.

### [S3](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html) :  Client representing Amazon Simple Storage Service 
   W
   
####   Method used : list_buckets()
   
   The method "list_buckets" will return a list of all the active S3 buckets being used.
   
