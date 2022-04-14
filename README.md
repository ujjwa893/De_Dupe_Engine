# De_Dupe_Engine

## Description

This was our project for the Database Management Systems Class wherein we have attempted to to implement a complete standalone de duplication system where there will be two modes of operation for the service. One will be a single mode and the other will be a batch
mode. The single mode is useful when a service needs to signup a user for their database and give access to features. They will be able to check if the user is the same person or a different individual based on the data entered. This ensures the trust of the service and prevent unnecessary duplicates from getting entered into the database.

The other mode of operation is the Batch Mode which focusses on the bulk upload from a user in the form of a excel/CSV sheet. This means that the data needs to be processed with respect to an already existing huge database. On successful comparison a report is generated for the admin to look into and remove verify the details of the person for getting added to the database.

The special features of our application is that the user/admin can tune the weights and set a bias according to the knowledge about the significance of the column attributes. The uploaded data undergoes thorough checking for any duplicates and the rows not fulfilling the threshold criteria for uniqueness are returned as error. The data entered has any duplicates the corresponding rows data is displayed with a message along with the similarity score else an affirmation message is displayed.

## Tech Stack used

mongoDB : to store bulk entries with JSON like documents with optional schemas

Flask Server : Framework to create web application

Bootstrap : For front end web development.

## Supporting Screenshots

### Single mode

![image](https://user-images.githubusercontent.com/82048242/163333263-c896fd08-b6c9-4ec1-8ff0-f54e5943ca6d.png)

![image](https://user-images.githubusercontent.com/82048242/163333297-1adfebcd-ea59-4d94-b9e4-d73f0b119642.png)

### Batch mode

![image](https://user-images.githubusercontent.com/82048242/163333408-acea2df7-e5c2-4f9f-a06f-ec29d5d52c15.png)

![image](https://user-images.githubusercontent.com/82048242/163333435-ffd39606-fd3c-4c21-b96d-d9fb90d78625.png)

![image](https://user-images.githubusercontent.com/82048242/163333452-4c28971e-2484-4165-8d70-78e8d22d9534.png)

Kindly read the report for complete details of the implementation.




