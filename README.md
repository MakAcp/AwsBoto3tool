# AwsBoto3tool
Tool to track AWS active resources.(Boto3 SDK)

Boto is the official AWS SDK for Python.

We have used the following clients:

### [Cost Explorer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ce.html) : Representing AWS Cost explorer service
   We use the cost explorer to track costs accrued over a specific time period(Cost is calculated individually for every service)
   
####   Method used : get_cost_and_usage()
   
   
   Sample Image displaying some of the costs
  
![image](https://user-images.githubusercontent.com/46950265/181297014-fa71a14b-37e6-44c3-bc3d-8391ee8ad23e.png)
