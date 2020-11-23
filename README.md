Roster application based on Optaplanner JavaFx and Hibernate Currently configured to support 14 day shift rosters where the staff member must complete x number of shifts per fortnight. For example 10 shift per fortnight no more or less. Supports multiple contract types eg 9 shift per fortnight, 8 shifts per fortnight etc. Takes in account casuals and assigns based on requirement. Takes into account requests such and Days On/Off Shifts On/Off ,Leave, Training Days, Rostered Days Off and Long term leave. Provides the ability to conduct continuous planning in 14 day blocks. Exports to an excel file. Provide a calendar view.

Currently the print function from Calendar view is not completed. There is also some tidy up work required although all it functioning. A MySqlFile is provide for ease of loading the database before opening the application.

Disclaimer being you use this application at your own risk.
For non java pers your can run the application by following the below steps.

Install mysql (you can use something like Wampserver for windows)
Create a database call newroster
username - myrosterapp
password - myroster
Import the provided newroster.sql to get you started
Once this is done you can run the RosterUpdate.jar file

Note this has been developed using Java 11 so you will need to ensure you have Java 11 or higher SDK installed