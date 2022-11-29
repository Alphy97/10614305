<<<<<<< HEAD
=======
# CA1-Assignment 
https://github.com/Alphy97/10614305.git
# reference 
           # heading first
           ## sub section
           ### sub section2
Bold	**bold text**
Italic	*italicized text*
Blockquote	> blockquote

1. First item
2. Second item
3. Third item
	
- First item
- Second item
- Third item

`code`

Link	[markdow_cheat sheet](https://www.markdownguide.org/cheat-sheet/)
Image	![alt text](https://www.bing.com/images/search?view=detailV2&ccid=NAi4PT8k&id=59DD8316EDDA8F292AE650E9F1276AC02A2960E8&thid=OIP.NAi4PT8kn24pym5kXDhzKwHaGb&mediaurl=https%3a%2f%2fupload.wikimedia.org%2fwikipedia%2fcommons%2fthumb%2fb%2fbd%2fCheckmark_green.svg%2f1200px-Checkmark_green.svg.png&cdnurl=https%3a%2f%2fth.bing.com%2fth%2fid%2fR.3408b83d3f249f6e29ca6e645c38732b%3frik%3d6GApKsBqJ%252fHpUA%26pid%3dImgRaw%26r%3d0&exph=1042&expw=1200&q=checkmark+image&simid=607998336914706731&FORM=IRPRST&ck=48B478F09B51C36B46E6E731E87FFEE5&selectedIndex=0&idpp=overlayview&ajaxhist=0&ajaxserp=0)

# Company choosen :Softila Technologies Pvt Ltd

## Introduction
Businesses struggling to cope with serious IT technical issues,security challenges and the threat their data and systems from cyber hacking,now is the time reasses what technology is for ,and wheather there is an alternative to in-house IT-network. Fortunately we have alternative :cloud computing .Arrival of cloud computing gave an opportunity for SMEs to take control of their IT systems once and for all.Cloud computing offers the chnace to take management of all your business's IT issues away while remaining fully in control.

### **Background of the enterprise**
------------------------------------

This report provides analysis of IT setup as well as cloud strategy of Softla technologies Private Ltd.
Softla technologies is a private company established on june 23 2013 in Ernakulam india.
They are focusing on providing IT related services and solutions especially in the field of Automobile,Argriculture,hospitality and software solutions.The company primarily focuses on publishing, consulting, and provision of software. Software publication comprises the creation, provision, and documentation of pre-built (non-customized) operating systems, business & other applications, and computer game software for all platforms. Providing the best answer in the form of custom software after assessing the user's demands and issues is part of consulting. Custom software also covers software that is created specifically for a user's request. Included are also web page creation, software maintenance, and writing any type of program in accordance with user instructions.
It falls under the section REAL ESTATE,RENTING AND BUSINESS ACTIVITIES and the division COMPUTER AND RELATED ACTIVITIES.

![alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT16LWMQ7MrdTar0NyW0_hUW_kKE4Jd-DWbOXpaOdA-jA&s)
	
### Current IT set up
----------------------

Softila technologies consist of 10 employees.They are bulding there software apllications using programming languages php,.det,java .Their selected technology of cloud is virtual machines .Basicaly they are  hosting  everything in a private  cloud based environment .Their choosen cloud service provider is AWS and Godaddy.The development of application software is carried out in local virtual machine .They are using 1 AWS server and 2 Godaddy server to host all of their services . All of the related services which are in need for the hosting including database and JSON are installed and kept in cloud server. 1 onpremises server is used particularly for  project management .

![alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ-qf3i77gsc4cLkl9rPXys62fUACpkZ9FQ7PRFkpe4mw&s)
                      
# Recommendations and Justifications 

### Contrast of cloud and non-cloud solutions of softila
----------------------------------------------------------
Softila project management and development solutions is done via non cloud solution while application hosting  is done on cloud solution.On anlysising these two came to the below points

| Colud                                    | Non Cloud                                                           |
| ---------------------------------------- | --------------------------------------------------------------------|
| Better cost planning and forcasting      |Co-located within the data centre                                    |
| Highest levels of resilience             |Confifencial and security is high                                    | 
| Build-in disaster recovery               |Maintenance is difficult                                             |
| vastly improved security and backup      |Remote and out-of office working not posible                         |
| Greater scaleability                     |Costantly requiring time-consuming manuel updates or costly upgrades |
| Remote and out-of-office working         |Regularly and consistently undertaking the back-ups                  |
| Automation of software updates           |Disaster recovery is very difficult                                  |                                                   | Reduction of cost                        |Underutilised divices                                                |
| Increased collaboration between employess|Scalabily as per the requiremnt not possible.                        |
|                                          |                                                                     |

- As per the analysis of their curresnt IT set up ,These recommendation would be help them to achieve more result in minimun cost.
Use of  already bult in platform as a serverices from cloud for developting their applications insted of location virtual machine and purchasing tools needed for the development ,for an example they can use amazon EC2,AWS Lambda,Amazon Lightsail,Elastic loadbalancing .These recommendtaion would be benefit for them during their application development phase.

               1.Amazon Light sale
             
For developers,students,snall enterprises, and other customers who require a solution to build and run their application on cloud,**Amazon Light sale** is a virtual private server(VPS)provider and the simplest method to get started with AWS.
 
               2.Amazon EC2
                  
Scalable computing power is offerd by **Amazon elastic compute cloud(Amazon EC2)** in the amazon web services cloud.By using amazon EC2,You can develop and deploy apps for quickly because you dont won't need to make an upfront hardware investment.

               3.AWS Lambda

The serverless compute services **AWS lambda** executes your code in response to events and manages the underlying compute resource for you automatically.These can be updates or status changes,like when a customer adds something to their shopping cart on an e-commerce website.
You can run code with **AWS lambda** withour setting up or managing servers.There are no fees when your code is not executing;you only pay for the compute time you use.You may use lambda to run code for almost any kind of application or backend service with no administration required .

              4.Elastic load balancers 

By using **Elatic load balancers** Incoming trafic is split among numerous targets,including EC2 instances,contaniners,and IP addresss in one or more availability zones,It will keep track of the  wellbeing of the registerd targets,only sending traffic to those athat are good in shape.

- Storing and Hosting they  are already using cloud platforms hence no recommendation from our side.

- For Testing they are currently using manuel testing by the checking the testcases provided  the client specifications. I would like to recommend them a cloud based tesing service CloudQA .This aids in cost management.The flexibility, pay-per-use business models,scalability,and testing of complicated test environments combining many opearting systems,browsers and platform combinations are further benefits of cloud testing.

             5.CloudDA

One of the increasingly popular cloud-based automation testing technologies is **ClodQA**.It is capable of tesing both online and mobile applications.

-For Project management they are working with their own server.As per them they are not migrating to cloud because of the cost .Company is very small and only 10 employees are there.They are not taking  huge amount of  projects,
They could successfully  maintain that server.As compared with cost associated with it,They found physical server is more affodable.As per their envirnement and conditions a physical server is enough for dealing with project managent of softila technologies.
-For easy and quickly management of users and groups and aswell as enabling single sign-on for services and applications I would suggest them microsoft active directory .Administartors and users can easily locate and use the information that active directory holds about network objects.A structured data store serves as the foundation for the logical,hierarchical organization of directory data in Active Directory

          6.AWS active directory

AWS active directory service makes it simple to create and maintain directories in the AWS cloud or link your AWS resources to an alreday-existing Microsoft active directory that is located on-premises.Onces your directory is ready,It can be used  for number of things,including Manage groups and users.enabling single sign-on for services and application.


