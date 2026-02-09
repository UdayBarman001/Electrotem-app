# My Fullstack Application

## Description
A fullstack application with Spring Boot backend and React frontend.

## Tech Stack
- **Backend**: Spring Boot (Java)
- **Frontend**: React
- **Database**: PostgreSql

## Prerequisites
- Java 17+
- Node.js 18+
- Maven
- [Database if applicable]

## Setup Instructions

### Backend Setup (IntelliJ IDEA)
1. Open IntelliJ IDEA
2. Open the `backend` folder as a project
3. Wait for Maven to download dependencies
4. Configure `application.properties` with your database credentials
5. Run the Spring Boot application
6. Backend runs on: http://localhost:8080

### Frontend Setup (VS Code)
1. Open VS Code
2. Open the `frontend` folder
3. Open terminal in VS Code
4. Run: `npm install`
5. Create `.env` file with: `REACT_APP_API_URL=http://localhost:8080/api`
6. Run: `npm start`
7. Frontend runs on: http://localhost:3000

## Running the Application
1. Start backend first (IntelliJ)
2. Then start frontend (VS Code)
3. Access app at http://localhost:3000