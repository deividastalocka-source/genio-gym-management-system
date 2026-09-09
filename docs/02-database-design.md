# Database Design

## Overview

The Gym Management System was designed around a relational database structure created in Genio. The database stores information about clients, employees, gyms, instructors, exercises, workout types and workout plans.

The tables are connected using primary and foreign keys so that related information can be referenced across the system without unnecessary duplication.

## Database Model

The database model shows the main tables used by the system and the relationships between them.

![Database Model](../diagrams/Database%20Model.png)

The main tables are:

- Client
- Employee
- Exercise
- Gym
- Instructor
- Workout Type
- Workout Plan

Each table was created to store a specific type of information required by the gym management system.

## Table Structure

The tables were configured within Genio with fields for storing the required data. Primary keys were used to uniquely identify records, while foreign keys were used where information from another table needed to be referenced.

### Exercise

The Exercise table stores exercises available within the system.

![Exercise Table](../screenshots/17%20-%20Exercise%20Table.png)

The table includes an exercise code, workout type reference and exercise name. The workout type is linked through a foreign key.

### Workout Type

The Workout Type table stores the different categories of workouts available within the system.

This allows exercises and workout plans to be associated with a particular workout type.

### Instructor

The Instructor table stores information about gym instructors.

![Instructor Table](../screenshots/19%20-%20Instructor%20Table.png)

Information stored includes the instructor's name, date of birth, average salary and specialty.

### Workout Plan

The Workout Plan table brings together information from several parts of the database.

![Workout Plan Table](../screenshots/20%20-%20Workout%20Plan%20Table.png)

Foreign keys are used to connect a workout plan with:

- A client
- An instructor
- A gym
- A workout type

The table also stores information such as the start date, end date, number of sessions per week and workout duration.

This structure allows a workout plan to reference existing records instead of storing the same client, instructor, gym and workout information repeatedly.

## Forms

Forms were created in Genio to provide a structured interface for viewing and entering information stored within the database.

The project contains forms for:

- Clients
- Employees
- Exercises
- Gyms
- Instructors
- Workout Types
- Workout Plans

The complete list of forms can be viewed within Genio:

![Forms List](../screenshots/22%20-%20Forms%20List.png)

These forms provide the user-facing interface for working with the underlying database tables.
