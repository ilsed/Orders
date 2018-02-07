# Stories
## Story 1
As an unregistered user I can create a customer account.

Create a customer with:
* Firstname
* Lastname
* Email address
* Password
* Address
* Phonenumber

## Story 2
As an administrator I can create an item.

Create an item with:
* Name
* Description
* Price

## Story 3
As a customer I can Order one or more items.

The price of the Order should be calculated and shown to the customer when ordering.

## Story 4
As an admin I can get a list of all orders of all customers.

For every order we need the following information:
* Order id
* Customer Lastname
* Customer Firstname
* Order total price
* Order creation date

## Story 5
As a customer I can ask my previous orders.

Look for the previous order by customer id.

All information is shown in the orders.

## Story 6
As an administrator I can update the price of an individual item.

Make sure you can reorder an order with an id.

## Story 7
As an admin user I can view all customers.

List all customers.

## Story 8
As an admin user I can view all orders of a customer

List for all the previous orders by customer id.
Also give the price for each order that they placed.

# Non-functional requirements
## Security
Implement security. The customers login using their emailaddress and password. The administrator have a username and password (these can be hardcoded in the application).

## Database
The data of the application should be preserved after rebooting the application.
