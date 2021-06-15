# Personal-Repository-Grootan
## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Browser Compatibility](#browser-compatibility)
* [Setup](#setup)


## General info
This project is to display details of "USERS" from API. 
* Initially, login using a dummy login username and password.
* On clicking the "LOGIN" button it is redirected to the next page where the list of USERS is displayed.
* The users list is retrived from the used API through the created beeceptor link.
* Only the name is displayed initially and on clicking any particular name more info about the user is displayed with options to display the previous and next records using the "Previous" and "Next" buttons.

## Technologies
Technologies used:
* HTML
* CSS
* Bootstrap 5.0.1
* JQuery 3.5.1

## Browser Compatibility
* Chrome
* Firefox
* Safari
* Microsoft Edge
* Opera 

## Setup
### Pre-requisites for dataset:
Consider the sample dataset:
{
"name":"Varsha",
"age":"20",
"dob":"18-02-2001",
"firstName":"Dhanvarsha",
"lastName":"Sugumar",
"more":{
"address_line1":"abc",
"address_line2":"def",
"address_line3":"ghi",
"phone":"123"
}
}
In the dataset mentioned above, "name" key is the unique identifer that has been considered, so this should always be unique

### Beeceptor link used :
https://anusruti.free.beeceptor.com

### Deployment:
To run this project,
* Open "index.html" and give any dummy username and password and click on "LOGIN" button.
* It redirects to the USER list and the names , which is a unique id of the users, are displayed using bootstrap cards.
* To view detailed information about the user click on the corresponding unique name for each user and detailed information of the user is displayed as a modal dialog.
* In the modal dialog displayed, click on the Next and Previous button to navigate between the users list.
* You can close the modal dialog by clicking on the close icon in the dialog.
