# introsde-2016-assignment-3-client
Introduction to Service Design and Engineering, University of Trento, Trento, Italy - Assignment 03: SOAP Web Services

### General info of the assignment
In this assignment, I worked alone.   
The server for my assignment is running @ [https://enigmatic-chamber-18596.herokuapp.com/ws/people?wsdl](https://enigmatic-chamber-18596.herokuapp.com/ws/people?wsdl)  
The server repository is @ https://github.com/ChukwudiUzoma/introsde-2016-assignment-3-server
### How to run the program?
To run the program use ant build-tool. To execute the program, please open terminal and run the following command in the root directory of the program:

	ant execute.client

The command installs all dependencies and executes the client. The client sends requests to the remote server running on Heroku and prints the results to the terminal and also saves them to a log file in the root folder.	
