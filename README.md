# Expense-Reimbursement-System

## Project Description
The Expense Reimbursement System (ERS) will manage the process of reimbursing employees for expenses incurred while on company time.
All employees in the company can login and submit requests for reimbursement and view their past tickets and pending requests.
Finance managers can log in and view all reimbursement requests and past history for all employees in the company.
Finance managers are authorized to approve and deny requests for expense reimbursement.

## Technologies Used
- Back-end technologies: Java, PostgresSQL, Maven, Log4j, Mockito, Servlets, AWS RDS, Tomcat
- Front-end technologies: HTML, CSS, JavaScript

## Features
### Employee
- An Employee can login
- An Employee can view the Employee Homepage
- An Employee can logout
- An Employee can submit a reimbursement request
- An Employee can view their pending reimbursement requests
- An Employee can view their resolved reimbursement requests
- An Employee can view their information

###
- Manager User Stories
- A Manager can login
- A Manager can view the Manager Homepage
- A Manager can logout
- A Manager can approve/deny pending reimbursement requests
- A Manager can view all pending requests from all employees
- A Manager can view all resolved requests from all employees and see which manager resolved it
- A Manager can view all Employees
- A Manager can view reimbursement requests from a single Employee

### To-do list:
- Debug Manager User Stories: A Manager can view reimbursement requests from a single Employee
- Allow Employee to update their information
- Restructure the design of the webpage
- Implement Password Hasing
- Load application on AWS EC2
- Have one centralized webpage for both Employee and Manager

## Usage
1. Load Project on Tomcat 8.5 server
2. Insert localhost:8080/ERS/ onto your web browser
3. Click on login at the top of the page
4. Login as a Employee with username/password: Megaman/megax or login as a Manager with username/password: manager1/manager1pw
5. Explore options between Employee webpage and Manager's webpage 

### License
This project uses the following license: MIT License

Copyright (c) [2021] [Steven Nguyen]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
