# School Management System

A comprehensive school management platform for managing students, teachers, courses, grades, attendance, and finances.

## Features

- **Student Management**: Registration, profiles, attendance tracking
- **Teacher Management**: Staff credentials, schedules, class assignments
- **Course Management**: Curriculum, class schedules, enrollment
- **Grading System**: Grades, transcripts, GPA calculation
- **Attendance Tracking**: Daily attendance, reports, analytics
- **Timetable Management**: Class schedules, teacher schedules
- **Finance Management**: Tuition, payments, receipts, invoices
- **Notifications**: Email/SMS alerts for parents, students, and staff
- **Reports & Analytics**: Performance dashboards, statistical reports
- **Role-Based Access**: Admin, Teacher, Student, Parent dashboards

## Tech Stack

- **Backend**: Node.js, Express.js
- **Frontend**: React, Redux, Tailwind CSS
- **Database**: PostgreSQL
- **Authentication**: JWT
- **APIs**: RESTful API

## Project Structure

```
school-system/
├── backend/              # Express.js API server
├── frontend/             # React dashboard application
├── database/             # Database schema and migrations
├── docs/                 # Documentation
└── docker-compose.yml    # Docker setup for local development
```

## Quick Start

### Prerequisites
- Node.js (v16+)
- PostgreSQL (v12+)
- Docker & Docker Compose (optional)

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install --prefix backend
   npm install --prefix frontend
   ```
3. Set up database:
   ```bash
   createdb school_management
   npm run migrate --prefix backend
   ```
4. Start the backend:
   ```bash
   npm run dev --prefix backend
   ```
5. Start the frontend:
   ```bash
   npm start --prefix frontend
   ```

## Documentation

See the [docs](./docs) folder for detailed documentation on:
- API endpoints
- Database schema
- User roles and permissions
- Setup and deployment

## License

MIT
