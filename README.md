# FitFlow Redesign

FitFlow is a fitness application redesign focused on personalized
workouts, nutrition tracking, progress monitoring, and community
engagement.

## Technology Stack

| Component | Technology |
|---|---|
| Frontend | Flutter (Dart) |
| Main Backend | Node.js + NestJS |
| AI Microservice | Python + FastAPI |
| Database | PostgreSQL |
| Authentication | Firebase Authentication |
| Cache | Redis |
| Real-Time Communication | WebSockets |

## Key Features

- AI-powered personalized workout plans
- Nutrition tracking and recommendations
- Progress monitoring
- Fitness challenges and community features
- Real-time updates and notifications
- Secure user authentication

## System Architecture

The Flutter frontend communicates with the NestJS backend through
REST APIs and WebSockets. The backend manages application logic
and communicates with PostgreSQL, Redis, Firebase Authentication,
and the Python/FastAPI AI microservice.

## Repository Structure

```text
fitflow-redesign/
│
├── frontend/
├── backend/
├── ai-service/
├── docs/
│   ├── technology-comparison.md
│   ├── weighted-matrix.md
│   ├── architecture.md
│   └── ADR-001.md
│
├── README.md
└── .gitignore
