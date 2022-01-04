# Software Requirement Specification

### Milestone 1
**User Stories**
1. Make an ER diagram  
As a backend developer, I want to have an ER diagram so I know what the database will look like.  
Acceptance criteria:  
The ER diagram should show all the entities. 

1. Create a GUI prototype  
As a team member, I want to have a GUI prototype to better understand what to make and to better help development.  
Acceptance criteria:  
The prototype should show all the pages of the application.  

1. Create the initial documentation  
As a team member, I want the documentation to be categorized and well organized so that I can easily and efficiently find what I need to do or work on.  
Acceptance criteria:  
The documentation should cover the technical details of the application.  

### Milestone 2
**User Stories**
1. Initial commit for front- and back-end  
As a developer, I want to have a template for the front and back end done so I can easily find where and what to work on.  
Acceptance criteria:  
The basic structure of the back- and front-end are complete.  

1. Create the schemas for the database.  
As a developer, I want to have a defined schema for the server so I know what goes where.  
Acceptance criteria:  
The schema for all the endpoints should be implemented.  

1. Create API endpoints.  
As a developer, I want to have API endpoints so that information can be sent and received.  
Acceptance criteria:  
All routes should be tested by our CI.  
The front end should be able to access the routes.  

1. Create CI tests for the server  
As a developer, I want to have CI tests so that I know that the server is working correctly.  
Acceptance criteria:  
There should be at least one CI test for each endpoint of the server.  

1. Implement initial GUI  
As a developer, I want to have a GUI implemented so that I can better understand the scope of the system.  
Acceptance criteria:  
The GUI should represent the prototype.  

1. Implement authentication capabilities  
As a user, I want to safely and securely authenticate and register.   
Acceptance criteria:  
Authentication uses Json Web Tokens to authenticate users.  
The passwords should be encrypted.  

### Milestone 3
**User Stories**
1. Convert MQTT to HTTP interpreter  
As a developer, I want a way to easily and accurately convert MQTT information into HTTP requests.  
Acceptance criteria:  
The interpreter can handle converting any valid MQTT information into HTTP requests.  

1. Convert HTTP to MQTT interpreter  
As a developer, I want a way to easily and accurately convert HTTP requests into MQTT information.  
Acceptance criteria:  
The interpreter can mutate any of the supported HTTP methods.  

1. Connect server and interpreter  
As a developer, I want to be able to send information from the interpreter to the server for testing purposes.  
Acceptance criteria:  
Access all the endpoints through the interpreter.  

1. Connect GUI and interpreter  
As a user, I want to be able to send and receive information through the application.  
Acceptance criteria:  
Receive all the information necessary through the interpreter.  

1. Have register/login page  
As an end-user, I want to have an easy way to log in and register so that I can use the website.  
Acceptance criteria:  
The user is able to create an account and log in to the system to use.  

1. Implement calendar and time selectors for appointments  
As an end-user, I want to book and select appropriate times so that I can get a dentist appointment.  
Acceptance criteria:  
The user is able to find the available time slots of each dentist and schedule their appointments.  

1. Finalize the GUI for google map  
As an end-user, I want to be able to interact with the map and view all dentist locations.  
Acceptance criteria:  
The map page can precisely display all dentist locations within the database as waypoints. Users are able to zoom in/out and shift focus between each waypoint upon choosing the corresponding dentist in the list.  

1. Create Use Case Diagram  
As a product owner, I want to have a Use Case Diagram so that I can understand the system better by learning more about the user’s interaction with it.  
Acceptance criteria:  
Accurately portrays all identified actors, their relations, and the use cases for the scenario.  

1. Create Sequence Diagram  
As a product owner, I want to have a Sequence Diagram so that I can see the interaction between the components for a particular scenario.
Acceptance criteria:  
Can portray all appropriate events sequences and the corresponding communication between components.   

1. Write general guidelines on how to set up the different components  
As a developer, I want to have guidelines on how to set up each component so that I can use them.  
Acceptance criteria:  
Thorough and comprehensive guidelines are in place and references are shown.  

### Milestone 4
**User Stories**

1. Frontend backend integration  
As a user, I want to be able to use the service through the front end.  
Acceptance criteria:  
All the features are working through the client.  

1. Circuit breaker (queue system)  
As the maintainer of the website, I don’t want the MQTT system to be overloaded by an excessive amount of requests.  
Acceptance criteria:  
After the amount of requests exceeds 10 requests per second, the system will stop all incoming requests for a set period and give the user and web maintainer an appropriate prompt.  

1. QoS (Quality of Service)  
As a user, I want to be sure that my requests arrive.  
Acceptance criteria:  
All the messages are sent with QoS 1.  

1. Map  
As a user, I want to be able to get directions to the clinic of my choosing.  
Acceptance criteria:  
After the user enters their address, the map should be able to identify their location as a starting point and provide direction to any of the provided clinics.  

1. Documentation  
As a developer, I want to know how the system functions.  
Acceptance criteria:  
All the documentation is done.  

1. Bug test  
As a user, I want to use a stable system  
Acceptance criteria:  
There are no major bugs in the system.  

1. Make video  
As a product owner, I want to be able to review the final stage of the website.  
Acceptance criteria:  
The video fulfills all the requirements and constraints set by the Product Owner
