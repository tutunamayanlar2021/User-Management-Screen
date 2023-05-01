
# User Management Screen - User Interface Specification Document

## Introduction
This document provides a detailed specification of the user interface components, their behavior and requirements for the User Management Screen. The User Management Screen is used to manage user accounts within the system.

## User Interface Components
The User Management Screen consists of the following components:

### User Table
The Users table displays a four-column list of users: ID, Username, Email, and Active. At the top of the table is a button to add a new user. A little to the right of the Add button, there is a checkbox that we tick when we want to hide inactive users.

Table example is as follows:

| ID | UserName  |    Email       |  Enabled  |
| --|:----------:| --------------:|-----------:
| 1 | Kader      | kader@gmail.com|  true     |
| 2 | Deniz      | deniz@gmail.com|  false    |
| 3 | Ali        | ali@gmail.com  | true      |

### New User Creation Panel
The new user panel includes a form to create a new user with the following fields:
- Header: the "New User" header placed towards the left.
- Username: a text field for the user name.
- Display Name: a text field for the display name.
- Phone: a text field for the phone number.
- Email: a text field for the email address.
- User Roles: a dropdown field with three options: Guest, Admin, and SuperAdmin.
- Enabled: a checkbox to enable or disable the user.
- "Save User" button to submit the form and create a new user at the top right of the panel.

### Initial View
When the user first loads the page, the Users table will be displayed. The table will show all of the existing users with their information and enabled status. The New User Panel will be hidden.

### Behavior
- Clicking the "Add New User" button, New User Panel will appear on the right side of the Users Table page.
- When the "Save User" button is clicked, the form will be submitted, and a new user will be added to the Users Table.
- When a user's Enabled checkbox is checked or unchecked, the Enabled status of that user will be updated in the Users Table.
- If there are no users in the table, a message will be displayed saying "No users found".

### Conclusion
This user management interface allows the user to view and manage existing users, as well as add new users to the system. The interface is intuitive and user-friendly, making it easy for users to manage the user list with ease.

