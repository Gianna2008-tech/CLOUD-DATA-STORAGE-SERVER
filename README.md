# CLOUD-DATA-STORAGE-SERVER
CLOUD DATA STORAGE SERVER
## AIM
To create and configure an Amazon RDS MySQL DB instance with Multi-AZ deployment, connect it to a web application using a security group and DB subnet group, and perform CRUD (Create, Read, Update, Delete) operations on the database through the application.

## ALGORITHM
Log in to the AWS Management Console.
Create a DB Security Group allowing MySQL (3306) access from the Web Security Group.
Create a DB Subnet Group with subnets in two Availability Zones.
Launch an Amazon RDS MySQL Multi-AZ DB instance.
Configure the DB instance with the required username, password, and database name. Wait until the database status becomes Available and copy the endpoint.
Open the provided web application using the Web Server IP.
Enter the RDS endpoint, database name, username, and password.
Connect the application to the database.
Test the application by adding, editing, viewing, and deleting records. 
## Output
<img width="1920" height="1080" alt="Screenshot 2026-08-17 151951" src="https://github.com/user-attachments/assets/0869d38b-ac28-4fc2-9811-27712427e491" />
<img width="1920" height="1080" alt="Screenshot 2026-08-17 151951 - Copy" src="https://github.com/user-attachments/assets/4e111960-577c-45ee-aa77-5958298e5246" />
<img width="1920" height="1080" alt="Screenshot 2026-08-17 152318" src="https://github.com/user-attachments/assets/5f1d67b7-7910-46f0-a827-3238e4425878" />
<img width="1920" height="1080" alt="Screenshot 2026-08-17 154516" src="https://github.com/user-attachments/assets/67c5b58a-8cdb-4ae7-a42c-4e8125caa431" />
<img width="1920" height="1080" alt="Screenshot 2026-08-17 155226" src="https://github.com/user-attachments/assets/3804333d-f9cc-463d-8e8f-31c2930e7f2e" />
<img width="1920" height="1080" alt="Screenshot 2026-08-17 155322" src="https://github.com/user-attachments/assets/e234cfc4-da27-43a5-a134-141ca0c11cbd" />
<img width="1920" height="1080" alt="Screenshot 2026-08-17 155443" src="https://github.com/user-attachments/assets/8b727e15-12d9-4fdc-977e-21b108c80a37" />
<img width="1920" height="1080" alt="Screenshot 2026-08-17 155609" src="https://github.com/user-attachments/assets/18dc872f-9dd8-4e34-9a7b-98eb42e6a237" />
## RESULT
The Amazon RDS MySQL Multi-AZ DB instance was successfully created and connected to the web application, and CRUD operations were performed successfully on the database.
