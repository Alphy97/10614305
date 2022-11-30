# CA1 Assignment : cloud technologies for business(B9MG119_2223_TMD1S)

[CA1-Assignment](https://github.com/Alphy97/10614305.git)
 
Lecturer Name :Paul Laird

No of words   : 1120

Presented by  : Alphy K.Mathew 

Student ID    :10614305

## Company choosen :Softila Technologies Pvt Ltd

## Introduction
Businesses struggling to cope with serious IT technical issues, security challenges and the threat their data and systems from cyber hacking, now is the time reassess what technology is for ,and wheather there is an alternative to in-house IT-network. Fortunately we have alternative : cloud computing .Arrival of cloud computing gave an opportunity for SMEs to take control of their IT systems once and for all.Cloud computing offers the chance to take management of all your business's IT issues away while remaining fully in control.

### **Background of the enterprise**
------------------------------------

This report provides analysis of IT setup as well as cloud strategy of Softila technologies Private Ltd.
Softila technologies is a private company established on june 23 2013 in Ernakulam india.
They are focusing on providing IT related services and solutions especially in the field of Automobile,Agriculture,hospitality,Mobile application development and software solutions.The company primarily focuses on publishing, consulting, and provision of software. Software publication comprises the creation, provision, and documentation of pre-built (non-customized) operating systems, business & other applications, and computer game software for all platforms. Providing the best answer in the form of custom software after assessing the user's demands and issues is part of consulting. Custom software also covers software that is created specifically for a user's request. Included are also web page creation, software maintenance, and writing any type of program in accordance with user instructions.
It falls under the section REAL ESTATE,RENTING AND BUSINESS ACTIVITIES and the division COMPUTER AND RELATED ACTIVITIES.

![alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT16LWMQ7MrdTar0NyW0_hUW_kKE4Jd-DWbOXpaOdA-jA&s)
	
### Current IT set up
----------------------

Softila technologies consist of 10 employees.They are building there software apllications using programming languages php,.det,java .Their selected technology of cloud is virtual machines .Basically they are  hosting  everything in a private  cloud based environment .Their chosen cloud service provider is AWS and Godaddy.The development of application software is carried out in local virtual machine .They are using 1 AWS server and 2 Godaddy server to host all of their services . All of the related services including database and JSON are installed and kept in cloud server. One  on-premises server is used particularly for  project management .

![alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ-qf3i77gsc4cLkl9rPXys62fUACpkZ9FQ7PRFkpe4mw&s)
                      
### Contrast of cloud and non-cloud solutions
----------------------------------------------------------
Softila project management and development solutions is done via non cloud solution while application hosting  is done on cloud solution.On analysing these two came to the below points

| Colud                                    | Non Cloud                                                           |
| ---------------------------------------- | --------------------------------------------------------------------|
| Better cost planning and forecasting     |Co-located within the data centre                                    |
| Highest levels of resilience             |Confidential and security is high                                    | 
| Build-in disaster recovery               |Maintenance is difficult                                             |
| vastly improved security and backup      |Remote and out of office working not possible                        |
| Greater scalability                      |Constantly requiring time-consuming manuel updates or costly upgrades|
| Remote and out-of-office working         |Regularly and consistently undertaking the back-ups                  |
| Automation of software updates           |Disaster recovery is very difficult                                  |                                                   | Reduction of cost                        |Underutilised devices                                                |
| Increased collaboration between employees|Scalabily as per the requirement not possible.                       |
|                                          |                                                                     |

### Recommendations and Justifications 

We are analysing their infrastructure in Development,Testing ,Hosting and Project management areas 

***As per the analysis of their current IT set up ,These recommendation would be help them to achieve more result in minimum cost.
Use of platform as a services from cloud for developing their applications instead of local virtual machines and purchasing appropriate tools, for an example they can use amazon EC2,AWS Lambda,Amazon Lightsail,Elastic loadbalancing .These recommendations would  benefit  them during their application development phase.***
   1. **Amazon Light sale** : For developers,students,small enterprises, and other customers who require a solution to build and run their application on cloud,**Amazon Light sale** is a virtual private server(VPS)provider and the simplest method to get started with AWS.
 
  2. **Amazon EC2** :Scalable computing power is offered by **Amazon elastic compute cloud(Amazon EC2)** in the amazon web services cloud.By using amazon EC2,You can develop and deploy apps for quickly because you  won't need to make an upfront hardware investment.

  3. **AWS Lambda** : The serverless compute services **AWS lambda** executes your code in response to events and manages the underlying compute resource for you automatically.These can be updates or status changes,like when a customer adds something to their shopping cart on an e-commerce website.
You can run code with **AWS lambda** without setting up or managing servers.There are no fees when your code is not executing;you only pay for the compute time you use.You may use lambda to run code for almost any kind of application or backend service with no administration required .

 4. **Elastic load balancers** : By using **Elastic load balancers** Incoming traffic is split among numerous targets,including EC2 instances,containers,and IP address in one or more availability zones,It will keep track of the  wellbeing of the registered targets,only sending traffic to those that are good in shape.

***Storing and Hosting they are already using cloud platforms hence no recommendation from our side***
 

***For Testing they are currently using manual testing by the checking the testcases provided by client specifications.I would like to recommend them a cloud based tesing service CloudQA .This aids in cost management.The flexibility, pay-per-use business models,scalability,and testing of complicated test environments combining many operating systems,browsers and platform combinations are further benefits of cloud testing***

  - **CloudDA** : One of the increasingly popular cloud-based automation testing technologies is **CloudQA**.It is capable of testing both online and mobile applications.

***For Project management they are working with their own server.As per them they are not migrating to cloud because of the cost .Company is very small and only 10 employees are there.They are not taking  huge amount of  projects,
They could successfully  maintain that server.As compared with cost associated with it,They found physical server is more affordable.As per their environement and conditions a physical server is enough for dealing with project management of softila technologies***

***For easy and quickly management of users and groups and as well as enabling single sign-on for services and applications I would suggest them microsoft active directory .Administrators and users can easily locate and use the information that active directory holds about network objects.A structured data store serves as the foundation for the logical, hierarchical organization of directory data in Active Directory***

 - **AWS active directory** : AWS active directory service makes it simple to create and maintain directories in the AWS cloud or link your AWS resources to an alreday existing Microsoft active directory that is located on-premises.Onces your directory is ready,It can be used  for number of things,including Manage groups and users.enabling single sign-on for services and application.

**Provided recommendations are based on below advantages  of cloud computing**

- A cloud environment consists of a very extensive infrastructure that offers a pool of IT resources that can be rented on a pay-as-you-go model where only the actual usage of the IT resources is charged. Compared to comparable on-premises environments, the cloud has the potential to reduce initial and operational costs proportional to pay-as-you-go usage.
- The cloud's inherent ability to scale IT resources allows organizations to respond to unpredictable fluctuations in usage without being constrained by predefined thresholds that might deny usage requests from customers. Conversely, the cloud's ability to reduce the required scale is a function directly related to proportional cost benefits.
- By leveraging cloud environments to increase the availability and reliability of IT resources, organizations can better guarantee service quality to their customers and further reduce or avoid potential business losses due to unexpected runtime outages.
 
## Conclusion

Softila technologies infrastructure including both cloud and non-cloud terminologies.As analysed their IT operations and suggested some options based on cloud technologies to improve performance at minimal cost.Also noticed that some specific area like hosting and project management no suggestion is provided beacuse their current option is good to continue with.

## Referance List

Chris Brownlee.(2017) ”Advantages of cloud computing” .CLOUD COMPUTING FOR BUSINESS,32

Softila technologies Pvt Ltd| Available at : [Softila wedsite]( https://www.facebook.com/softila )

AWS cloud service provider | Available at : [Amazon website] ( https://aws.amazon.com )



