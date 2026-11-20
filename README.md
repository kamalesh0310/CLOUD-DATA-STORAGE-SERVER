# CLOUD-DATA-STORAGE-SERVER
CLOUD DATA STORAGE SERVER
## Aim

To create and configure an Amazon Relational Database Service (Amazon RDS) instance as a cloud data storage server, configure the required security settings, connect it to a web application, and perform database operations using the application.

## Algorithm / Steps

1. Create a Security Group for the RDS database.
2. Add an inbound rule to allow MySQL (Port 3306) access from the Web Security Group.
3. Create a DB Subnet Group using two Availability Zones.
4. Launch an Amazon RDS MySQL database instance.
5. Configure the database with the required identifier, username, password, storage, and instance class.
6. Associate the database with the created Security Group and Subnet Group.
7. Wait until the database status becomes **Available**.
8. Copy the RDS endpoint.
9. Open the web application using the provided Web Server IP address.
10. Enter the RDS endpoint, database name, username, and password.
11. Connect the application to the database.
12. Verify the connection by adding, editing, and deleting records in the Address Book application.
## Output
<img width="1920" height="1080" alt="Screenshot (92)" src="https://github.com/user-attachments/assets/9e6051ad-7748-4df7-a3ca-a2376a9c1198" />
<img width="1920" height="1080" alt="Screenshot (94)" src="https://github.com/user-attachments/assets/cfa86bdf-80ef-4794-996a-302cddc402ea" />
<img width="1920" height="1080" alt="Screenshot (95)" src="https://github.com/user-attachments/assets/d2be1c16-5144-44c6-89af-f39ab981021a" />
<img width="1920" height="1080" alt="Screenshot (96)" src="https://github.com/user-attachments/assets/f6a11e29-b850-4a42-9638-88143f209221" />
<img width="1920" height="1080" alt="Screenshot (97)" src="https://github.com/user-attachments/assets/d7581dc7-3ae0-4285-b7ae-f705658aadf4" />
<img width="1920" height="1080" alt="Screenshot (98)" src="https://github.com/user-attachments/assets/347abb7e-35ab-4b85-b2d7-463b8e1a41f3" />
## Result
Thus, an Amazon RDS database instance was successfully created and configured as a cloud data storage server. The database was securely connected to a web application, and data operations such as inserting, updating, and deleting records were successfully performed through the application.
