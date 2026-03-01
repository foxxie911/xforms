# XForms - Dynamic Form Builder Platform

A comprehensive web application built with ASP.NET Core Blazor Server that enables users to create, manage, and share dynamic forms and templates with real-time collaboration features.

## Key Features

### Core Functionality
- **Dynamic Form Creation**: Build customizable forms with various question types (text, multiple choice, checkboxes, etc.)
- **Template Management**: Create reusable form templates with drag-and-drop question ordering
- **Real-time Collaboration**: Live commenting system using SignalR for team feedback
- **Multi-language Support**: Localization support with resource files for internationalization
- **User Management**: Role-based access control with admin dashboard

### Technical Highlights
- **Authentication & Security**:
    - Full ASP.NET Core Identity implementation with 2FA support
    - External login providers integration (Google, Microsoft, etc.)
    - Custom authorization policies and role management
    - Password reset and email confirmation workflows

- **Data Management**:
    - PostgreSQL database with Entity Framework Core
    - Optimistic concurrency control for data integrity
    - Comprehensive data seeding for development
    - Efficient indexing strategies for performance

- **Modern UI/UX**:
    - MudBlazor component library for responsive design
    - Dark/light theme support
    - Real-time notifications and status messages
    - Mobile-responsive layouts

## Technology Stack

### Backend
- **ASP.NET Core 9.0** - Web framework
- **Entity Framework Core** - ORM and data access
- **PostgreSQL** - Primary database
- **Cloudinary** - Image management and storage

### Frontend
- **Blazor Server** - Interactive web UI framework
- **MudBlazor** - Material Design component library
- **HTML5/CSS3** - Semantic markup and styling

### Services & Integration
- **Salesforce API** - CRM integration capabilities
- **External Authentication** - OAuth 2.0 providers
- **Email Services** - SMTP configuration ready

## Getting Started

### Prerequisites
- .NET 9.0 SDK
- PostgreSQL database
- Visual Studio 2022 or JetBrains Rider

### Installation
1. Clone the repository
2. Configure connection strings in `appsettings.json`
3. Run database migrations

```bash
dotnet ef database update
```
4. Start the application:

```bash
dotnet run
```

## Key Technical Achievements

### Architecture & Design Patterns
- **Clean Architecture**: Separation of concerns with distinct layers
- **Dependency Injection**: Comprehensive DI container configuration
- **Repository Pattern**: Abstracted data access layer
- **CQRS Principles**: Command-query separation in service design

### Performance Optimizations
- Database indexing strategies for common queries
- Lazy loading and eager loading configurations
- Caching considerations for frequently accessed data
- Optimistic concurrency handling

### Security Best Practices
- Role-based authorization with custom policies
- Secure password hashing and management
- Anti-forgery token implementation
- Input validation and sanitization

## Skills Demonstrated

This project showcases expertise in:
- **Full-stack Development**: End-to-end web application development
- **Modern .NET**: Latest ASP.NET Core features and best practices
- **Database Design**: Relational modeling and EF Core advanced features
- **Authentication Systems**: Complex identity management scenarios
- **UI/UX Development**: Component-based architecture and responsive design
- **API Integration**: Third-party service integration (Salesforce, Cloudinary)
- **DevOps Readiness**: Configuration management and deployment preparation