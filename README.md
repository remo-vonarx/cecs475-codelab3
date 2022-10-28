# cecs475-codelab3

## Local project setup

Apply these steps for the initial setup of the project.

1. Install the according MsSQL Server with the following command in PMC:

`Install-Package Microsoft.EntityFrameworkCore.SqlServer -version 3.1.0`

Adapt the version param accordingly; the latest version is not compatible with the CSULB Student Virtual Lab. However, `3.1.0` works.

2. Apply the initial database migration in PMC: 

`Update-Database`

This creates the database and fills it with initial data.

3. Build the project.

4. Run `MvcMovie`
