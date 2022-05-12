# Bank

## Description

   The Bank app is a console-based application that simulates banking operations. A customer can apply for an account, view their balance, and make withdrawals and deposits. An employee can approve or deny accounts and view account balances for their customers.
	
## Purpose

   We want to see that you can meet deadlines and that you can code. You are expected to complete the following requirements and give a 5 minute presentation of your project.

## Requirements
1. Functionality should reflect the below user stories.
2. Data is stored in a database.
3. Data Access is performed through the use of JDBC in a data layer consisting of Data Access Objects.
4. All input is received using the java.util.Scanner class.
5. The project must be a Maven project.


## User Stories
Total Points: 26 points (the points correspond to the difficulty of the task)

* As a user, I can register for a customer account (checking or savings or both!).
	* 3 points
* (Stretch goal) As a user, I can apply for a joint account 
	* 3 points
* As a user, I can login.
	* 2 points
* As a customer, I can apply for a new bank account with a starting balance.
	* 3 points
* As a customer, I can view the balance of a specific account (that belongs to me).
	* 1 point
* As a customer, I can make a withdrawal or deposit to a specific account (that belongs to me).
	* 2 points
* As the system, I reject invalid transactions.
	* Ex:
		* A withdrawal that would result in a negative balance.
		* A deposit or withdrawal of negative money.
	* 2 points
* As an employee, I can approve or reject an account registration by a user.
	* 2 points
* As an employee, I can view a customer's bank accounts.
	* 1 point
* As a customer, I can post a money transfer to another account.
	* 3 points
* As a customer, I can accept a money transfer from another account.
	* 2 points
* An employee, I can view a log of all transactions.
	* 2 points

	
NOTE: The user stories are an informal, easy to follow description of a feature needed for an application. It will not encompass all the details a task will require, for example when a user signs up for an account, they should provide a username and password, or if a user can login, then they should be able to log out! Keep this in mind when completing user stories. 

NOTE: Additional functionalities, such as email notifications, logging, and unit testing can be implemented, but the priority is the user stories. It's highly recommended to complete those before adding extra features. 

Project Evaluation Parameters
1) Your project will be evaluated based on coverage of technology and the user stories that have been completed.
2) How you have implemented best practices: naming conventions, separation of code into various classes, how well have you applied OOP and design patterns.
3) How well you present your project: concise and professional commuincation, logical flow and ability to handle the Q&A section.