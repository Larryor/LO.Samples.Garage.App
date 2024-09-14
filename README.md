#Task
A customer wants a software to manage his car rental business.
He has a customer base and a list of cars that customers can rent


#Requirements
The software must be able to:
- Manage customers (CRUD)
- Manage cars (CRUD)
- View and edit the current rental state of the cars
- Provide information on
o what customer is renting which car right now,
o how many cars are rented right now,
o and how many kilometres in total a car was rented in the past.

#User stories
- As a user i want to be able to
   - navigate to see all the cars i have and their state (Available, Rented, In Repair) along side how many total KM they have been rented for in the past
   - be able to switch a car to/from all the states
   - be able to add a new car
   - be able to delete a car (only allowed in the state "Available" and "In Repair"
 
- As a user i want to be able to
   - navigate to see all my customers
   - see how many cars a customer is renting
   - add a new customer
   - remove a current customer (only allowed if the customer is not currently renting a car)
