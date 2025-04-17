# Educational .NET Core Leave Management System

This repository contains the source code for an Educational .NET Core Leave Management System built using Clean Architecture. The project uses CQRS, AutoMapper, Blazor, .NET API, and EF Core. It also includes unit and integration tests.


## Table of Contents

- [Technologies](#technologies)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Code Samples](#code-samples)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [License](#license)

## Technologies

The project uses the following technologies:

- .NET Core (6/7/8)
- CQRS
- AutoMapper
- Blazor
- .NET API
- EF Core
- xUnit
- Moq

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository to your local machine.
2. Open the solution file in Visual Studio or another IDE of your choice.
3. Restore the NuGet packages.
4. Set the startup projects to `HR.LeaveManagement.Api` and `HR.LeaveManagement.BlazorUI`.
5. Run the project.

## Project Structure

The project is organized using the Clean Architecture principles. The solution is composed of the following projects:

- `HR.LeaveManagement.Application`: Contains the application layer of the project, which contains the application logic and interfaces.
- `HR.LeaveManagement.Domain`: Contains the domain layer of the project, which contains the domain models and business rules.
- `HR.LeaveManagement.Infrastructure`: Contains the infrastructure layer of the project, which contains the implementation of the interfaces defined in the application layer.
- `HR.LeaveManagement.Api`: Contains the API layer of the project
- `HR.LeaveManagement.BlazorUI`: Contains the Blazor client application

## Code Samples

The project contains code samples for several areas of .NET Core development, including:

- CQRS
- AutoMapper
- Blazor
- .NET API
- EF Core
- Unit Testing
- Integration Testing

Each project and code sample is well-documented, and the code is designed to be easy to read and follow.

## Documentation

The repository contains documentation for each of the code samples, including:

- An overview of the sample and its intended use case
- Installation and configuration instructions
- Code walkthroughs and explanations
- Best practices and tips for working with the sample

The documentation is designed to be accessible to developers of all skill levels, from beginners to advanced users.

## Contributing

Contributions to this repository are welcome. If you have a code sample or educational resource that you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes and commit them to your branch.
4. Submit a pull request.

Please ensure that your contributions adhere to the repository's code of conduct and that they are well-documented and follow best practices.

## Course

What you'll learn

    Implement SOLID Principles
    ASP .NET Core Blazor and API Development
    Advanced Tools - MediatR, Automapper, Fluent API and Validation
    Custom Exceptions and Global Error Handling
    Custom .NET Core Middleware
    Using NSwag and NSwag Studio
    Use Swagger for API Documentation
    Implement CQRS Pattern
    Use Identity and JWT To Secure Application API
    Build API Client Secure Application
    Moq and Shouldly Frameworks
    Unit Testing

Description

Overview

Creating a modular, testable, and maintainable application in .NET Core requires a solid foundation. Setting up an application architecture requires foresight and much consideration, as early decisions will impact how easily the application is extended and maintained.

In the long run, though, applications need to be maintained and, in this case, extended. Between its design and the way the code was written, neither is possible, so the application needs to be redesigned and future-proofed.

Why SOLID Architecture?

When we talk about SOLID architecture, what we refer to isn’t a straightforward task. Decisions made early in the process can have a large impact later on, and maintainability and testability play an important role. Adopting these practices can also contribute to avoiding code smells, refactoring code, and facilitating more efficient agile development.

SOLID stands for:

    S - Single-Responsibility Principle

    O - Open-closed Principle

    L - Liskov Substitution Principle

    I - Interface Segregation Principle

    D - Dependency Inversion Principle

In this course, you explore foundational architectural principles which help with the creation of maintainable code. You will discover how to set up a real-world application architecture with ASP.NET Core. Then, you’ll learn how to plug in different, common blocks such as email and authentication and have a foundation to plug-in other third-party services as needed.

Everything in this course is .NET 6 / .NET 7 compatible.

When you finish this course, you’ll have the skills and knowledge to create a testable and maintainable ASP.NET Core application to architect real-world enterprise .NET Core apps.

N.B. - The project in this course is based on the deliverables in Complete ASP.NET Core and Entity Framework Development. While it is not mandatory to do this course, much of the existing code will be reused from this course's content.

Build A Strong Foundation in .NET Clean Architecture:

    Learn Clean or Onion Architecture and Best Practices

    Learn Command Query Responsibility Segregation (CQRS)

    Implement Mediatr Pattern

    Add Email Service using SendGrid

    Efficient Exception Handling and Routing

    Implementing Unit Testing

    Moq and Shouldy

    Global Error Handling with Custom Middleware and Exceptions

    Adding Validation Using Fluent Validation

    Build a .NET Core API and Blazor UI Application

    Implement JWT(JSON Web Token)  Authentication

Content and Overview

To take this course, you must have some knowledge of .NET Core development and C#.

This is a huge course. Over 10 hours of premium content, but smartly broken up to highlight related activities based on each module in the application being built. We will also look at troubleshooting and debugging errors as we go along; implementing best practices; writing efficient logic, and understanding why developers do things the way they do. Your knowledge will grow, step by step, throughout the course, and you will be challenged to be the best you can be.

We don't do things the perfect way the first time; that is different from the reality of writing code. We make mistakes and point them out and fix them around them. By doing this, we develop proficiency in using debugging tools and techniques. By the time you have finished the course, you will have moved around in Visual Studio and examined logic and syntax errors so much that it will be second nature for you when working in the .NET environment. This will put your newly learned skills into practical use and impress your boss and coworkers.

The course is complete with working files hosted on GitHub, including some files to make it easier for you to replicate the demonstrated code. You will be able to work alongside the author as you work through each lecture and will receive a verifiable certificate of completion upon finishing the course.

Course by Trevoir Williams