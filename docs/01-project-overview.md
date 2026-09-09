# 01 — Project Overview

## Introduction

The Genio Gym Management System was developed during an international internship at **Quidgest in Lisbon, Portugal** in 2022.

The project was completed collaboratively by **Deividas Talocka and Bobby Traykov** using the Genio development platform.

The objective was to design and build a system that could organise and manage information used within a gym environment.

## Project Purpose

The system was designed to make it easier for gym staff and administrators to manage information relating to:

- Clients
- Employees
- Instructors
- Gym locations
- Exercises
- Workout types
- Workout plans

Rather than requiring users to work directly with the underlying database, the system provides forms and navigation features that make information easier to access and modify.

## Users

Two types of user accounts were implemented:

### Admin

The Admin account provides greater access to the system and allows authorised users to modify and maintain database information.

### Staff

The Staff account has more restricted access, allowing employees to perform the tasks required for their role while limiting unnecessary access to database functionality.

## System Design

The application was built around a relational data model connecting the different areas of the gym management system.

For example, workout plans combine information relating to clients, instructors and workout types through relationships between the underlying data structures.

The system also uses required fields to ensure important information is entered before certain records can be completed.

## User Interface

Forms were created to provide a simpler method of entering and modifying information.

A structured menu tree was also implemented to organise navigation between different areas of the application.

The interface was customised using Genio's integrated theme tools to provide a consistent application layout.

## Project Scope

The completed system demonstrates:

- Relational data modelling
- Data relationships
- User access levels
- Data-entry forms
- Application navigation
- Business information management
- User interface customisation

## Next

Continue to [02 — Database Design](02-database-design.md).
