# Docker with Data Conversion  

This project demonstrates how to set up a Dockerized environment for a data conversion application, featuring both a frontend and backend. You can build and run the application using `docker-compose` and Docker commands.  

---

## Prerequisites  

Before starting, ensure the following tools are installed:  
- **Docker**  
- **Docker Compose**  

---

## Setup Instructions  

### 1. Clone the Repository  

Clone the repository to your local machine by running the following commands:  

```bash  
git clone https://github.com/ashish5061/Docker-with-Data-Conversion.git  
cd Docker-with-Data-Conversion  

## Use Docker Compose to build and start the containers:
docker-compose up --build  

## Access the Application
Frontend: http://localhost:3000
Backend: http://localhost:8000

## Stop and Remove Containers
docker-compose down  
