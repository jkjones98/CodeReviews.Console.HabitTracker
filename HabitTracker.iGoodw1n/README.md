# ConsoleCodeTracker
This is a C# console CRUD application to track amount of lines of code user has written on concrete programming language.

Developed using C# and SQLite.


# Given Requirements:
- [x] When the application starts, it should create a sqlite database, if one isn’t present.
- [x] It should also create a table in the database, where the hours will be logged.
- [x] You need to be able to insert, delete, update and view your logged hours. 
- [x] You should handle all possible errors so that the application never crashes 
- [x] The application should only be terminated when the user inserts 0. 
- [x] You can only interact with the database using raw SQL. You can’t use mappers such as Entity Framework
- [x] Reporting Capabilities

# Features

* SQLite database connection

	- The program uses a SQLite db connection to store and read information. 
	- If no database exists, or the correct table does not exist they will be created on program start.

* A console based UI where users can navigate by key presses
	- See all records
	- Add new record
	- Update existing record
	- Delete existing record
	- See annual report

* CRUD DB functions

	- From the main menu users can Create, Read, Update or Delete entries for whichever date they want, entered in dd-MM-yy format.
	- Data inputted are checked to make sure they are in the correct and realistic format. 

* Basic Reports of Cumulative code lines
	User can get annual report for total code lines written for respective programming language