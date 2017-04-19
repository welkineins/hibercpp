# Design Spec 

version: 0.1

## Objective

Create an simple used SQL query builder and Active Record for operating multiple database backends.

## Components

### Driver
Wrapper of backend database engine.

### Database
Main object to hold a backend driver and porivide basic common sql execution.

### Query Builder
Query builder provides a fluent interface to creating and running queries. 

### Active Record
Active record provides a simple implementation of ActiveRecord pattern to operate database with objects. 
