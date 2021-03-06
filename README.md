# :trident: Integration of AWS RDS and WordPress app running on EC2 Instance :trident:

![wordpress-rds-ec2](https://user-images.githubusercontent.com/78288350/116659353-1a448080-a9af-11eb-8e52-2bd4230e63c8.jpg)

###### :dart: In this article we are going to deploy "WordPress" which is a free and open-source content management system written in PHP on top of AWS EC2 Instance!

###### :dart: As WordPress is a frontend application it requires a database to store its data. So we will use MySQL Database Server as a backend database for WordPress and MySQL will be setup using Amazon RDS. 

###### :dart: Finally, we will provide the endpoint of MySQL to WordPress for connectivity.

## :beginner: TASK DESCRIPTION:

###### :white_check_mark: Create an AWS EC2 instance.

###### :white_check_mark: Configure the instance with Apache Webserver.

###### :white_check_mark: Download php application name "WordPress".

###### :white_check_mark: As wordpress stores data at the backend in MySQL Database server. Therefore, you need to setup a MySQL server using AWS RDS service using Free Tier.

###### :white_check_mark: Provide the endpoint/connection string to the WordPress application to make it work. 

> ## “Technology is just a tool. In terms of getting the kids working together and motivating them, the teacher is most important.”

> ## ~ by Bill Gates

:boom: So let's start walking through this Task & Complete it!

## :beginner: Step 1 👉 Create an AWS EC2 instance

###### 🔅 We need to launch an EC2 Instance on AWS which we will use to configure Apache Webserver and run WordPress.

###### :dart: Let’s quickly launch the instance:

![1](https://user-images.githubusercontent.com/78288350/116660548-d488b780-a9b0-11eb-9a39-f95671b7283f.png)
![2](https://user-images.githubusercontent.com/78288350/116660554-d6527b00-a9b0-11eb-9679-6411e538a39a.png)





