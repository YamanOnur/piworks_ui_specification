# Introduction
  1. This is  user interface specification document for user management screen.
  2. To draw user flow diagram, I used lucidchart.com.
# User Flow Diagram
![Flow Diagram](FlowDiagram.png "User Flow Diagram")
# Specifications
  1. When the user firstly logs into the application, he or she will see "+New User" button, "Hide New User" check button and user list.
  2. As soon as "+New User" button is clicked, he will see a form called New User.
  3. In new user form, he needs to fill out the form containing text boxes: Username, Displayname, Phone, Email and select User Roles combo box. There are three options available for user roles: Guest, Admin, Super Admin.
  4. Then he will decide if enabled checkbox is ticked. After filling out whole form "Save User" will be activated.
  5. Finally, when "Save User" button is clicked, the user will be added to the list by incrementing previous id by 1. This list includes limeted information about users: Corresponding Username, Email and Enabled.
  6. Depending on the preferency of hiding disabled user option, newly added user will be displayed or not displayed.
  7. After all, the terminal will be returned. So you can clean the new user form and deactivate save user button in this step.
