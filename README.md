# RailwayManagementSystem
It is a Python + MySQL project.
---------
:FOLDERS:
_________

/Assets : Contains the data that is to be inserted in the MySQL tables in csv format
         
         Files: Train_details.csv -> Contains all the data about the trains in the format 
                                     (Train No, Station Code, Station Name, Arrival time, Departure Time, 
                                     Distance, Source Station, Source Station Name, Destination Station, 
                                     Destination Station Name)

/core : Contains all the files that are required by the project to work

        Files: __init__.py -> Makes the folder to be recognized as a module
               Checks.py -> This file contains the functions that verify the requirements of the Project
               InsertData.py -> This file contains the functions to insert the data in the MySQL tables
               User_Functions.py -> This file contains the function that allow a user to perform certain task
               Other.py -> This file contains some commonly used functions

-------------------
:ROOT FOLDER FILES:
___________________

Main.py -> This is the main file that connects all the other modules and is used to run the project

----------
:FEATURES:
__________

Overview: It is a Railway Management system in which a user can book tickets, cancel reservations,
          check fares etc. It uses MySQL as the backend database.

1. Book a Ticket: Users can book a ticket
2. Cancel a Booking: Users can cancel a booked ticket
3. Check Fares: Users can check fares before booking
4. Show my Bookings: User can check their bookings
5. Show Available Trains: Users can see the available trains 
6. Clear Screen: Clears the terminal screen
7. Menu: Shows the menu
8. About: Prints the content of this file to the screen
9. Exit: Exit the program
