# Database Design

## Overview

The Gym Management System was built using a relational database structure in Genio. The database was designed to organise information about clients, employees, gyms, instructors, workout plans, workout types and exercises.

Primary and foreign keys were used to connect related information between the tables and allow data to be reused throughout the system.

## Database Model

The database model focuses on five main tables:

- Client
- Employee
- Gym
- Instructor
- Workout Plan

![Database Model](../diagrams/Database%20Model.png)

These tables represent the main entities used to manage clients, staff, gym locations, instructors and workout plans.

## Database Tables

The tables were created and configured within Genio.

![Database Tables Overview](../screenshots/14%20-%20Database%20Tables%20Overview.png)

### Client Table

The Client table stores information about gym clients.

![Client Table Fields](../screenshots/15%20-%20Client%20Table%20Fields.png)

### Employee Table

The Employee table stores information about employees working within the gym.

![Employee Table Fields](../screenshots/16%20-%20Employee%20Table%20Fields.png)

### Exercise Table

The Exercise table stores exercises used within the system and links them to workout types.

![Exercise Table](../screenshots/17%20-%20Exercise%20Table.png)

### Gym Table

The Gym table stores information about gym locations.

![Gym Table](../screenshots/18%20-%20Gym%20Table.png)

### Workout Type Table

The Workout Type table stores the different workout categories available within the system.

![Workout Type Table](../screenshots/19%20-%20Workout%20Type%20Table.png)

### Instructor Table

The Instructor table stores information about gym instructors.

![Instructor Table](../screenshots/20%20-%20Instructor%20Table.png)

### Workout Plan Table

The Workout Plan table connects information from different parts of the system to create a structured workout plan for a client.

![Workout Plan Table](../screenshots/21%20-%20Workout%20Plan%20Table.png)

The table uses references to other records such as clients, instructors, gyms and workout types. It also stores information relating to the workout schedule.

## Summary

The database structure provides the foundation of the Gym Management System. Separating information into individual tables makes the data easier to organise while relationships between the tables allow information to be connected throughout the application.

The database was then used to build the forms and management interfaces used within the completed system.

---

## Next

Continue to [03 - Application Interface](03-application-interface.md) to see how the database was used to build the application's menus, forms and management interfaces.
