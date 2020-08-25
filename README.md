# Interview Prep Test App
Welcome to the Interview Prep Test App. The goal of this application is to prepare for a technical interview with a team at Nike.

## The problem:
Nike needs to replace a legacy inventory management systems with a new system.

## The Tools:
- Python
    - Django Rest API
    - MongoDB Database 
- Java
    - Spring Rest API
    - Postgres SQL database
- Vue.js
- Google OAUTH
- Redis Cache
    - used to cache sessions between the different applications.


## Step One Hello World
The first step is to get all of the different modules that this project will require set up. I plan to use docker compose to set up all the dependencies that I will not be required to make direct changes but will just need to configure.

## Step Two Requirements:
At some point in the future I will fill this fake requirements for my small inventory system.

What am I doing and why am I doing it?

## Architecture

            Python -> MongoDB
Vue.js -> 
            Java -> PostGres

Java Responsible for:
Managing list of customers and orders.
Python Responsible for:
Inventory and Salesrm 

Vue App:
- Home Page:
    - Links
        - Customer Page
        - Inventory Page
        - Order Page
        - Sales Page
        - Order Completion page
- Sales Page - CRUD
- Inventory Page - CRUD
- Order Page - CRUD
- Sales Page - View Only
- Order Complete Page - Select and order to complete
    - Removes inventory and then changes status on order adds sale to sales collection.


## Implementation

## Release Plan

## Known Issues

