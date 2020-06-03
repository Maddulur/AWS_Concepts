# Integrate Cognito Service With APIGateway

Goto Amazon Cognito Service and Click on "Manage User Pools"
![1](https://user-images.githubusercontent.com/63221837/83547236-8a3c5380-a51f-11ea-8f83-7028a2c0f249.png)

Click on "Create a user pool"
![1](https://user-images.githubusercontent.com/63221837/83595598-20a06180-a580-11ea-8f9d-f22fd4ff48b5.png)
Give pool name and click on Review defaults

![2](https://user-images.githubusercontent.com/63221837/83595602-226a2500-a580-11ea-973d-c04f49761576.png)

Give App Client Name and then click on Create App client name
Now Goto click on Review and then Click on "Create User Pool"

Now we need to create a Domain Name, for this we need to click on domain name

![3](https://user-images.githubusercontent.com/63221837/83595604-226a2500-a580-11ea-9db4-47f5d04a5d29.png)

Give Domain prefix and check availability. If it is available click on save changes

Now we need to add Resource Server for our App client. Here we can create scopes
![4](https://user-images.githubusercontent.com/63221837/83595605-2302bb80-a580-11ea-99f6-1f298d52d200.png)

Click on Resource servers and give name for Resource server, Identifier and scopes. Then click on save changes

![5](https://user-images.githubusercontent.com/63221837/83595607-239b5200-a580-11ea-9815-282a62b19d7e.png)

Attach this Scope to our App Client. Click on App Client settings

![6](https://user-images.githubusercontent.com/63221837/83595608-2433e880-a580-11ea-8d6f-71fe0a8133a4.png)

Select Client Credentials and then select Allow custom scopes then save

Now we are going to integrate Cognito with API Gateway:
---------------

