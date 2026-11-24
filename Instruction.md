Project 1: Subject Loading and Room Assignment Monitoring System

Project Overview
Design and develop a Windows Desktop Application using C# .NET Framework WinForms that manages subject loading, schedules, and room assignments for an academic institution. The system should prevent scheduling conflicts and optimize resource utilization and should have a live viewing of the current class schedule. 

 Project Objectives
- Implement OOP principles (Encapsulation, Inheritance, Polymorphism, Abstraction)
- Implement SOLID principle
- Create a functional WinForms application with intuitive UI
- Apply proper software architecture and design patterns
- Demonstrate version control proficiency using GitHub

 Core Features Required:
 1. User Management Module
- Admin Account
  - Full system access
  - User account management
  - System configuration
- Faculty Account (Optional)
  - View personal schedule
  - View room assignments
  - Request schedule changes 
- Registrar Account (Optional)
  - Manage subject loading
  - Assign rooms
  - Generate reports

 2. Subject Management
- Add, edit, delete, search subjects
- Subject details: Code, Title, Units, Department, Program
- Subject offerings per semester/term
- Lecture and laboratory components

 3. Faculty Loading Module
- Assign subjects to faculty members
- Set maximum teaching load per faculty
- Track teaching units and hours
- Handle overload assignments with approval workflow

 4. Room Assignment Module
- Room inventory management (Room number, Capacity, Type)
- Schedule room assignments
- Visual room availability calendar
- Conflict detection system
- Room utilization reports

 5. Schedule Management
- Time slot configuration (Day, Start Time, End Time)
- Class schedule creation and editing
- Conflict checking algorithm (same faculty, same room, same students)
- Block scheduling support
- Schedule templates (optional)

 6. Reporting Module (optional)
- Faculty loading reports (per faculty, per department)
- Room utilization reports
- Master schedule (per program, per year level)
- Conflict reports
- Export to PDF/Excel


Class Structure (Minimum)
Core Classes:
- User (base class)
  - Admin (inherits User)
  - Faculty (inherits User) (optional)
  - Registrar (inherits User) (optional)
- Subject
- Room
- Schedule
- TimeSlot
- Department
- AcademicTerm
- FacultyLoad
- ScheduleConflictChecker

Manager Classes:
- UserManager (Optional)
- SubjectManager
- RoomManager
- ScheduleManager
- ReportManager (Optional)
- FacultyManager

Database Requirements
- Use SQL Server or MySQL
- Implement proper normalization (at least 3NF)
- Use stored procedures for complex operations (optional)
- Implement transactions for critical operations (optional)

 UI Requirements (Minimum)
- Login Form with role-based authentication (optional)
- Dashboard showing key metrics and notifications
- Data Entry Forms with validation
- Search and Filter functionality
- DataGridView for displaying records
- Schedule Views for visual schedule representation
- Proper error handling and user feedback
- Professional UI design with consistent theme

 Required Documentation

 1. UML Diagrams
- Class Diagram (showing all classes, attributes, methods, relationships)
- Use Case Diagram (showing actors and their interactions)

 2. Entity Relationship Diagram (ERD)
- Complete database schema
- Show all tables, columns, data types
- Indicate primary keys, foreign keys
- Show relationships and cardinality

 3. Project Documentation
- Project Description


Grading Criteria

| Criteria | Points |
|------------|---------|
| OOP Implementation (Design Patterns, SOLID principles) | 25% |
| Functionality (Features working properly) | 25% |
| Database Design (Normalization, relationships) | 10% |
| User Interface (Usability, design) | 15% |
| Documentation (UML, ERD, SRS, etc.) | 15% |
| Code Quality (Clean code, comments, organization) | 10% |
| Total | 100% |

Project Timeline
TBD

Submission Requirement
1. GitHub Repository (must be accessible to teacher)
2. Complete Documentation (uploaded to repository)
3. Working Application
4. Database Backup (.bak or .sql file)


Important Notes
- Code must be original work - plagiarism will result in project failure
- All team members must contribute - check commit history
- Regular commits required - not just one final upload
- Application must handle exceptions - no crashes allowed
- Follow C# naming conventions - PascalCase for classes/methods, camelCase for variables

Support Resources
- Microsoft C Documentation: https://docs.microsoft.com/dotnet/csharp/
- SQL Server Documentation: https://docs.microsoft.com/sql/
- GitHub Guides: https://guides.github.com/
Shalom!
