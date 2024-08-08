<<<<<<< HEAD
# NextGenDevelopers
=======
# Hospital Management System
Hospital Management System using MySQL, Php and Bootstrap

Link: nextgenhospital.online
## Need to work on:

## Prerequisites
1. A server
2. An Editor (Preferably VS Code or Sublime Text)
3. Any web browser 

## Languages and Technologies used
1. HTML5/CSS3
2. JavaScript (to create dynamically updating content)
3. Bootstrap (An HTML, CSS, and JS library)
4. A web server, Digital ocean was used 
5. Php
6. MySQL (An RDBMS that uses SQL)
7. TCPDF (to generate PDFs)


## GETTING INTO THE PROJECT:
Hospital Management System in php and mysql. This system has a ‘Home’ page from where the patient, doctor & administrator can login into their accounts by toggling the tabs accordingly. 


'About Us' page  allows us to get some more information about the quality and the services of the hospital.


‘Contact’ page allows users to provide feedback or queries about the services of the hospital. 


The ‘Home’ page consists of 3 modules:
1. Patient Module
2. Doctor Module
3. Admin Module

### Patient Module:

  &nbsp; &nbsp; &nbsp; This module allows patients to create their account, book an appointment to see a doctor and see their appointment history.
  The registration page(in the home page itself) asks patients to enter their First Name, Last Name, Email ID, Contact Number, Password and radio buttons to select their gender.
  

Once the patient has created his/her own account after clicking the ‘Register’ button, then he will be redirected to his/her Dashboard


The Dashboard page allows patients to perform two operations:

**1. Book his/her appointment:**

  &nbsp; &nbsp; &nbsp; Here, the patients can able to book their appointments to see a doctor. The appointment form requires patients to select the doctor that they want to see, Date and Time that they want to meet with the doctor. The consultancy fee will be shown accordingly to the patient as it was already determined by the doctor.


After clicking on the ‘Create new entry’ button, the patient will receive an alert that acknowledges the successful appointment of the patient 


**2. View patients’ Appointment History:**

  &nbsp; &nbsp; &nbsp; Here, the patient can see their appointment history which contains Doctor Name, Consultancy Fee, Appointment Date and Time

Consultation Fees:

Patients can pay consultation fees using Paystack, with options for mobile money (MoMo) and Visa.
Communication:

Chat with doctors.
Audio and video call functionalities.


Once the patient has logged out of his account, if he wants to go into his account again, he can login his account, instead of register his account again.

This is how the patient module works. On the whole, this module allows patients to register their account or login their account(if he/she has one), book an appointment and view his/her appointment history.

### Doctor Module:

  &nbsp; &nbsp; &nbsp; The doctors can login into their account which can be done by toggling the tab from ‘Patient’ to ‘Doctor’

Once the doctor clicking the ‘Login’ button, they will be redirected to their own dashboard 


In real-time, the doctors will have thousands of appointments. It will be easier for a doctor to search for appointment in the case of more appointments. To make it easier, I have a ‘Search’ box in the navigation bar  which allows doctors to search for a patient by their contact number.
&nbsp; &nbsp; &nbsp; Once everything is done, the doctor can logout of their account. Thus, in general, a doctor can login into his/her account, view their appointments and search for a patient. This is all about Doctor Module.

### Admin Module:
   
   &nbsp; &nbsp; &nbsp; This module is the heart of our project where an admin can see the list of all patients. Doctors and appointments and the feedback/queries received from the ‘Contact’ page. Also admin can add doctor too. 
  &nbsp; &nbsp; &nbsp; Login into admin account can be done by toggling into admin tab of the Home page. 
  &nbsp; &nbsp; &nbsp; `username`: admin, `password`: admin123


On clicking the ‘Login’ button, the admin will be redirected to his/her dashboard as shown in 


This module allows admin to perform five major operations:

**1. View the list of all patients registered:**

  &nbsp; &nbsp; &nbsp; Admin can able to view all the patients registered. This includes the patients’ First Name, Last Name, Email ID, Contact Number and Password. 
  
  
**2. View the list of all doctors registered:**

  &nbsp; &nbsp; &nbsp; Details of the doctors can also be viewed by the admin. This details include the Name of the doctor, Password, Email and Consultancy fees,Searching for a doctor can be done by using the doctor’s Email ID in the search box.


**3. View the Appointment lists:**

  &nbsp; &nbsp; &nbsp; Admin can also able to see the entire details of the appointment that shows the appointment details of the patients with their respective doctors. This includes the First Name, Last Name, Email and Contact Number of patients, doctor’s name, Appointment Date, Time and the Consultancy Fees. 
  
  
**4. Add Doctor:**

  &nbsp; &nbsp; &nbsp; Admin alone can add a new doctor since anyone can register as a doctor if we put this section on the home page. This form asks Doctor’s Name, Email ID, Password and his/her Consultancy Fees.
  
  
  After adding a new doctor, if we check the doctor’s list, we will see the details of new doctor is added to the list 
  
  
**5. View User’s feedback/Queries:**

  &nbsp; &nbsp; &nbsp; Admin is allowed to view the feedback/Query that has been given by the user in the ‘Contact’ page . This includes User’s Name, Email Id, Contact Number and the message(Feedback/ Query) 
  
  
  &nbsp; &nbsp; &nbsp; Taking everything into consideration, admin can able to view the details of patients and doctors, appointment details, Feedback by the user and can add a new doctor. Once everything is done, the admin can logout from his account.

## Updates

### 1. Cancel Appointments
	
   &nbsp; &nbsp; &nbsp; Patients and doctors can able to delete their appointments.
 
    
  If the patient deletes the last record (for doctor Ganesh), then a label "deleted by you" will be displayed in the column 'Current Status' and the action will change to cancel state.
  
  
  Now if we login to the doctor Ganesh's account and view his appointment details, then it will look like this:
  
  
  Similarly doctors can also delete their appointments and patients can view their updated appointment details.
  
### 2. Remove Doctors by Admin

&nbsp; &nbsp; &nbsp; Admin can also delete the doctors from the system. This let admin to have more control over the system.





>>>>>>> 1a1cbf9 (yes)
