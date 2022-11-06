# Vaccine-Tracker
Vaccine Tracker for School

CROSS-PLATFORM APPLICATION DEVELOPMENT
PROJECT 1 – CROSS-PLATFORM APP DESIGN AND IMPLEMENTATION 
SCHOOL VACCINATION TRACKER
Weightage: 25%

Recently the Government of India has given permission to vaccinate the school going children under age of eighteen with the Covid vaccination. The government is also thinking to manage this effort at the school level as it will be easier to track and manage the vaccination drive progress. Also parents will be assured about the safety of the ward as all the students belonging to a particular school will be vaccinated in the one go providing a safe learning environment for all. 
OBJECTIVE: 
To create working prototype of cross-platform application (involving both frontend and backend components with interactions between them) for the specified user stories using the technologies / frameworks discussed in the classroom sessions
PROBLEM STATEMENT: 
A web based vaccine tracking system to be specifically designed for administration, tracking and management of vaccination for schools
As a part of this assignment, you are required to implement the User Interface and its related functionalities for the features listed below as user stories. 
EPIC 1: SCHOOL COORDINATOR LANDING PAGE
User Story 1.1: 
As a school coordinator, I should be presented with a landing page on successful login.

Description: The school coordinator page should contain a dashboard view and a navigation
menu to Add/Manage student details, Manage/update Vaccination status, generate reports.
The Dashboard to contain the status of analytics (number of students vaccinated, upcoming
vaccination drives etc.

Acceptance Criteria:
•	If there are no vaccination drives, it should display a message “no upcoming drives”.
•	The status of number of students registered vs number of them vaccinated to be displayed.

User Story 1.2: 
As a school coordinator user, I should be able to select the menu items.
Description: On clicking the menu item “Add/Manage student details”, the user should be
navigated to the student details page.
Acceptance Criteria:
•	A form to accept individual student details to be provided 
•	Bulk upload of student details option to be provided. 

User Story 1.3: 
As a school coordinator user, I should be able to generate the report of the vaccinations
administered with student details.
Description: On clicking the “generate report” and selecting appropriate filters the user should
be able to view the list of students with vaccination details like vaccinated status, date of
vaccination, name of vaccine. Filtering options with name of vaccination to be present
Acceptance Criteria:
•	The student details with vaccination details like vaccinated status, date of vaccination, name
•	of vaccine to be displayed in a table. 
•	Pagination to be applied. 
•	Option to download the details in a CSV/ excel/ pdf to be provided.

Assumptions for EPIC 1
•	User interfaces, client side validation and backend code with APIs need to be implemented.
•	It is assumed that the users are successfully created/logged in successfully and directed to landing page.
•	The vaccination status details are fetched from the backend and available in JSON format
•	Any other assumptions made can be listed in the documentation.

EPIC 2: MANAGE VACCINATION DRIVE
User Story 2.1: 
As a school coordinator, I should be able to book a vaccination drive
Description: The school coordinator should be able to enter the details of the vaccination drive
and create it after approval from the relevant authorities
Acceptance Criteria:
•	A form to enter the details of the vaccination drive [date, number of vaccines available]
•	On submit the details to be updated in the upcoming vaccination drives.

User story 2.2: 
As a school coordinator, I should be able to view the details of the upcoming vaccination drive and modify it
Description: The school coordinator should be able to view/edit the details of the vaccination drive
Acceptance Criteria: 
•	The school coordinator should view the details of vaccination drive. 
•	Option to edit the dates of the drive, number of slots/vaccines to be available.
•	The edit option to be disabled for completed vaccination drives

Assumptions for EPIC 2: [User Stories 2.1, 2.2, 2.3]
•	The vaccination drive and its relevant details are created and available in a JSON format.
•	Any other assumptions made can be listed in the documentation



