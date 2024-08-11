# Alfred Mensah Cloud Portfolio
_______________________________
### This is my cloud portfolio page that is using AWS
### About The Project
#### This is a hands on cloud engineering project delivered by Azubi Africa Cloud team in 2024. After 6 months of AWS cloud training. we got the chance to work on some real life cloud projects.  
#### The purpose of this project is to design a web page that displays some data from a database(AWS Dynamodb) with Dynamodb, AWS SDK, and terraform as tools.
________________________________________________________________________________________________________________________________________________________

### Technologies Used:
__________________________

- #### Git And Github
- #### HTML
- #### CSS
- #### Docker
- #### Terraform
- #### AWS SDK
- #### php
______________________________________________________________________________________________
### Task 1
### Using Terraform to Create DynamoDB
_____________________________________________

### Overview

``` 
1. Install terraform on your local machine

2. Set up your AWS Credentials, by configuring the AWS CLI 

3. Create  a new directory on your local machine and create a file in your terraform directory and name it any name of your choice.

4.  Create dynamoDB table using terraform file

5. Run terraform init to initialise

6. Run terraform plan to preview changes 

7. Run terraform apply to create dynamoDB 
```
### Task 2
#### Linking DynamoDB to Webpage
#### Overview
```
1. Install Xampp server on your local machine and start the aparche server, and mysql.

2. Ensure Apache listens on port 80.

3. Configure your firewall to allow traffic on port 80.

4. Verify if apache is running and accessible.

5. install package manager for php .ie https//getcomposer.org/ .AWS SDK for php

6. clone the files into Xampp htdocs on your local machine

7. Create a new database with the same name ie alfred_db

6.call on dynamoDB to perform desired functions
```
______________________________________________________________________________________________


### Task 3

#### Packaging my application

##### Creating Dockerfile

###### Dockerfile was created from aparche with port 80 exposed as shown below

```
FROM php:8.2-apache

COPY . /var/www/html/

EXPOSE 80
```

