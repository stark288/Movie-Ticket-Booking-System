# Movie-Ticket-Booking-System
Console project in Core Java technology for front-end and MySQL server as local back-end database.

## Features

[Note- 1]The perticular movie has a specific `movie ID` that is unique to every movie and it will not assign to any other movie even if the movie gets deleted.<br>
[Note- 2]Every Customer is given a specific `Unique ID` when he books a ticket, and it will not assign to any other customer even if the ticket gets deleted.

### There are two panals
1. Customer Panal 
2. Owner Panal

![Panals](Images/6.png?raw=true "Title")

### 1. Customer Panal-

In the Customer Panal, there is a list of operations a customer can perform-
1. Book Ticket
2. Show my Ticket
3. Cancle Ticket
4. Check Seat
5. Show Movie List
6. Back
0. Exit


![Customer Panals](Images/7.png?raw=true "Title")


**`Book Ticket`-** Once one click on this menu the list of all movie available will be shown as table. The customer will enter the desired movie ID.Then The customer will enter his Personal and Required Information (name, phoneNo., no. of seats to be booked). After this ticket will be booked and it will be shown in the console window.

**`Show my Ticket`-** This feature will get easy if a person has his `Unique ID`, but if the person doesn't have his id then he has to fill his details to get his ticket.

**`Cancle Ticket`-**  A person can cancle the ticket only if he has his `Unique ID`. After entering the unique id, the ticket will be display and the customer will asked for confirmation to cancle the ticket or not.

**`Check Seat`-**  Check seat option has the featture to View seats available in the theatre.

**`Show Movie List`-** This Feature simply list up all the details of the movies available.


### 2. Owner Panal-

