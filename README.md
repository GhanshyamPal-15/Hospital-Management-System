# Hospital-Management-System
A simple console-based Java project created for learning and practice, along with Git and GitHub concepts.

Hospital Management System

A simple console-based Hospital Management System developed in Java. This project demonstrates basic Java programming concepts such as classes, objects, encapsulation, ArrayList, methods, constructors, and user input using Scanner.

Features : 
Add a new patient
Add a new doctor
Schedule an appointment
View all patients
View all doctors
View all appointments
Automatically generate unique Patient IDs
Automatically generate unique Doctor IDs
Validate Patient and Doctor IDs when scheduling appointments


Technologies Used :
Java
IntelliJ IDEA
ArrayList
Scanner
Object-Oriented Programming (OOP)


Project Structure :
HospitalManagement/
└── src/
    └── com/
        └── management/
            ├── blc/
            │   ├── Patient.java
            │   ├── Doctor.java
            │   └── Appointment.java
            │
            └── elc/
                └── HospitalManagement.java
                
Package Structure :
*BLC (Business Logic Code) contains the main data classes and business objects.

It stores:
Patient
Doctor
Appointment date


*ELC (Event Logic Code) contains the main application logic.

This is the main class of the application. It provides a menu through which the user can perform different operations.
Application Menu :
When the application starts, the following menu is displayed:

Hospital Management System
1. Add Patient
2. Add Doctor
3. Schedule Appointment
4. View Patients
5. View Doctors
6. View Appointments
0. Exit


Example :

Adding a patient:

Enter Patient Name: Rahul
Enter Patient Age: 25
Enter Patient Gender: Male
Patient added successfully!


Adding a doctor:

Enter Doctor Name: Sharma
Enter Doctor Specialty: Cardiology
Doctor added successfully!

Scheduling an appointment:

Enter Patient ID: 1
Enter Doctor ID: 1
Enter Appointment Date (YYYY-MM-DD): 2026-08-25
Appointment scheduled successfully!


Current Limitations:
This is a beginner-level console application.
Data is stored only in memory.
Data is lost when the application is closed.
There is no database.
There is no graphical user interface.
There is no login/authentication system.
Appointment dates are currently stored as String.



Future Improvements :
Possible improvements include:
Add MySQL database integration
Add a graphical user interface
Add patient search functionality
Add doctor search functionality
Add appointment cancellation
Validate appointment dates
Add login and authentication
Add exception handling for invalid user input
Store and retrieve hospital data from a database

Important Note : 
This project is intended for learning  purposes only. 
