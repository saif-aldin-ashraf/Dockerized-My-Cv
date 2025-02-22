# Dockerized-My-Cv
Saif's CV Website This project is a Dockerized personal CV website that showcases my skills, experience, and certifications. It includes a Flask backend, a MySQL database, and a static frontend served by Nginx. The entire application is containerized using Docker and can be easily deployed using Docker Compose.


## Features
Frontend: A static HTML/CSS website hosted using Nginx.

Backend: A Flask API that handles dynamic functionality (e.g., visitor count).

Database: A MySQL database to store and manage data (e.g., visitor count).

Dockerized: The entire application is containerized for easy deployment and scalability.

Docker Compose: Simplifies the setup and running of the application with a single command.


## Technologies Used
Frontend: HTML, CSS, JavaScript, Nginx.

Backend: Flask (Python), MySQL.

Database: MySQL.

Containerization: Docker, Docker Compose.

![image](https://github.com/user-attachments/assets/f86da8b6-4f35-4860-9c9c-69c02e9cf017)


## Run the application using Docker Compose:

`docker-compose up -d`


## Access the website:

`http://localhost:8050`

#### Test the backend API:

`curl http://localhost:5001/api/visitor-count`



![Screenshot 2025-02-22 184215](https://github.com/user-attachments/assets/cbefea68-c4ea-46e8-b667-a81c82e81166)



![Screenshot 2025-02-22 190101](https://github.com/user-attachments/assets/6bf3c90e-b59a-407c-b72f-4703a3a7cd70)


