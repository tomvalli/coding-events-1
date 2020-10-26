# Coding Events
## Mission Statement:
*Coding Events* was built to provide a tool for listing various local and national coding events.  Whether it is a large conference like Apple's WWDC or a small local JUG, Coding Events has been built to list them all.
* * *
## Where We Are:
At present, Coding Events is capable of accepting new events with *name, descrption,* and *type of event* and then displaying a list of those events. You are able to add informative tags to created events.  This information is stored in a MySQL database.  Coding Events was built using Spring Boot, Thymeleaf, and Hibernate.
* * *
## Where We're Going:
We will soon be adding user profiles so you can register for events and keep track of past events.  
### TODO:
- add a Person class for un/pw authentication
	- Add fields: id, username, password
- add a Profile class
	- Add fields: realName, displayName, email, phoneNumber, location, event_id
- add an AccountRecovery class
	- Add fields: recoveryMethod(ENUM), recoveryEmail, recoverySMS, recoveryAuthApp

- These classes will all have a 1:1 relationship in the database aside from the Person -> Event relationship which will be a 1:Many relationship.
