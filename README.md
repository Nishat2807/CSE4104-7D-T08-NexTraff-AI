# NexTraff AI

### An AI-Powered Traffic Monitoring and Congestion Analysis System

## 1. Project Overview

NexTraff AI is a web-based AI-powered traffic monitoring and congestion analysis system designed to detect and count vehicles from uploaded traffic videos and estimate traffic congestion levels.

The system uses Artificial Intelligence (AI) and computer vision technology to analyze traffic videos and provide useful information about road traffic conditions. It aims to make traffic monitoring easier, faster, and more organized.

## 2. Problem Statement

Traffic congestion is a common problem that causes delays, fuel wastage, and difficulties in traffic management. Manual traffic monitoring can be time-consuming and inefficient. Counting vehicles manually may also lead to inaccurate results.

NexTraff AI aims to address these problems by introducing an AI-based system that can automatically detect vehicles, count them, and estimate traffic congestion levels from uploaded traffic videos.

## 3. Project Objectives

- To develop a web-based traffic monitoring platform.
- To detect vehicles from uploaded traffic videos.
- To classify detected vehicles using AI technology.
- To automatically count detected vehicles.
- To estimate traffic congestion levels.
- To display analysis results through an interactive dashboard.
- To store previous analysis results for future reference.
- To reduce the time and effort required for manual traffic monitoring.

## 4. Proposed Features

- User Registration and Login.
- Traffic Video Upload.
- AI-Based Vehicle Detection.
- Vehicle Classification.
- Automatic Vehicle Counting.
- Traffic Congestion Estimation (Low, Medium, High).
- Dashboard for displaying analysis results.
- Previous Analysis History.
- Input Validation and Error Handling.
- Responsive User Interface.

## 5. Proposed Technology Stack

| Component | Technology |
|---|---|
| Frontend | React.js |
| Backend | Node.js, Express.js |
| Database | PostgreSQL |
| AI Model | Python, Pretrained YOLO |
| Data Visualization | Chart.js |
| Version Control | Git and GitHub |
| Deployment | Vercel / Render |

## 6. Project Scope

The initial version of NexTraff AI will focus on analyzing uploaded traffic videos. The system will detect and classify vehicles, count detected vehicles, estimate congestion levels, and display analysis results through a dashboard.

Real-time traffic monitoring through live CCTV cameras and automatic traffic signal control are outside the initial project scope. Advanced traffic congestion prediction may be considered as a future improvement.

## 7. User Roles

The system will mainly support two types of users:

**Visitor:**

- View general project information.
- Access registration and login pages.
- Create a new account.

**Registered User:**

- Log in to the system.
- Upload traffic videos.
- Start video analysis.
- View vehicle detection and counting results.
- Check traffic congestion levels.
- View the analysis dashboard.
- Review previous analysis records.
- Log out of the system.

## 8. Future Improvements

- Real-time traffic monitoring using CCTV cameras.
- Advanced traffic congestion prediction.
- Improved vehicle classification.
- More detailed traffic analysis and reporting.
- Additional dashboard visualization features.

## 9. Project Status

**Development in Progress**

This project is being developed as part of the Software Development III (CSE 4104) course.

## 10. System Design

The system design of NexTraff AI defines the overall structure of the application, database organization, user interactions, system workflow, planned API endpoints, and AI integration process.

The following design components have been prepared:

- System Architecture Diagram.
- Entity Relationship (ER) Diagram.
- Updated Use Case Diagram.
- Activity Diagram.
- API Design Document.
- AI Integration Workflow.

These design documents will guide the development and implementation of the project.

### System Architecture

The proposed system follows a modular architecture consisting of four main components:

- **Frontend:** React.js web application for user interaction.
- **Backend:** Node.js and Express.js for handling requests and application logic.
- **Database:** PostgreSQL for storing user information, uploaded video references, and analysis results.
- **AI Service:** Python with a pretrained YOLO model for vehicle detection and classification.

### Database Design

The database is designed to manage users, uploaded videos, traffic analysis records, vehicle counts, and congestion results.

### AI Integration

The project uses a pretrained YOLO object detection model through a Python-based AI service. Uploaded traffic videos are processed to detect and classify vehicles. The system then calculates vehicle counts and estimates congestion levels as Low, Medium, or High.

## 11. API Design

The proposed API endpoints are organized into the following categories:

**Authentication APIs:**

- POST `/api/auth/register`
- POST `/api/auth/login`
- POST `/api/auth/logout`

**User APIs:**

- GET `/api/users/profile`
- PUT `/api/users/profile`

**Video APIs:**

- POST `/api/videos/upload`
- GET `/api/videos/{videoId}`

**AI Analysis APIs:**

- POST `/api/analysis/{videoId}/process`
- GET `/api/analysis/{analysisId}`
- GET `/api/analysis/history`

These endpoints are planned to support user authentication, video uploading, AI-based analysis, and retrieval of previous analysis results.

## 12. Project Documentation

The project documentation includes the System Design Document and related diagrams.

The documentation covers:

- Project Information.
- System Architecture.
- Database Design.
- Use Case Diagram.
- Activity Diagram.
- API Design.
- AI Integration Workflow.
- References.

The documentation files are maintained in the `documentation/` and `diagrams/` folders.

## 13. Repository Structure

The project repository is organized into separate folders for frontend development, backend development, database design, documentation, and system diagrams.

```text
CSE4104-7D-T08-NexTraff-AI/
│
├── frontend/
├── backend/
├── database/
├── documentation/
├── diagrams/
├── README.md
└── .gitignore
```

## 14. Team Information

| Name | Student ID |
|---|---|
| Nishat Tamanna Joly | 11230321320 |
| Raeeq Inteser | 11230321324 |
| Rudro Biswas | 11230321524 |
| Shahriar Rahat | 11230321328 |

**Course:** Software Development III  
**Course Code:** CSE4104  
**Section:** 7D  
**Team Name:** CSE4104-7D-T08  
**Team Leader:** Nishat Tamanna Joly

## 15. Repository

**GitHub Repository:**

https://github.com/Nishat2807/CSE4104-7D-T08-NexTraff-AI

---

**NexTraff AI – Making Traffic Monitoring Smarter.**
