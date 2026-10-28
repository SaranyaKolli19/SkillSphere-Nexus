# SkillSphere Nexus

**Enterprise Learning, Certification & Career Development Management Platform**

SkillSphere Nexus is a full-stack enterprise learning platform designed to manage employee profiles, skills, assessments, certifications, and career development in one centralized system.

## Project Overview

The main goal of this project is to help organizations manage employee competencies, track learning progress, monitor certifications, and support professional development.

## Project Objectives

- Manage employee profiles and professional skills.
- Maintain a centralized skill catalog.
- Assess employee skills and record assessment scores.
- Track certifications, issue dates, and expiry dates.
- Map employee skills to job roles and competency requirements.
- Provide dashboards and reports for workforce development.

## Technologies Used

## Technologies Used
| S.No. | Technology | Version | Purpose |
|---:|---|---|---|
| 1 | Angular | 20 | Frontend development and user interface |
| 2 | TypeScript | Compatible with Angular 20 | Frontend application logic |
| 3 | HTML5 | — | Structure of web pages |
| 4 | CSS3 | — | Styling and responsive layouts |
| 5 | Java | 25 | Backend programming |
| 6 | Spring Boot | 4 | Backend development and REST APIs |
| 7 | Spring Data JPA | Compatible with Spring Boot 4 | Database access and persistence |
| 8 | Hibernate | Managed by Spring Boot dependencies | Object-relational mapping (ORM) |
| 9 | PostgreSQL | 18 | Relational database management |
| 10 | Redis | Planned | Caching and performance optimization |
| 11 | Apache Kafka | Planned | Event-driven communication |
| 12 | Keycloak | Planned | Authentication and authorization |
| 13 | Microservices Architecture | Planned | Separation of application modules into independent services |
| 14 | Git | — | Version control |
| 15 | GitHub | — | Source code hosting and collaboration |
| 16 | Postman | — | REST API testing |
| 17 | IntelliJ IDEA | — | Application development environment |


**Note:** Verify the installed versions before publishing. Redis, Kafka, Keycloak, and microservices are marked as planned and should only be described as implemented after integration.

Note: Redis, Kafka, Keycloak, and the microservices architecture are planned technologies until they are integrated into the application.

## Key Features

### 1. Employee Profile Management

- Create and manage employee profiles.
- Maintain employee names, email addresses, departments, and job roles.
- Associate employees with skills, assessments, and certifications.

### 2. Skill Catalog and Competency Mapping

- Maintain a centralized catalog of technical and professional skills.
- Assign skills to employees.
- Track employee proficiency levels.
- Map skills to job roles and competency requirements.

### 3. Skill Assessment and Scoring

- Conduct employee skill assessments.
- Calculate and store assessment scores.
- Record pass and fail results.
- Maintain assessment history.

### 4. Certification Tracking

- Maintain employee certification records.
- Store certification names, issuing organizations, and issue dates.
- Track certification expiry dates.
- Identify valid, expiring, and expired certifications.
- Planned feature: automatically generate a certification record after an employee passes an eligible assessment.

### 5. Training and Career Development

- Organize employee training activities.
- Track learning progress.
- Support career development planning.
- Identify skills that employees need to improve.

### 6. Dashboard and Reporting

- Display employee and skill statistics.
- Monitor assessment results.
- Track certification status.
- Provide insights into workforce skills and learning progress.

## System Architecture

The planned application architecture consists of the following layers:

| Layer | Technology | Responsibility |
|---|---|---|
| Frontend | Angular 20 | User interface |
| Backend | Java 25, Spring Boot 4 | Business logic and REST APIs |
| Database | PostgreSQL | Persistent application data |
| Caching | Redis | Faster access to frequently used data |
| Messaging | Apache Kafka | Asynchronous service communication |
| Identity Management | Keycloak | Authentication and authorization |

The initial application follows a frontend–backend–database architecture, with additional enterprise components planned for future development.

## Getting Started

### Prerequisites

Install the following software:

- Java Development Kit (JDK) 25
- Node.js and npm
- Angular CLI 20
- PostgreSQL
- IntelliJ IDEA
- Git

### Step 1: Clone the Repository

```bash
git clone https://github.com/SaranyaKolli19/SkillSphere-Nexus.git
cd SkillSphere-Nexus
```

### Step 2: Configure the Database

Create a PostgreSQL database named `skillsphere_db`.

Configure the database URL, username, and password in the backend configuration file, such as `application.properties`.

Do not commit database passwords or other sensitive credentials to GitHub.

### Step 3: Run the Backend

Open a terminal in the backend directory containing `pom.xml`.

If the project includes the Maven Wrapper, run this command in Windows PowerShell:

```powershell
.\mvnw.cmd spring-boot:run
```

Alternatively, if Maven is installed:

```bash
mvn spring-boot:run
```

The backend should be accessible at `http://localhost:8080` if configured to use the default port.

### Step 4: Run the Frontend

Open another terminal in the Angular frontend directory containing `package.json`.

Install dependencies:

```bash
npm install
```

Start the application using the configured npm script:

```bash
npm start
```

If no `start` script exists, use:

```bash
npx ng serve
```

Open `http://localhost:4200` in your browser.

Note: Adjust the commands and directory paths to match the actual repository structure.

## Testing

The application can be tested using Postman and the browser.

- Test employee management APIs.
- Verify skill creation and employee-skill mapping.
- Test assessment scoring and results.
- Verify certification generation after a passing assessment.
- Check certification expiry tracking.
- Verify that frontend data is saved to PostgreSQL.

## Development Roadmap

- [ ] Complete employee profile management.
- [ ] Complete skill catalog and competency mapping.
- [ ] Implement assessment scoring and history.
- [ ] Implement automatic certification generation.
- [ ] Connect the dashboard to live backend data.
- [ ] Complete certification expiry tracking.
- [ ] Develop training and career development modules.
- [ ] Add reporting and analytics.
- [ ] Integrate Redis, Kafka, and Keycloak.
- [ ] Implement the planned microservices architecture.
- [ ] Deploy the application.

## Project Information

| Field | Details |
|---|---|
| Project Name | SkillSphere Nexus |
| Project Type | Full-Stack Web Application |
| Domain | Enterprise Learning and Workforce Development |
| Frontend | Angular 20 |
| Backend | Java 25 and Spring Boot 4 |
| Database | PostgreSQL |
| Repository | [GitHub - SkillSphere Nexus](https://github.com/SaranyaKolli19/SkillSphere-Nexus) |

## Future Enhancements

- Role-based access control.
- Advanced learning analytics.
- Automated certification workflows.
- Improved competency gap analysis.
- Cloud deployment and scalability.

## License

A suitable open-source license can be added once the project's licensing and reuse terms have been decided.
