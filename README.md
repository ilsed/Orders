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
As a customer I can reorder a previous order.

Make sure you can reorder an order with an id.

## Story 5
As an admin I can get a list of all orders of all customers.

For every order we need the following information:
* Order id
* Customer Lastname
* Customer Firstname
* Order total price
* Order creation date

## Story 6
As a customer I can ask my previous orders.

Look for the previous orders by customer id.

All information is shown in the orders.

## Story 7
As an administrator I can update the price of an individual item.

Make sure you can reorder an order with an id.

## Story 8
As an administrator user I can view all customers.

List all customers.

## Story 9
As an administrator I can view all orders of a customer.

List for all the previous orders by customer id.
Also give the price for each order that they placed.

## Story 10
As a customer I can view the number of items in stock.

Keep track of the number of items in stock.

## Story 11
As a customer I can see the shipping date of an order.

The shipping date is calculated automatically when placing an order. When all the items are on stock, the shipping date is tomorrow, otherwise the shipping date is next week.

## Story 12
As an administrator I can view all orders that should be shipped today.

List all items you should ship today, also give the address where they should be shipped to.

## Story 13
As an administrator I want to have a stock status per item.

The statusses are:
* Low
* Medium
* High

The stock status per item is determined by the percentage of items ordered in the previous week. You should have at least 3 categories:

## Story 14
As an administrator I can view all items that are low in stock.

List all orders that have status Low in stock.

# Non-functional requirements
## Security
Implement security. The customers login using their emailaddress and password. The administrator have a username and password (these can be hardcoded in the application).

## Database
The data of the application should be preserved after rebooting the application.
