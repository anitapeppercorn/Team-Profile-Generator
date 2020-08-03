# Team-Profile-Generator
This project is a Node.js command-line application that takes in information about employees on a software engineering team and generates an HTML webpage that displays summaries for each person. Because testing is key to making code maintainable, we also write unit tests for each part of the code and ensure that it passes all of them. This application uses Jest for running the unit tests and Inquirer for collecting input from the user. The application is invoked by using the following command:node index.js
1. A sample HTML file generated using the application is submitted here.
2. This GitHub repository contains the application code; https://github.com/anitapeppercorn/Team-Profile-Generator
3. Here is a link to a walkthrough video that demonstrates its functionality and all of the tests passing. It takes in information about employees on a software engineering team and generates an HTML webpage that displays summaries for each person.
4. The application has these classes: Employee, Manager, Engineer, and Intern.
[MIT](http://img.shields.io/badge/license-MIT-brightgreen.svg) 
 
 ## Contact 
![Badge](https://img.shields.io/badge/Github-anitapeppercorn-4cbbb9) 
![Profile Image](https://github.com/anitapeppercorn.png?size=50)
View the author's portfolio at:  https://anitapeppercorn.github.io/anitaprofileportfolio/
![GIF of work](/images/runtest.gif)
![GIF of work](/images/promptresponse.gif)
![Screen Image of Page](/images/empire.png)
contact the author at anita@peppercorn.ai.
  

  ### Installation
  Packages required to run this program are: Packages required include: inquirer, fs, jest

  ## Contributors
  Anita Ganti

  ### Usage
  Examples of how to use this program:  Use this project to create a webpage for your team
  
  ### License
  MIT
  
  ### Tests
  To test, run the following command: npm run test
  


## User Story
AS A manager
I WANT to generate a webpage that displays my team's basic info
SO THAT I have quick access to their emails and GitHub profiles

## Acceptance Criteria
GIVEN a command-line application that accepts user input
WHEN I am prompted for my team members and their information
THEN an HTML file is generated that displays a nicely formatted team roster based on user input
WHEN I click on an email address in the HTML
THEN my default email program opens and populates the TO field of the email with the address
WHEN I click on the GitHub username
THEN that GitHub profile opens in a new tab
WHEN I start the application
THEN I am prompted to enter the team manager’s name, employee ID, email address, and office number
WHEN I enter the team manager’s name, employee ID, email address, and office number
THEN I am presented with a menu with the option to add an engineer or an intern or to finish building my team
WHEN I select the engineer option
THEN I am prompted to enter the engineer’s name, ID, email, and GitHub username, and I am taken back to the menu
WHEN I select the intern option
THEN I am prompted to enter the intern’s name, ID, email, and school, and I am taken back to the menu
WHEN I decide to finish building my team
THEN I exit the application, and the HTML is generated
