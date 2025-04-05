Database Systems

Tourmato Database System Overview

Tourmato is a company offering unique "off-the-beaten-track" tours across several European cities. The system includes various entities like customers, employees, equipment, tour sessions, and tourist attractions to help manage these exciting experiences. 
The database is designed to manage all aspects of the business, from customer bookings to equipment maintenance and tour scheduling.

Key Entities and Relationships

Customers: The people booking tours with Tourmato. Customers can book multiple tours, and each booking can have one or more customers.
Employees: These are staff members working at Tourmato, split into two main roles:
Tour Guides: Responsible for leading tour sessions.
Support Staff: In charge of maintaining equipment.
Equipment: Items like bicycles and helmets, used for cycling tours. These are managed by support staff for upkeep.
Tour Sessions: These represent actual tours scheduled on specific dates, with unique start and end times and addresses. Different types of tours include walking, cycling, and food tours.
Tourist Attractions: Locations like landmarks or restaurants that are part of the tour sessions.
Food & Drinks: Available in food tours, customers can enjoy local dishes and drinks while visiting different restaurants.

Database Structure

Customers can book multiple Tour Sessions, and each session can have multiple Tourists (customers).
Tour Sessions can include one or more Attractions, such as landmarks and restaurants, depending on the type of tour.
Tour Guides are assigned to Tour Sessions to lead the tours, ensuring each session has a specific guide.
Support Staff are responsible for maintaining Equipment like bicycles and helmets, ensuring everything is in perfect condition for each tour.

Key Features of the System

Booking System: Allows customers to book and manage tours, with detailed session information (start/end times, price, max customers, etc.).
Tour Types: Different tour types include walking, cycling, and food tours, with some sessions combining activities.
Equipment Management: A robust system for tracking and maintaining bicycles, helmets, and other equipment used for cycling tours.
Staff Roles: Clearly defined roles for Tour Guides and Support Staff to ensure a smooth experience for customers and proper maintenance of equipment.

Data Dictionary

This section outlines the attributes and relationships within the database. Each entity (e.g., Customer, Tour Session, Tour Guide) is explained with details on primary keys, foreign keys, and other relevant attributes like name, contact number, and addresses.
