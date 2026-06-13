# Aaron Befus — CS 499 ePortfolio

Welcome to my CS 499 Computer Science ePortfolio.

This portfolio includes my professional self-assessment, code review, original and enhanced artifacts, and enhancement narratives for the CS 499 capstone.

## Code Review

My code review evaluates the original CS 465 Travlr Getaways full-stack application as the single artifact selected for enhancement in CS 499. The review examines the project across the three required enhancement categories: software design and engineering, algorithms and data structures, and databases. It also discusses security considerations related to authentication, authorization, validation, configuration, and error handling.

[Watch the Code Review Video](https://youtu.be/oBbEKwmo_oQ)

## Artifact

The original artifact is the CS 465 Travlr Getaways full-stack application. The project was built with the MEAN stack and included static public pages, Express and Handlebars server-rendered routes, REST API routes, MongoDB/Mongoose models, authentication code, and an Angular admin single-page application.

For CS 499, I am enhancing this artifact by migrating it toward a React, Spring Boot, and PostgreSQL architecture. Because all three enhancement categories build on the same application, the same enhanced codebase is used across the portfolio, with each section focusing on a different area of improvement.

## Enhancement One: Software Design and Engineering

The first enhancement focuses on software design and engineering. In this enhancement, I began restructuring the Travlr application into a clearer full-stack architecture with a React frontend and a Spring Boot backend. The enhanced version separates responsibilities across frontend components, API access code, controllers, DTOs, models, services, repositories, and configuration classes.

This work improves the original artifact by reducing the mixed structure of static pages, server-rendered views, API routes, and Angular admin functionality. The enhancement establishes a more maintainable foundation for later work in algorithms and data structures and databases.

[View the Software Design and Engineering Enhancement](https://github.com/aaron-eugene/CS-499/tree/milestone-2-software-design)

[Read the Software Design and Engineering Narrative](https://github.com/aaron-eugene/CS-499/blob/main/Milestone_2_Narrative.md)

## Enhancement Two: Algorithms and Data Structures

The second enhancement focuses on algorithms and data structures. In this enhancement, I improved how the Travlr application handles trip data by adding search, filtering, sorting, pagination, defensive input handling, and summary logic. These changes move the project beyond simply returning all trip records and create a more useful and scalable way to retrieve trip information.

This work improves the original artifact by adding structured query behavior and clearer service-layer coordination. The enhanced backend can process user-selected criteria such as price, duration, search text, sort field, sort direction, page number, and page size. The enhancement also adds tests that verify the behavior of trip search, sorting, filtering, pagination, lookup, and defensive handling of invalid inputs.

[View the Algorithms and Data Structures Enhancement](https://github.com/aaron-eugene/CS-499/tree/milestone-3-algorithms)

[Read the Algorithms and Data Structures Narrative](https://github.com/aaron-eugene/CS-499/blob/main/Milestone_3_Narrative.md)

## Enhancement Three: Databases

The third enhancement focuses on databases. In this enhancement, I migrated the Travlr application from temporary or development-focused data storage toward PostgreSQL-backed persistence using Spring Data JPA and Flyway database migrations. The enhanced version defines a relational trip table, applies database constraints, seeds initial data through migration scripts, and connects the backend repository layer to the PostgreSQL database.

This work improves the original artifact by replacing less structured data handling with a relational schema that better supports validation, uniqueness, indexing, persistence, and future growth. The enhancement also preserves the application’s layered architecture by keeping database access behind a repository abstraction while allowing the service and controller layers to continue working with clear application models and DTOs.

[View the Databases Enhancement](https://github.com/aaron-eugene/CS-499/tree/milestone-4-databases)

[Read the Databases Narrative](https://github.com/aaron-eugene/CS-499/blob/main/Milestone_4_Narrative.md)

## Final Enhancement Direction

The enhancement direction for the full capstone project is to continue building the Travlr Getaways application into a cleaner, more maintainable full-stack system. The React frontend provides a unified component-based user interface, the Spring Boot backend provides structured API, service, validation, security, and repository layers, and PostgreSQL provides relational persistence with appropriate constraints and schema design.

The final version of the project will build on these three enhancement areas by polishing the frontend, improving the admin workflow, strengthening security, updating documentation, and preparing the completed codebase for final portfolio submission.
