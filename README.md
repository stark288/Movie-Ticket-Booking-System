# Movie-Ticket-Booking-System
Console project in Core Java technology for front-end and MySQL server as local back-end database.

## Features

[Note- 1]The perticular movie has a specific `movie ID` that is unique to every movie and it will not assign to any other movie even if the movie gets deleted.<br>
[Note- 2]Every Customer is given a specific `Unique ID` when he books a ticket, and it will not assign to any other customer even if the ticket gets deleted.

### There are two panals
1. Customer Panal 
2. Owner Panal

![Panals](Images/6.png?raw=true "Panals")

### 1. Customer Panal-

In the Customer Panal, there is a list of operations a customer can perform-
1. Book Ticket
2. Show my Ticket
3. Cancle Ticket
4. Check Seat
5. Show Movie List
6. Back
0. Exit


![Customer Panal](Images/7.png?raw=true "Customer Panal")


* **`Book Ticket`-** Once one click on this menu the list of all movie available will be shown as table. The customer will enter the desired movie ID.Then The customer will enter his Personal and Required Information (name, phoneNo., no. of seats to be booked). After this ticket will be booked and it will be shown in the console window.

* **`Show my Ticket`-** This feature will get easy if a person has his `Unique ID`, but if the person doesn't have his id then he has to fill his details to get his ticket.

* **`Cancle Ticket`-**  A person can cancle the ticket only if he has his `Unique ID`. After entering the unique id, the ticket will be display and the customer will asked for confirmation to cancle the ticket or not.

* **`Check Seat`-**  Check seat option has the featture to View seats available in the theatre.

* **`Show Movie List`-** This Feature simply list up all the details of the movies available.


### 2. Owner Panal-

The Owner Panal has a login page so that it can be accessed only by owner

`Username - shubham`<br>
`Password - password`


![Owner Panal login](Images/8.png?raw=true "Owner Panal login")

After successfully login, there is shown a list of operations that the Owner can perform-

1. Add New Movie
2. Delete Movie
3. Show Movie List
4. See Total Bookings
5. Back
0. Exit

![Owner Panal](Images/9.png?raw=true "Owner Panal")

* **`Add New Movie`-** The Owner can add new movie in the theatre with this feature. After selecting this feature the Owner has to add information about movie (name, format(*Hindi 2D/Hindi 3D/English 2D/English 3D*), Date, time, price, seats). After adding movie successfully, it will be given a unique id. 

* **`Delete Movie`-** To delete a movie from the theatre, the Movie id should be known. After entering the movie id, the info of the movie will be display and the Owner will asked for confirmation to delete the movie or not. When a movie gets deleted, all bookings associated with that movie will gets deleted.


* **`Show Movie List`-** As before, This Feature simply list up all the details of the movies available.

* **`See Total Bookings`-** The Owner can see all the bookings with this feature. After selecting this feature, there will be shown two lists, First, the list of all the movies and second the list of all the bookings.

## Database
I have used MySQL database for back-end. The name of this database is ***`MTBS`***
In this database there are two tables 
* Customer
* Movie

![MTBS](Images/1.png?raw=true "MTBS")

### Customer
![Customer](Images/2.png?raw=true "Customer")

### Movie

![Movie](Images/3.png?raw=true "Movie")

### Data in tables

![Movie](Images/4.png?)<hr>![Movie](Images/5.png?)
