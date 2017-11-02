# Orders
No security needed, if you really want to implement it take a look on Spring security.

## Story 1
As an unregistered user I can create a customer account.

Create a customer with:
* Firstname
* Lastname
* Email address
* Address
* Phonenumber

## Story 2
As a customer I can Order an item.

An item group has an amount and a shipping date. This should be calculated automatically. When we have the items in stock this should be tomorrow otherwise this should be next week.

The price should also be calculated and shown to the customer when ordering.

## Story 3
As a customer I can ask my previous orders.

Look for the previous order by customer id.

## Story 4
As a customer I can reorder a previous order.

Make sure you can reorder an order with an id.

## Story 5
As an admin user I can add an item.

Create an item with:
* Name
* Description
* Price

## Story 6
As an admin user I can view all customers.

List all customers.

## Story 7
As an admin user I can view all orders of a customer

List for all the previous orders by customer id.
Also give the price for each order that they placed.

## Story 8
As an admin user I can view all orders that should be shipped today.

List all items you should ship today, also give the address where they should be shipped to. Per item group on one order you can have a different shipping date, but all items are shipped to the same address.

## Story 9
As an admin user I want to have a calculated max stock of an item.

Calculate the max stock of an item, this is determined by the percentage of items ordered in the previous week. You should have at least 3 categories:
* Low
* Medium
* High

When no items were ordered the previous week, then don’t change the priority. 

## Story 10
As an admin user I can view all items that I should reorder.

List all orders that are low in stock. Low is determined by lower than 20% of the current max stock. 
