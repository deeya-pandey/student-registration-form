# Student Registration System

A full-stack web application for managing student registrations. It allows users to register students, upload supporting documents, view student records, edit details, and delete records.

## Features

- Student registration with multi-step form sections
- Personal information management
- Address selection using province, district, and municipality
- Parent/guardian details
- Enrollment and academic history
- Financial details and scholarship information
- Extra-curricular activities and awards
- Supporting document uploads
- Student list, detail, edit, and delete operations
- Dropdown data for nationality, blood group, marital status, and disability status
- REST API with Swagger documentation

## Tech Stack

### Frontend

- React
- Vite
- Tailwind CSS
- React Router
- React Hook Form
- Zod
- Axios

### Backend

- ASP.NET Core 8
- Entity Framework Core
- SQL Server
- AutoMapper
- Swagger / OpenAPI

## Project Structure

```text
student-registration-form/
├── frontend/                  # React frontend application
│   ├── src/
│   │   ├── components/         # Registration form components
│   │   ├── pages/              # Registration, list, detail, and edit pages
│   │   └── api/                # API request configuration
│   └── package.json
│
├── backend/                   # ASP.NET Core Web API
│   ├── Controllers/            # API endpoints
│   ├── Data/                   # Entity Framework database context
│   ├── DTOs/                   # Data transfer objects
│   ├── Models/                 # Database models
│   ├── Repositories/           # Data-access layer
│   ├── Services/               # Business logic layer
│   ├── Migrations/             # Entity Framework migrations
│   ├── Uploads/                # Uploaded student files
│   └── StudentRegistrationAPI.csproj
│
└── README.md
