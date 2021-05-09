# User Interface Specification Document
## Main Page
Main page will have the users table where each row displays a user's features. Each user will be displayed with the _'ID', 'User Name', 'Email' and 'Enabled'_ information. At the top of the users table one button to add new user and one click box to hide disabled users will be placed. When click box is selected users which are disabled will be removed from the table and when it's unselected disabled users must be displayed in the table. When the new user button is clicked user will be directed to another page to fill out new user form. 
## Form Page
Form will ask user to input followings:
- Username 
- Display name 
- Phone
- Email 
- User roles 
- Enabled attribute

Username, display name, phone and email feautres will be text input type whereas enabled is checkbox and user roles are list input. List of user roles will be _'Guest', 'Admin', 'SuperAdmin'._ Filled data must be checked for the each input text box. Depending on the attribute each box must have differenet constraints. When user clicks on the save user button which is placed on top of the new user form. Constraints of the input boxes' will be checked. If user can pass the constraints, new user will be saved and user will be redirected to the previous page. If not, unsatisfied constraints will be displayed to user to refill.
