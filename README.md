# RESTfulWebService

To run this project in your Eclipse IDE, take the following steps:

Import the project: 
Step 1 :- 
File -> Import -> Maven -> Existing Maven Projects -> 
In the 'Root directory' option, use 'Browse' option to select the project you want to import. 
Select your project under option 'Projects:' if not selected. Select option: 'Add Project to working set'.
Click Next
Your project would start adding to your workspace.
It may take a while.

Step 2 :-
Open pom.xml
Save the file.
Dependencies will start downloading. After all the dependencies have been downloaded.

Step 3 :-
Open application.properties file.
Configure it as per your requirements i.e. giving values to the following properties:

spring.datasource.url=

spring.datasource.username=

spring.datasource.password=

spring.jpa.properties.hibernate.dialect= 

Use 'spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQLDialect' for MYSQL version lower than 5.7.

Step 5 :-
Open Application.java file and run it as Java Application
The console will start showing various logs. 
When 'Application started' log appears in the console, then open your browser (preferably Google Chrome).
Type this url:
http://localhost:8080/demo/add?firstName=Ankit&lastName=Kumar&productPurchased=Java Development 
and then type this url:
http://localhost:8080/demo/all

You will see that the values of firstName,lastName and productPurchased that you have entered in the first URL will
be reflected back in JSON forrmat. You can add more values using the 'add' uri in the first URL by changing values of 
properties.
