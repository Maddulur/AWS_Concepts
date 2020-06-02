# Integrate Cognito with API Gateway
Cognito Authorization:
----------------
Goto Amazon Cognito Service and Click on "Manage User Pools"
![1](https://user-images.githubusercontent.com/63221837/83547236-8a3c5380-a51f-11ea-8f83-7028a2c0f249.png)
Click on "Create a user pool"
![2](https://user-images.githubusercontent.com/63221837/83547239-8b6d8080-a51f-11ea-8068-1b3efe41ae80.png)
Give pool name and click on Review defaults
![3](https://user-images.githubusercontent.com/63221837/83547242-8c061700-a51f-11ea-82cc-861225e6cb5f.png)![2](https://user-images.githubusercontent.com/63221837/83547239-8b6d8080-a51f-11ea-8068-1b3efe41ae80.png)
Click on Create pool
![4](https://user-images.githubusercontent.com/63221837/83547245-8c061700-a51f-11ea-9790-d07965272e86.png)
Click on Domain name
![5](https://user-images.githubusercontent.com/63221837/83547246-8c9ead80-a51f-11ea-9e19-6d46e119c637.png)
Give Domain prefix and Click on check availability, if it shows This domain is available then click on save changes
![6](https://user-images.githubusercontent.com/63221837/83547250-8d374400-a51f-11ea-9669-1ef8f36da511.png)
Give App client name and click on create app client
![7](https://user-images.githubusercontent.com/63221837/83547251-8d374400-a51f-11ea-8e5b-6c950fa4e65d.png)
Copy App client id and App client secret
![8](https://user-images.githubusercontent.com/63221837/83547252-8dcfda80-a51f-11ea-8780-1166e1d8610a.png)
Click on Resource servers and click on Add a resource server
![9](https://user-images.githubusercontent.com/63221837/83547254-8dcfda80-a51f-11ea-9540-1a96d9e2aa9b.png)
Give Resource server details and click on Save changes
![10](https://user-images.githubusercontent.com/63221837/83547256-8e687100-a51f-11ea-8dd2-b1daf8f0e06e.png)
click on App client settings, select client credentials check box and then allow custom scopes then click on save changes

API Server:
-----------
Goto API Server and create new API

Click on Build with in REST API

Give API name and Click on create API

Click on Action and select Create Resource

Give Resource name and then click on Create Resource

Click on Action and then click on Create Method
Create GET and POST Methods

Click on GET methods, select Mock and then click on Save

Click on Integration Responce

Give above details and then click on save


