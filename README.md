# PatientRecordsDbApp
This project performs CRUD operations on the MYSQL database.
Database "patientrecords" consists of a table "patients". We have used XAMPP to connect with local MYSQL database through Apache server.

Following are the files in the project - 
1. Patient.java
    This is a model class which consists of patient details
2. UserMenu.java:
    Displays list of options to choose for CRUD operations on the database for the end user. 
3. Controller.java:
    Based on the user's choice passed from UserMenu.java, Controller class collects the user inputs for inserting/updating a record
4. PatientDao.java:
    Based on the user inputs passed from Controller.java, this class connects with the MYSQL database and performs CRUD operations
