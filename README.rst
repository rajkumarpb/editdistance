Technical Documentation: Calculate Edit Distance


APPLICATION OVERVIEW
A single page application that contains a two text field form which when submitted sends two strings to a backend service. The backend service computes the edit distance between two strings (returns the minimum number of operations required to transform one string into another). The computed output is then returned to the end user.


KEY TECHNICAL DETAILS
Frameworks
•	NodeJS: v7.8.0
•	Angular CLI: v1.5.0
•	Angular 5
•	Bootstrap: v3.3.7
•	ExpressJS: 4.16.2

Tools
•	Visual Studio Code: v1.18
•	Git Bash
•	Source Tree


BUSINESS REQUIREMENTS
•	No page reload / Single-page App
•	JSON dependent on both ends
•	Do not use third-party libraries to compute the edit distance
•	Use Git Repository


URLs
•	Back end Server: http://localhost:4500/
•	Frond end: http://localhost:4200/

CLI Commands
•	To start backend server, in project root: >nodemon server or npm start
•	To start front end application, in /client/view/ folder: >ng serve
•	To run unit tests, in /client/view/ folder: >ng test
