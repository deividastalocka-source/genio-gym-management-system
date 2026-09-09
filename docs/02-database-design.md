# Database Design

## Overview

The Gym Management System was built using a relational database structure in Genio. The database was designed to organise information about clients, employees, instructors, gyms and workout plans.

Primary and foreign keys were used to connect related information between the tables.

## Database Model

The database model contains five main tables:

- Client
- Employee
- Gym
- Instructor
- Workout Plan

![Database Model](../diagrams/Database%20Model.png)

The model shows how the main parts of the system are connected. The Workout Plan table acts as an important part of the database because it references information stored in other tables.

## Client Table

The Client table stores information about gym clients, including details required to manage their membership and workout plans.

## Employee Table

The Employee table stores information about employees working within the gym.

## Gym Table

The Gym table stores information about gym locations.

## Instructor Table

The Instructor table stores information about instructors, including their personal and employment information.

## Workout Plan Table

The Workout Plan table connects information from other parts of the system to create a workout plan for a client.

It can reference records such as the client, instructor and gym through foreign keys. This allows the system to reuse existing information instead of duplicating it across multiple records.

## Database Implementation

The database structure was implemented within Genio, where the tables, fields, primary keys and foreign-key relationships were configured.

The completed database structure provided the foundation for the forms and other functionality developed later in the project.
