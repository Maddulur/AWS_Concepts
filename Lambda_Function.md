# Lambda Function - Node.js

Goto AWS Management Console and search Lambda service 
![1](https://user-images.githubusercontent.com/63221837/83593478-7bcf5580-a57a-11ea-9948-21df825f22f0.png)

Click on Create function

![2](https://user-images.githubusercontent.com/63221837/83593481-7d008280-a57a-11ea-95f9-c6ee88c98515.png)

Give Details as shown above and Click on create function

![3](https://user-images.githubusercontent.com/63221837/83593484-7d991900-a57a-11ea-80a1-39dfe99bce33.png)

Goto Function Code and paste below code and save the function

    exports.handler = (event, context, callback) => {
        let min = 0;
        let max = 100;
        let rand = Math.floor(Math.random()*max)+min;
        callback(null, rand);
    };

Click Test button and just accept the popup for test config. Then, we get the number generated and the logs:
![4](https://user-images.githubusercontent.com/63221837/83593486-7d991900-a57a-11ea-97f1-8d8bc4903047.png)
