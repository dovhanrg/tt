# Scale Junior Frontend Developer Assessment

Thank you for your interest in interviewing for Scale. This assessment will
test your ability to create a web application based on a set of requirements.


## Overview

In this exercise you will create a React web application which will contain the
pages described below.

You will use the sample REST API located at https://reqres.in/ to provide the data for the application.

## Deliverables

* Zip or TAR your project directory and include a README file with instructions on how to run the application.
* Be sure to omit the node_modules directory to keep the file size down.
* For extra points, include a Dockerfile to ease the execution of your application.
* Email the zip or tar archive to your recruiter

### Login Page

The application should require that a user is logged in.

If they have not already logged in, a login page should be displayed.

The login page will include a form with "username" and "password" inputs and authenticate against the https://reqres.in/api/login
endpoint to retrieve a token.

(Note: you will need to use one of the emails from a user at https://reqres.in/api/users and any string as a password)

### List Users Page

This page should retrieve users from the https://reqres.in/api/users endpoint and display them in a table.

The table should include the following columns:

* id
* first_name
* last_name
* email
* actions

Each row should include an "Edit" action

### Edit User Page

This page should be displayed when the user clicks on the "Edit" button above. This page
should display a form to allow us to edit a user's first_name, last_name, and email.

The page should include a "Save" button which issues a PUT request to the user's endpoint.

### Styling

The application should be created with Material-UI components (https://material-ui.com/) and use the default theme.

Alternatively you may use Bootstrap or Bulma.io to lay out and style the application.
