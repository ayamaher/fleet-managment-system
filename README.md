# fleet-managment-system
Bus Booking System

Task Introduction The goal of this project is to implement a building a fleet-management system (bus-booking system) using the latest version of the Laravel Framework. 
Task Deliverables Please make sure to deliver the following
1. A public github repository containing your code. Make sure proper .gitignore is in place. Commit messages will be checked.
2. Database dump with proper data to be tested. 
3. Proper README.md file explaining how to a. Access the administration area b. Any special configs needed to run the application.  
4. ** Bonus: Use docker or vagrant so that the app runs with one command via the terminal.  Expected Stuff We expect you to do proper validation where applicable in any user input. Database structure and authentication techniques are also core part of this task.   Task Description will follow in the next page.    
Task Description Robusta studio wants to build a fleet-management system (bus-booking system) Having: 
1- Egypt cities as stations [Cairo, Giza, AlFayyum, AlMinya, Asyut...] 
2- Predefined trips between 2 stations that cross over in-between stations. ex: Cairo to Asyut trip that crosses over AlFayyum -firstly- then AlMinya. 
3- Bus for each trip, each bus has 12 available seats to be booked by users, each seat has an unique id.
4- Users can book an available trip seat.
For example we have Cairo-Asyut trip that crosses over AlFayyum -firstly- then AlMinya: any user can book a seat for any of these criteria (Cairo to AlFayyum), (Cairo to AlMinya), (Cairo to Asyut), (AlFayyum to AlMinya), (AlFayyum to Asyut) or  (AlMinya to Asyut)  if there is an available seat, taking into consideration if the bus is full from Cairo to AlMinya, the user cannot book any seat from AlFayyum but he can book from AlMinya.  We require the following: Implement a solution for this case using a Relational-Database and Laravel web app that provides 2 APIs for any consumer(ex: web app, mobile app,...)
● User can book a seat if there is an available seat.
● User can get a list of available seats to be booked for his trip by sending start and end stations. 
** Bonus: Implement proper unit tests are available. Development Stack:
● Latest version of laravel framework.
● Relational-Database 
