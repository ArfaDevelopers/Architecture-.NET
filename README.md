# Architecture Template
The goal of this template is to provide a straightforward and efficient approach to enterprise application development, leveraging the power of clean Architecture and ASP.NET Core.

Using this template, you can effortlessly create a Single Page App (SPA) with ASP.NET Core and Angular or React, while adhering to the principles of Clean Architecture.

Getting started is easy - simply install the .NET template (see below for full details).

# Getting Started
The following prerequisites are required to build and run the solution:

- .NET 8.0 SDK (latest version)
- Node.js (latest LTS, only required if you are using Angular or React)
- The easiest way to get started is to install the .NET template:
- Once installed, create a new solution using the template. You can choose to use Angular, React, or create a Web API-only solution.
- Specify the client framework using the -cf or --client-framework option, and provide the output directory where your project will be created.

# Database
The template is configured to use SQL Server by default.

When you run the application the database will be automatically created (if necessary) and the latest migrations will be applied.

Running database migrations is easy.

# Deploy
The template includes a full CI/CD pipeline. The pipeline is responsible for building, testing, publishing and deploying the solution to Azure. If you would like to learn more, read the deployment instructions.

# Technologies
- ASP.NET Core 8
- Entity Framework Core 8
- Angular 15 or React 18
- MediatR
- AutoMapper
- FluentValidation
- NUnit, FluentAssertions, Moq & Respawn
