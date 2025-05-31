# Favorite Songs Manager

This repository contains a **Spring Boot backend API** and a **REACT frontend**, containerized with Docker for easy development and deployment.

---

## Features
- Add songs with details like title, artist, and album.
- View the list of all your favorite songs.
- Remove or update songs from your list.

## Technologies Used

- Backend: Java, Spring Boot, H2 database
- Frontend: React
- Web Server: Nginx (serving static React build)
- Containerization: Docker, Docker Compose

---

## Run the Application with Docker Compose
Ensure Docker and Docker Compose is installed.

1. Clone the repository:
```bash
   git clone https://github.com/marissaaragon/music-tracker.git
   cd music-tracker
```
2. Build and Run the Application:
```bash
   docker compose up --build
```
3. Access the Application:

Frontend: http://localhost:3000/
Backend: http://localhost:8080

## Notes
- To stop the application, press Ctrl + C in the terminal where Docker Compose is running, then run:
```bash
   docker compose down
```
- The backend uses an in-memory H2 database. All data will be lost when the app stops.


  
