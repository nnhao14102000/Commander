# MVC REST API Application

## Technology and tools

1. NET Core 3.1 MVC REST API
2. Repository pattern
3. Dependency injection
4. Entity Framework
5. Data Transfer Objects (DTOs)
6. AutoMapper
7. Tools: VSCode, SQL Server, Postman.

## Agenda

1. FIRST 2 API ENDPOINTS (GET / READ)

- Project Setup
- Create our Domain Model (Command)
- Build Our Repository Interface
- Implement our Repository Interface (Mock Reposiory)
- Create our Controller (CommandsController)
- Create 2x API Endpoints
- Using Dependency Injection

2. ENTITY FRAMEWORK & SQL SERVER

- Architecture Checkpoint
- Set Up SQL Server App Login
- Entityframework Packages
- Entityframework Toolset
- Create our Database Context (CommanderContext)
- Our Database Connecttion String
- Register our DB Context in Startup
- Create Migrations
- Cancel Migrations & revist Command Model
- Add Data Validations to Command Model
- Create Migrations (Again!)
- Run Migrations against Database
- Add Data to Database
- Revist Our Repository to use DB Context

3. DATA TRANSFER OBJECTS & CREATE ENDPOINT

- Architecture Checkpoint
- Why Data Transfer Objects?
- AutoMapper Package & Startup Registration
- Create our first DTO
- Creating a mapping Profile
- Updating Our Action Results to use DTOs

4. PUT, PATCH & DELETE API ENDPOINTS

- Architecture Checkpoint
- Updating our Repository for Creating Resources
- Create a New DTO (for Creating)
- Create 3rd API Endpoint to Create Resources
- Use CreatedAtRoute to return 201 CreatedAtRoute
- Add Annotations to DTO to avoid 500 Errors
- Update Repository to Support Updates
- Add a New DTO (for Updating)
- Add 4th API Endpoint for Updating (PUT Request)
- Update our AutoMapper Profile
- Overview of PATCH
- Install 2x packages to support PATCH
- Update Startup
- Update our AutoMapper Profile (Final Update)
- Add 5th API Endpoint for Updating (PATCH Request)
- Add 6th API Endpoint for Deleting (DELETE Request)

## Reference

[.NET Core 3.1 MVC REST API](https://youtu.be/fmvcAzHpsk8) Of Les Jackson

#### © 14/02/2021 | Write again code by Nguyen Nhut Hao and thanks for this video above from Les Jackson
