# Team-Profile-Generator
Homework10

# Project Description
The Team Profile Generator is a command-line-input application run in Node that requests information from the user about members of an engineering team and generates an HTML file displaying that information.  Before running the application the user must perform an npm install to install all required dependencies.

Upon launching the app, the user is asked to describe the first member of their team.  The user enters the team member's name, selects that member's role from a list (options include "Engineer," "Intern," and "Manager), enters the member's ID (any string), enters the member's email address, and then must enter another piece of information that will differ depending on what role was selected.  If "Engineer" was selected, the app asks the user for the team member's GitHub username; if "Intern" was selected, the member's school is requested; and if "Manager" was chosen, the user is prompted for the team member's phone number.

A screenshot showing an example user input is shown below:

![Screenshot of user input](https://github.com/Eimer87/Homework10/issues/2#issue-783630698)

When all information on the team member has been entered, the user is asked whether there are any more members they would like to add.  If so, the user is asked the same questions about the new team member.  If not, an HTML file is created with cards displaying the information on all the team members entered by the user in the "outputs" folder titled "team.html."  A screenshot of an example team profile is shown below:

![Screenshot of HTML output](https://github.com/Eimer87/Homework10/issues/1#issue-783630416)

# Set up
After installing dependencies use node app.js on the terminal screen.
