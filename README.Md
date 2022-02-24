PLANNING

DAY 0 (2/23/22):

1. Research:

Program Administration Scale (PAS), Measuring Early Childhood Leadership and Management by Teri N. Talan and Paula Jorde Bloom; and

Caring for Our Children, National Health and Safety Performance Standards,  Guidelines for Early Care and Education Programs, by American Academy of Pediatrics, et al.  Fourth edition contains guidelines on the development and evaluation of the health and safety of children in early care and education settings. This guide features 10 chapters of more than 650 standards and dozens of appendixes with valuable supplemental information, forms, and tools.         Key Features

More than 100 updated standards and appendixes
Updated appendixes, including Signs and Symptoms Chart, Recommended Immunization Schedule, and Recommendations for Preventive Pediatric Health Care
Completely revised and updated topics on environmental health, infectious diseases, and nutrition

	Topics Include

Staffing
Program activities for healthy development
Health promotion and protection
Nutrition and food service
Facilities, supplies, equipment, and environmental health
Play areas and playgrounds, and transportation
Infectious diseases
Children with special health care needs and disabilities
Administration
Licensing and community action
And more …

2. App Name: GigglesTool
3. App Description: A childcare assessment tool 

GigglesTool is an app designed and developed for out-of-home childcare facilities (including center, Early Headstart, Head Start, Large Family Child Care Home, Small Family Child Care Home) to measure the quality of leadership and management practices regarding health and safety based upon the following National Health and Safety Performance Standards:
2.2.0.1: Methods of Supervision of Children;
5.1.4.4: Locks; and
9.2.3.9: Written Policy on Use of Medications. 
By using this app, the Early Childcare Education community will have a better understanding of how facilities can improve their health and safety practices to better protect children from harm.


4. Complete User Stories
5. Complete ERD
6. Two Repo Links:
	https://github.com/annettem123/GigglesTool-FEND
	https://github.com/annettem123/GigglesTool-BEND
7.  Project Description:
This project is built on a monolithic back-end using Spring Boot and its modules.  I used PostreSQL to create my database and Tomcat to run my application.
8. Technical Info:
Persist 2 models (standards, activities) to a PostgreSQL database.
Use Spring Profiles for environment settings.
At least one API endpoint will perform full CRUD create, read, update, and delete actions
Other API endpoints can perform CRUD based on the business use-case (service).
Expose CRUD routes that were built using REST conventions.
Handle exceptions gracefully.
Send appropriate messages back to the client in the event that an exception occurs.
Have Controller and Service separate.
Document each end-point, such that

Stick with KISS (keep it simple, stupid) and DRY (don’t repeat yourself) principles.
