**what is AWS?**

AWS is amazon web service which provide variety of services which are inexpensive and free to join, pay only for what you use.

**Services Provided by AWS:**
-----------

**1.Elastic compute cloud:**

It is used to create an instance and with the help of that you can create your laptop with whatever size of RAM and PROCESSOR and OS you want and according to that it will cost the price.

**Steps to launch EC2 Instance:**

1.login to your AWS console After that Search for EC2 in your services search bar and select EC2 so you will get the below image:

![ec2](https://user-images.githubusercontent.com/64422457/80917018-f473a400-8d79-11ea-9238-13f2e0579ef8.png)

2.click on launch instance and after that you will get below image:

![ec21](https://user-images.githubusercontent.com/64422457/80917289-77492e80-8d7b-11ea-8a84-6d50efeb8850.png)

3.After that in search box whatever windows,linux,ubuntu you can search that in search box which shown in above image:

4.Then you need to select instance type,ram,processor and click on next :

![ec3](https://user-images.githubusercontent.com/64422457/80917576-7d400f00-8d7d-11ea-9a50-fabefada9814.png)

5.In configuration details keep everything default and go to next:


![ec4](https://user-images.githubusercontent.com/64422457/80917871-48cd5280-8d7f-11ea-9408-69dd5efc7458.png)



6.In add storage select the size and type of storage and go to next:

![ec5](https://user-images.githubusercontent.com/64422457/80917991-2be54f00-8d80-11ea-99dd-3b27e67d7894.png)



7.In tags you need to give whatever name you want so you can identify your insatnce:

![Screenshot (111)](https://user-images.githubusercontent.com/64422457/80918156-145a9600-8d81-11ea-81a5-f9f5f5708989.png)





8.After adding tag click on Configure security group and here you can create a security group give it any name and description, but if you already have and existing group you can use it:


![ec7](https://user-images.githubusercontent.com/64422457/80918186-5b488b80-8d81-11ea-97ad-c8ff02497bef.png)


9.you can review and launch the instance:

10.you will get this window select create a new key and give a name and download the key:

![ec8](https://user-images.githubusercontent.com/64422457/80918332-fc374680-8d81-11ea-8e73-bd77957bc98f.png)

this key is very important like without this key you can not open your file

11.now click on launch you can see ur instance:

![ec8](https://user-images.githubusercontent.com/64422457/80918586-5c7ab800-8d83-11ea-8a95-cf9b960f193a.png)

so if your local os is windows you need to connect your ec2 instance with third party app MOBAXTERM download the portable edition

once you install this application and run it click on session on top left corner and choose SSH.

after that copy ec2 ip address to remote host and in specify username give ec2-user.

and then go to advance ssh setting,click on checkbox use private key and upload your downloaded key pair

![Screenshot (112)](https://user-images.githubusercontent.com/64422457/80918886-c778be80-8d84-11ea-85d4-2e22677a115b.png)

after click on ok your connection get established.


![Screenshot (113)](https://user-images.githubusercontent.com/64422457/80919001-466df700-8d85-11ea-96d5-3ca088496273.png)

**2.S3:**

It is used for data storage.If we want to upload PHOTO,VIDEO,DOCUMENT to AMAZON S3 you must first create an S3 bucket in one of the AWS Regions. You can then upload any number of objects to the bucket.

**steps for creating s3:**
1.first go to service and select S3 service after selecting S3 you will get below tab:

![Screenshot (119)](https://user-images.githubusercontent.com/64422457/81100339-0136fa00-8f2a-11ea-9bdf-e9114537aab3.png)

2.after that click on create bucket and then give your bucket name:

![1 name](https://user-images.githubusercontent.com/64422457/81101862-5b38bf00-8f2c-11ea-94fd-93707642aa2c.PNG)

3.after creating bucket you will get view :

![2 S3-view](https://user-images.githubusercontent.com/64422457/81102181-e023d880-8f2c-11ea-9f41-7d1318f6c3f6.PNG)

4.after that click on new folder and click on upload to a file:
![3 to-Create-folder](https://user-images.githubusercontent.com/64422457/81102307-13fefe00-8f2d-11ea-9fbd-98da160b4452.PNG)

![5 Create-folder](https://user-images.githubusercontent.com/64422457/81102964-fd0cdb80-8f2d-11ea-8c32-e04c6dce7355.PNG)

5.so after creating folder we need to upload file:

![4 to-Upload](https://user-images.githubusercontent.com/64422457/81102644-8cfe5580-8f2d-11ea-95e2-26f4a750b57e.PNG)

6.so follow the below steps for uploading file:
![6 folder-uploaded](https://user-images.githubusercontent.com/64422457/81103227-61c83600-8f2e-11ea-9975-df6cd73b1bb1.PNG)

![6 upload](https://user-images.githubusercontent.com/64422457/81103229-6260cc80-8f2e-11ea-860e-8b95f7dfd21a.PNG)

![7 uploaded](https://user-images.githubusercontent.com/64422457/81103307-79072380-8f2e-11ea-8f41-0b8a7db5631d.PNG)

7.To make a file public go on static website hosting option and then give ur uploaded file name:

![8 public](https://user-images.githubusercontent.com/64422457/81103767-267a3700-8f2f-11ea-8481-ea7529fd124d.PNG)

8.Then select action and make them public:

![9 Make-public](https://user-images.githubusercontent.com/64422457/81103949-693c0f00-8f2f-11ea-9063-6f1312ca4da8.PNG)

9.SO your S3 bucket is ready 


**RDS(RELATIONAL DATABASE SERVICE):**

Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate, and scale a relational database in the cloud.


STEPS for connection RDS to your system:

1.Go in search box and search for RDS and click on CREATE DATABASE:

![Screenshot (122)](https://user-images.githubusercontent.com/64422457/81410436-56f3e800-915e-11ea-977f-6542fb677490.png)

2.Then select Easy create and then select Mysql:
![Screenshot (123)](https://user-images.githubusercontent.com/64422457/81410852-0c26a000-915f-11ea-84ee-5ed6517acd58.png)

3.After that select on free tier,then giver your dtabasename and give your master username and give password and remember that password:

![Screenshot (124)](https://user-images.githubusercontent.com/64422457/81410862-0f219080-915f-11ea-96c4-ecbf4c7035b2.png)

4.after that before hit on create database go to additional configuration and make your dtabase public so you can access it outside your AWS so after that you can click on create database:

![Screenshot (125)](https://user-images.githubusercontent.com/64422457/81413015-5eb58b80-9162-11ea-803b-2d4213d15aa4.png)

![Screenshot (126)](https://user-images.githubusercontent.com/64422457/81413463-177bca80-9163-11ea-99ed-91425bf8bd29.png)

5.Then go to defaulty security group after that go to edit inbound rule and click on add rule and save the rule:

























