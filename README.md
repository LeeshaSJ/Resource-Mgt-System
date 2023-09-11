# Resource-Mgt-System

Note:

In order to make the project work, you have to first download the database file (Assignment2-Database.dacpac).

To import dacpac file into Visual Studio 2022, follow these steps:

-Open the project.
-Open SQL Server Object Explorer (View->SQL Server Object Explorer).
-Expand SQL Server.
-Right click on "Databases" folder and click on Publish Data-tier Application.
-Select the relevant .dacpac file and give the database the name "Assignment2.Data".
-The database and its data will now be shown in the SSOE.
-In order for the application to run properly, the correct data source (found as "connection string" inside the properties window of the database "Assignment2.Data") should be added to line 8 of CS code in the file "db.cs" in "Models" folder.
