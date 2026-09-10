# FitFlow System Architecture

## Architecture Components

- Flutter Frontend
- Node.js + NestJS Backend
- Python + FastAPI AI Microservice
- PostgreSQL Database
- Firebase Authentication
- Redis Cache
- WebSocket Real-Time Layer

## Main Data Flows

### Personalized Workout

User → Flutter → NestJS → AI Microservice → NestJS → PostgreSQL → Flutter

### Social Sharing

User → Flutter → NestJS → PostgreSQL → WebSocket → Other Users

### Nutrition Tracking

User → Flutter → NestJS → AI Service → PostgreSQL → Flutter

## Security

Firebase Authentication is used for user authentication.
HTTPS is used for communication, and backend APIs validate
and authorize requests.

## Scalability

NestJS provides a scalable backend structure. Redis reduces
repeated database requests, while the AI microservice can be
scaled independently.
