# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-outline)

## Submission Instructions

### Overview
A great deal of small nonprofit organizations struggle with the ability to track donations as well as organize and maintain their constituents. Lacking a budget for a proper database or CRM solution, many of these nonprofits opt for solutions as simple as a spreadsheet. 
Simple CRM will allow these nonprofits to gain better control over their donor and transactional data, offering a user-friendly front-end to navigate and maintain their critical data.

This idea was inspired by my own experiences working in the nonprofit fundraising and CRM field. I've been fortunate enough to work for larger, well-established nonprofits, but my time in the industry has exposed me to the needs of much smaller nonprofits that still do great work.
### Features
- User login: all users must log in. Since this is not intended as a publicly accessible application, there is no option to create a new account. New usernames can be created only by an administrator.
- Add new donors: Users will have the ability to add donor contact records to the database. 
- Create new campaigns: Fundraising campaigns can be created, edited and activated by users with proper permissions. 
- Post transactions: Users can post donations from individual donors to the database. Each transaction is linked to an individual donor and campaign. 
### Technologies
- C#/.Net Core
- MySQL
- HTML/Bootstrap
### What I'll Have to Learn
- I plan to have 3 user account levels with varying permissions: admin, manager, and employee. Therefore, I'll need to learn how to establish different permissions for user accounts.
- I would also like to include functionality that allows a user to create a new donor record (if an existing record isn't found) when posting donations. This will require me to learn how to trigger a pop-up window form to create a new donor account. 
After doing so, the pop-up would close and the transaction form will populate the newly created donor ID. 
### Project Tracker
https://trello.com/b/qkdkOsE6/simple-crm-liftoff-project
