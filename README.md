

PeopleFlow (www.pplflw.com) is a global HR platform enabling companies to hire & onboard their employees internationally, at the push of a button. It is our mission to create opportunities for anyone to work from anywhere. As work is becoming even more global and remote, there has never been a bigger chance to build a truly global HR-tech company.


As a part of our backend engineering team, you will be responsible for building our core platform including managing employees, This employees are assigned to different states, initially when an employee is being added it will be assigned "ADDED" state.


The other states (State machine) of A given amployee are:
- ADDED
- IN-CHECK
- APPROVED
- ACTIVE


Our backend stack is using:
- Java 11 
- Spring Framework 
- Kafka

Your task is to building an Restful API doing the following 
- An Endpoint support adding an employee with very basic employee details including (name, contract information, age, etc.) With initial state "ADDED" Which incidates that the employee isn't active yet.

- An Endpoint to change the state  of a given employee to "In-CHECK" or any of the states in the state machine 


Please provide a solution with the following features with the following consideration.

- Being simply executable with the least effort Ideally using Docker and docker-compose
- For state machine could be as simple as of using ENUM or https://projects.spring.io/spring-statemachine/ 
- Please provide testing for your solution.
- Providing the API Contract e.g. OPENAPI spec. is a big plus


Please provide the solution to "Islam.abdelaziz@pplflw.com"






