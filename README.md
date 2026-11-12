# Thorncroft Park Primary School – Integrated Digital Platform

**Project Type:** School Website, School Information System (SIA/SIS) & Learning Management System (LMS)  
**Location:** Ruwa, Mashonaland East, Zimbabwe  
**Project Status:** Planning & Requirements Gathering  
**Year:** 2026

---

## 1. Project Overview

The Thorncroft Park Primary School Digital Platform is a proposed integrated web-based system designed to modernise the school's administrative, academic and educational activities.

The project aims to provide a centralised digital environment where school administrators, teachers, parents and students can interact with school information and educational resources.

The platform will consist of three main components:

1. **Official School Website** – Provides public information about the school.
2. **School Information System (SIA/SIS)** – Manages student records, teachers, attendance, examinations and school administration.
3. **Learning Management System (LMS)** – Supports digital learning, assignments, educational materials and assessments.

All three components will share a common backend, database and authentication system.

## 2. Project Objectives

The main objectives are:

- Establish a professional online presence for Thorncroft Park Primary School.
- Digitise student and teacher information management.
- Simplify school administrative processes.
- Improve communication between teachers, parents and students.
- Provide a centralised platform for academic records.
- Support digital teaching and learning.
- Improve access to educational materials.
- Reduce dependence on manual record-keeping.
- Provide secure and organised access to school information.

## 3. Main System Components

### 3.1 Official School Website

The public-facing website will serve as the school's official online information platform.

**Planned features:**

| Page | Description |
|---|---|
| Home | School introduction and highlights |
| About Us | School background, mission and vision |
| Academics | Grades, subjects and programmes |
| Leadership | School administration and leadership |
| Admissions | Admission information and application process |
| News & Events | School announcements and activities |
| Gallery | School photos and events |
| Contact | Contact information and location |

**Expected outcome:** A professional and accessible website where parents, prospective students and visitors can learn about the school.

### 3.2 School Information System (SIA/SIS)

The School Information System will handle administrative and academic management.

**Planned modules:**

| Module | Functionality |
|---|---|
| Dashboard | Overview of school activities |
| Student Management | Student registration and profiles |
| Teacher Management | Teacher and staff records |
| Class Management | Grade and class allocation |
| Attendance Management | Daily attendance records |
| Timetable Management | Class and teacher schedules |
| Examination Management | Examination setup and marks |
| Results Management | Academic performance records |
| Report Cards | Generate student academic reports |
| Fees Management | Record payments and outstanding balances |
| Parent Portal | Access children's academic information |
| Notifications | Important school announcements |

**Expected outcome:** A centralised system that helps school administrators manage daily operations and academic information.

### 3.3 Learning Management System (LMS)

The LMS will provide a digital environment for teachers and students.

**Planned modules:**

| Module | Functionality |
|---|---|
| Digital Classrooms | Create and manage online classes |
| Subject Management | Organise learning by subject |
| Learning Materials | Upload PDFs, documents and videos |
| Assignments | Create and distribute homework |
| Submissions | Students submit completed assignments |
| Quizzes | Online quizzes and assessments |
| Grading | Teachers assess student submissions |
| Feedback | Teachers provide academic feedback |
| Progress Tracking | Monitor student learning progress |
| Announcements | Classroom updates |
| Learning Calendar | Assignment and lesson schedules |

**Expected outcome:** An accessible digital learning environment that supports teaching, homework and student progress monitoring.

## 4. User Roles and Permissions

The platform will support five primary user categories.

| User Role | Responsibilities |
|---|---|
| Super Administrator | Complete system configuration and management |
| Headteacher | School-wide administrative and academic oversight |
| Teachers | Manage classes, attendance, assignments and academic results |
| Parents/Guardians | Monitor children's attendance, performance and announcements |
| Students | Access learning materials, assignments and academic information |

Each user will have permissions appropriate to their responsibilities.

## 5. System Integration

The website, SIA and LMS will operate as interconnected components rather than independent applications.

They will share a central backend and database.

### Example workflow

1. An administrator registers a student through the SIA.
2. The student is assigned to a grade and class.
3. The student receives access to the appropriate LMS classroom.
4. Teachers record attendance through the SIA.
5. Teachers upload learning materials and assignments through the LMS.
6. Students access materials and submit assignments.
7. Teachers assess submissions and record results.
8. Parents access their children's academic progress through the parent portal.

This integration will reduce duplicated information and improve communication between different parts of the school.

## 6. Technology Stack

The following technologies are proposed for development.

| Technology | Purpose |
|---|---|
| React.js | Frontend development |
| Tailwind CSS | Responsive user interface styling |
| Node.js | Backend runtime |
| Express.js | Backend framework and REST APIs |
| PostgreSQL | Relational database |
| JWT / Secure Sessions | Authentication |
| REST API | Communication between frontend and backend |
| Cloudinary / Object Storage | File and image storage |
| Git | Version control |
| GitHub | Source code management |
| Vercel | Frontend deployment |
| Backend Hosting | API deployment |

The final hosting and storage providers will be selected after evaluating the school's requirements, budget and internet availability.

## 7. Proposed System Architecture

The project will initially follow a modular monolithic architecture.

This means the application will use one backend while keeping its functionality organised into separate modules.

```text
thorncroft-school/
│
├── frontend/
│   ├── public-website/
│   ├── admin-dashboard/
│   ├── teacher-portal/
│   ├── parent-portal/
│   └── student-portal/
│
├── backend/
│   ├── config/
│   ├── middleware/
│   ├── modules/
│   │   ├── authentication/
│   │   ├── students/
│   │   ├── teachers/
│   │   ├── classes/
│   │   ├── attendance/
│   │   ├── examinations/
│   │   ├── results/
│   │   ├── fees/
│   │   ├── assignments/
│   │   ├── learning-materials/
│   │   └── notifications/
│   │
│   └── server.js
│
├── database/
│   ├── schema.sql
│   └── migrations/
│
├── documentation/
│
├── .gitignore
└── README.md
```

*This is a proposed structure and may change during implementation.*

## 8. Development Roadmap

Development will be divided into eight phases.

### Phase 1: Research and Requirements Gathering

- Understand existing school administrative processes.
- Identify the needs of administrators, teachers, parents and students.
- Confirm grade structure and subjects.
- Gather approved school information and branding materials.
- Define functional and technical requirements.

### Phase 2: UI/UX Design

- Design the public website.
- Design administrator dashboards.
- Design teacher, parent and student portals.
- Create responsive layouts.
- Establish a consistent design system.

### Phase 3: Database and Backend Development

- Design database tables and relationships.
- Implement authentication.
- Implement role-based access control.
- Develop REST API endpoints.
- Implement data validation and security.

### Phase 4: Public Website Development

- Develop the homepage.
- Create school information pages.
- Implement news and announcements.
- Develop admissions information pages.
- Implement gallery and contact pages.

### Phase 5: School Information System Development

- Student registration.
- Teacher and staff management.
- Class and subject management.
- Attendance tracking.
- Timetable management.
- Examination management.
- Academic results.
- Report card generation.
- Fees management.

### Phase 6: Learning Management System Development

- Digital classrooms.
- Learning materials.
- Assignments and submissions.
- Online quizzes.
- Grading and feedback.
- Student progress tracking.

### Phase 7: Integration and Testing

- Integrate all three systems.
- Test authentication and permissions.
- Test database operations.
- Test system functionality.
- Perform security testing.
- Fix bugs and improve performance.

### Phase 8: Deployment and Maintenance

- Register an appropriate domain.
- Configure hosting and database services.
- Enable HTTPS.
- Configure automated backups.
- Train school administrators and teachers.
- Deploy the application.
- Provide ongoing technical support.

## 9. Security and Data Protection

Since the platform will process student information, academic records and potentially children's personal information, security will be a major development priority.

Planned security measures include:

- Secure password hashing.
- Role-based access control.
- HTTPS encryption.
- Input validation.
- Protection against SQL injection and cross-site scripting.
- Secure file uploads.
- Database backups and recovery.
- Login monitoring.
- Audit logs for important administrative activities.
- Restricted parent access to their own children's information.

The implementation will also consider applicable Zimbabwean data protection requirements and appropriate consent procedures for children's information.

## 10. Non-Functional Requirements

| Requirement | Description |
|---|---|
| Performance | Efficient loading and response times |
| Responsiveness | Compatibility with mobile devices, tablets and computers |
| Security | Protection of user accounts and school information |
| Reliability | Stable operation and backup mechanisms |
| Scalability | Ability to support additional users and modules |
| Usability | Simple interfaces for different user categories |
| Maintainability | Organised code and documentation |
| Accessibility | Clear navigation and accessible content |

The platform will also consider low-bandwidth environments and mobile accessibility.

## 11. Expected Deliverables

At the completion of the project, the following deliverables are expected:

1. Official school website.
2. School Information System.
3. Learning Management System.
4. Centralised PostgreSQL database.
5. Authentication and user management.
6. Administrator dashboard.
7. Teacher portal.
8. Parent portal.
9. Student portal.
10. Testing documentation.
11. Technical documentation.
12. Deployment and maintenance instructions.

## 12. Project Success Criteria

The project will be considered successful when:

- The public website provides reliable school information.
- Administrators can register and manage students.
- Teachers can manage classes and attendance.
- Academic results can be recorded and generated.
- Parents can access their children's academic information.
- Students can access learning materials and assignments.
- Teachers can grade student submissions.
- The three components communicate correctly.
- User permissions protect confidential information.
- The application operates reliably on mobile and desktop devices.

## 13. Implementation Strategy

The project will be developed and released incrementally.

| Release | Main Deliverables |
|---|---|
| Release 1 | Website, authentication and administrator dashboard |
| Release 2 | Core School Information System |
| Release 3 | Learning Management System |
| Release 4 | Parent and student portals, integration and deployment |

This approach will make development easier to manage, test and improve.

## 14. Future Enhancements

Possible future features include:

- SMS and email notifications.
- Parent-teacher communication.
- Online admissions applications.
- Advanced academic analytics.
- Automated report generation.
- School event management.
- Mobile application.
- Offline-friendly learning resources.
- Integration with other educational services.

These features will be considered according to the school's actual needs.

## 15. Project Vision

The long-term vision is to establish a unified digital environment for Thorncroft Park Primary School.

The platform will connect school administration, teachers, parents and students through one centralised system.

By integrating school information management and digital learning, the project aims to improve administrative efficiency, academic organisation, communication and access to educational resources.

**The goal is not simply to create a school website, but to develop a complete digital platform that can support the school's everyday operations and future growth.**

---

**Project:** Thorncroft Park Primary School Digital Platform  
**Development Status:** Planning & Requirements Gathering  
**Documentation:** README.md  
**Year:** 2026

*Note: School-specific information, branding, policies, contact details and operational requirements must be verified with the school before implementation or public release.*
