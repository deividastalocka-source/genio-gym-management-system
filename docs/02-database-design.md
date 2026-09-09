# 02 — Database Design

## Overview

The Genio Gym Management System was designed around a relational data model that connects the different types of information required by the application.

The database structure was created before implementing the system in Genio and was used as the foundation for the application's tables, forms and relationships.

## Database Model

![Genio Gym Management System Database Model](../diagrams/Database-Model.png)

The editable source diagram is also available here:

[Database Model — Draw.io Source](../diagrams/Database-Model.drawio)

## Main Data Areas

The system was structured around several main areas of gym information:

- Clients
- Employees
- Instructors
- Gyms
- Exercises
- Workout Types
- Workout Plans

Each area stores information required for a particular part of the system while relationships allow information to be shared between them.

## Clients

Client records store information relating to gym members, including:

- Name
- Date of birth
- Membership type
- Due payments

Client information can then be referenced when creating workout plans.

## Employees and Instructors

Employee records store information such as the employee's role, salary and date of birth.

Instructor records contain information specific to gym instructors, including their specialty.

This allows instructors to be associated with workout plans created for clients.

## Gyms

Gym records contain the name and location of each gym.

These records allow other areas of the system to associate information with a particular gym location.

## Exercises and Workout Types

Exercises and workout types provide the information required to organise the different forms of exercise available within the system.

These records can then be referenced when building workout plans.

## Workout Plans

The workout plan structure brings information from multiple areas of the system together.

A workout plan can contain information such as:

- Client
- Instructor
- Workout type
- Start date
- End date
- Workout frequency
- Workout duration

Relationships between the underlying data allow these records to reference information already stored elsewhere in the system rather than duplicating it.

## Data Validation

Some fields were configured as required fields.

This prevents a user from completing certain records without entering essential information. For example, the client field within a workout plan was made mandatory.

## Design Outcome

The relational structure provided a foundation for the rest of the application by allowing related business information to be organised and connected within the system.

The design was then implemented in Genio and used to build the application's tables, forms and user-facing functionality.

## Next

Continue to [03 — Authentication and User Roles](03-authentication-and-user-roles.md).
