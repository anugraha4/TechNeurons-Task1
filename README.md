# TechNeurons-Task1

Project Approach
Understanding Requirements:

Thoroughly reviewed the project requirements provided, which included functionalities for student and teacher management, principal dashboard, user authentication, and data visualization based on educational statuses.
Technology Selection:

Chose ASP.NET Core MVC for backend development due to its robustness, cross-platform compatibility, and integrated support for Entity Framework Core.
Selected Entity Framework Core as the ORM (Object-Relational Mapper) for database interaction, leveraging its code-first approach for defining and managing database schema.
Database Design:

Designed a relational database schema using Entity Framework Core's code-first approach. Defined entities such as Student and Teacher with appropriate attributes (e.g., name, address, class, educational status).
Development Steps:

Setup: Created a new ASP.NET Core MVC project using Visual Studio Code. Configured Entity Framework Core to use SQL Server as the database backend.
Model Creation: Defined model classes (Student, Teacher) representing database entities.
Context and Migration: Implemented SchoolContext deriving from DbContext to facilitate database operations. Generated initial migrations and updated the database schema using Entity Framework Core tools (dotnet ef migrations).
Controller and Views: Developed controllers (PrincipalController, TeacherController, StudentController) to handle CRUD operations for students and teachers. Implemented corresponding views using Razor syntax for rendering HTML.
