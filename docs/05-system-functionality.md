# System Functionality

## Overview

The completed Gym Management System combines the database, forms and application interface to provide a centralised system for managing gym information.

The system allows different types of records to be created and managed while maintaining relationships between related information.

## Client Management

The system allows client records to be maintained within the application.

Client information includes:

- Name
- Date of birth
- Payment status
- Membership type

This provides a central location for storing information about gym members.

## Employee Management

Employee records can be created and associated with a gym location.

The system stores information such as the employee's personal details, salary and function within the gym.

## Gym Management

Gym records allow individual gym locations to be maintained within the system.

Each gym can store identifying information such as its name and address and can be referenced by other records within the application.

## Instructor Management

The system allows instructor information to be maintained separately from other employee records.

Instructor records include information such as name, date of birth, salary and specialty.

## Exercise and Workout Type Management

Exercises and workout types can be maintained within the application.

Exercises can be associated with a workout type, allowing them to be organised according to the type of training they are used for.

## Workout Plan Management

Workout plans combine information from several areas of the system.

A workout plan can associate:

- A client
- An instructor
- A gym
- A workout type

Additional information can also be stored for the workout schedule, including start and end dates, frequency and duration.

Using existing records when creating workout plans reduces duplication and connects related information throughout the database.

## User Access

The application includes separate Admin and Staff dashboards.

This provides different entry points into the system depending on the user and demonstrates how the application can be structured around different types of users.

## Complete System

Together, the database structure, management pages and forms create a functional Gym Management System for organising information across the business.

The project demonstrates the process of designing a relational data model and using Genio to transform that structure into a working application with interfaces for accessing and managing the stored information.

---

## Next

[← Go Back](04-forms-and-navigation.md) | [Next →](06-testing-and-troubleshooting.md)
