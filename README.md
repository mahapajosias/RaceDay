# RaceDay Event Management System

## Project Description

RaceDay is a full-stack event management system designed to manage race events, participant enrolments, event categories and race results.

The system allows organisers to create and manage race events and categories, while participants can register, view events, enrol in race categories and view their results.

This repository contains the planning documentation and database design for Part 1 of the PROG6212 Programming 2B assignment.

## User Roles
L
### 1. Organiser

The Organiser can:

- Create race events
- Update race events
- Delete race events
- Create and manage event categories
- View event participants
- Record race results
- Update race results

### 2. Participant

The Participant can:

- Register an account
- Log in and log out
- Manage their profile
- View available race events
- View event categories
- Enrol in race categories
- View their enrolments
- View their race results

## Part 1 Documentation

The `docs` folder contains:

- RaceDay ERD
- API Endpoint Plan
- SQL Database Script

## Database

The RaceDay database contains the following main entities:

- USERS
- EVENTS
- CATEGORIES
- ENROLMENTS
- RESULTS
- PARTICIPANT_PROFILES

The database uses primary keys and foreign keys to maintain relationships between the entities.

## API

The planned API provides endpoints for:

- Authentication
- User profiles
- Events
- Categories
- Enrolments
- Results

## Continuous Integration

GitHub Actions is used to validate the required Part 1 documentation and SQL database script.

The CI workflow checks that the required files exist and validates important SQL statements.

## Demonstration Video

YouTube video:

**To be added after recording the Part 1 demonstration video.**

## Module Information

**Module:** PROG6212  
**Project:** RaceDay Event Management System  
**Part:** Part 1
