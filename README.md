# ConsoleTimeLogger

# Given Requirements:
- [ ] When the application starts, it should create a sqlite database, if one isn’t present.
- [ ] It should also create a table in the database, where the hours will be logged.
- [ ] You need to be able to insert, delete, update and view your logged hours. 
- [ ] You should handle all possible errors so that the application never crashes 
- [ ] The application should only be terminated when the user inserts 0. 
- [ ] You can only interact with the database using raw SQL. You can’t use mappers such as Entity Framework
- [ ] Reporting Capabilities
- [ ] 
# Features

* SQLite database connection

	- The program uses a SQLite db connection to store and read information. 
	- If no database exists, or the correct table does not exist they will be created on program start.

* A console based UI where users can navigate by key presses

* CRUD DB functions

	- From the main menu users can Create, Read, Update or Delete entries for whichever date they want, entered in mm-DD-yyyy format. Duplicate days will not be inputted. 
	- Time and Dates inputted are checked to make sure they are in the correct and realistic format. 

* Basic Reports of Cumulative hours

* Reporting and other data output uses ConsoleTableExt library to output in a more pleasant way
