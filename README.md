# Shop Manager Project
=================

This is a simple shop management program that allows shop managers to perform basic CRUD (Create, Read, Update, Delete) operations on their shop items and orders.


## User stories:
-------

```
As a shop manager
So I can know which items I have in stock
I want to keep a list of my shop items with their name and unit price.

As a shop manager
So I can know which items I have in stock
I want to know which quantity (a number) I have for each item.

As a shop manager
So I can manage items
I want to be able to create a new item.

As a shop manager
So I can know which orders were made
I want to keep a list of orders with their customer name.

As a shop manager
So I can know which orders were made
I want to assign each order to their corresponding item.

As a shop manager
So I can know which orders were made
I want to know on which date an order was placed. 

As a shop manager
So I can manage orders
I want to be able to create a new order.
```

## Usage
To use the program, simply run the app.rb file in your terminal using the command ruby app.rb. Once the program is running, you can use the following options:

```
# ruby app.rb
Welcome to the shop management program!

What do you want to do?
  1 = list all shop items
  2 = create a new item
  3 = list all orders
  4 = create a new order
  5 = exit

```
By selecting each option, you can interact with the program and perform the corresponding operation.

## Technologies:

- Ruby 3.0.2
- RSpec (for testing)
- Simplecov and Simplecov-console (for test coverage)
- Rubocop (for code analysis and style enforcement)
- PostgreSQL (for database management)

