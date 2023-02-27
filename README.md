# CS470 Final Reflection
Kalin Mason
02/26/23
YouTube Link - https://www.youtube.com/watch?v=O3qraT2uxAE

# Reflection 

Through this course I was able to learn more about cloud computing and the various components that go into such. I learned how to organize containers, use docker to spin up and create those containers, use of Docker files, as well as utilization of the AWS suite services. I was able to create a working application through S3, DynamoDB, Lambda, and API Gateway.

As a software developer I feel my strengths lie in troubleshooting and problem solving. As this course was a first for me to learn about AWS I was able to work through many problems I stumbled across such as security access, API header handling, and CORS issues. 

With this course I feel I was able to learn the skills needed for a FSE. I was able to learn how to leverage AWS S3 to contain my front-end application logic, use Lambda functions to create event based triggers that would interact with the back-end and front-end together. I was lastly able to create two DynamoDB that would contain questions and answers while tying them together. 

When it comes to handling scale and error handling. I was able to develop an application that would handle errors such as users entering in bad information that would prevent the user from submitting anything to the database. I was also able to learn about scalability and being able to create an application that would scale vertically through AWS S3 and Lambda. 

To predict the cost of the application, I was able to leverage the built in Graphs and metrics behind the uses of these services. From there I was able to compute the cost per action or event. This model allowed me to predict accurately how much the application would cost to maintain in AWS.

I think serverless is far easier to compute the cost of compared to containers. With containers, you don't really have any metrics to go off of and see how much resources are being used. With serverless you get a lot of data surrounding resource uses and being able to compute the cost from this. 

When it comes to deciding factors in a plan for expansion it can be broken down in to pros and cons. 
Pros: User experience, ease of scale from AWS, and fast to market builds. With these pros we will be able to increase the user experience with the ease of scale from AWS. With AWS we can get to market quickly because a lot of the heavy lifting was abstracted away from us. 
Cons: Cost for more services, more moving parts to maintain, and project complexity. With these cons there would be a potential of cost for increasing the number of services, there would be more moving parts with the project you'd need to maintain. Also the overall complexity of the project would increase due to the increase in services.

When it comes to pay-for-service we can be assured that we will only pay for what we use. This makes AWS a compelling argument to use as we don't need to do a cost analysis on resources we may not even use but built into our project. With AWS we can pay for what we use and be flexible by turning on and off services that can grow vertically and horizontally. 
