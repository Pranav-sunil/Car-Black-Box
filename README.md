# Car-Black-Box
A black box records all the activities occurring in a a vehicle. The program will store changes in gear and collisions. The menu is password protected and allows the user to view the saved logs, download and view on the monitor, clear the saved logs, edit the time and also the password.

Target Micro-Controller: PIC 18F4580  
Board:  rhydoLABZ PIC 18F4580 CAN Developement Board( https://www.rhydolabz.com/pic18f4580-can-development-board-rhydolabz )  
Compiler: XC8  
Application used to develop program: MPLAB X IDE (v6.20 )  

Features of the application:  
1. Store events such as change in gear, occurance of collsion, speed and time of occurance( max. 10 events ).  
2. Password protected menu system:  
    2.1 View the saved events on the CLCD avaliable on the board.  
    2.2 Download and view saved data from External EEPROM on the board to a Laptop/PC using Teraterm application.  
    2.3 Clear the saved logs in the system.  
    2.4 Change the time in the RTC.  
    2.5 Change the password.  
