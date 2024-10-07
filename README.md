Overview

This project is a simple application designed to manage a registry of government-funded training centers. It provides two APIs:
1. POST API : to create and save a new training center.
2. GET API : to retrieve all stored training centers.

The application uses an in-memory database and includes features such as validation for fields and error handling via an `ExceptionHandler`.

Features

- Add a new training center with validation for fields (such as CenterName, CenterCode, and ContactPhone).
- Retrieve all stored training centers.
- Automatic server-side timestamp generation for `createdOn` field.
- Uses Spring Boot for backend, JPA for database interaction, and H2 as an in-memory database.

Technologies

- Java 
- SpringBoot
- Database
- JUnit (for testing)
