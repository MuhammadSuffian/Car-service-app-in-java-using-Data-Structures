HOW to USE it:

To use as an Customer:

1.Create Account

2.Login using gmail and password used to create account 

3.Book appointement(it will also give to a Appointenet ID/tokken ID)

4.Check history

5.Log out

To use as an Admin:
1.Enter username Admin and Password Admin
2.It will open admin Page
3.Search by tokken given to customer
4.Manage Appointements

Note:Passwords are stored in Custom hashes

The Car Service App is a Java-based application designed to facilitate the booking and management of car service appointments for customers, with additional administrative features. The app employs data structures such as queues, stacks, and file handling to efficiently handle various operations.

The app supports two types of users: customers and administrators. Customers can create an account, log in, and view their service history. Administrators have additional privileges, including managing appointments and searching by tokens.

To implement the appointment management system, a queue data structure can be used. The queue stores upcoming appointments in a first-in, first-out (FIFO) manner. This ensures that appointments are processed in the order they were made. Each appointment in the queue would contain relevant information such as the customer's name, appointment time, and car details.

For the storage of service history, a stack data structure can be employed. Each customer would have their own stack to store their service history. The stack allows for efficient retrieval of the most recent service records, following the last-in, first-out (LIFO) principle. Each entry in the stack represents a service appointment and contains details like the date, type of service, and any additional notes.

To ensure the permanent storage of customer service history, file handling can be utilized. When a customer logs into their account or completes a service appointment, the relevant information can be written to a file. 
