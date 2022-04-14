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

![image](https://user-images.githubusercontent.com/82048242/163333934-04f33fa8-e467-473f-9f93-a09ad0153aba.png)


![image](https://user-images.githubusercontent.com/82048242/163334025-6742e052-f34b-488c-b563-d4dd9f976587.png)


### Batch mode

![image](https://user-images.githubusercontent.com/82048242/163334136-3dd63015-a055-4899-ab7e-1b64bb0a80fb.png)


![image](https://user-images.githubusercontent.com/82048242/163334232-9bd0f034-7ff2-420b-8485-68ca646cb110.png)


Kindly read the report for complete details of the implementation.




