Dealership Review Platform
Project Overview
The Dealership Review Platform is a comprehensive web application designed to enable users to view car dealers, read and submit reviews, and manage user authentication. This project leverages a full-stack approach, incorporating both frontend and backend technologies to deliver a seamless user experience.

Features
User Authentication: Secure user registration and login using Django's built-in authentication system.
Dealer Listings: View a list of car dealers with detailed information.
Review Management: Submit and view reviews for specific dealers.
Sentiment Analysis: Analyze the sentiment of reviews using a sentiment analysis service deployed on IBM Cloud Code Engine.
Architecture
The project is divided into several components, each responsible for specific functionalities:

Frontend
React: A JavaScript library for building user interfaces. It handles the rendering of dynamic components and ensures a responsive user experience.
Backend
Django: A high-level Python web framework that handles server-side logic, user authentication, and data management.
Node.js: A JavaScript runtime used to implement backend microservices for managing dealers and reviews.
MongoDB: A NoSQL database used to store dealer and review data, ensuring efficient and scalable data management.
Docker: Containerization technology used to package the Node.js microservices and MongoDB, ensuring consistent environments across development, testing, and production.
Deployment
IBM Cloud Code Engine: Used to deploy the sentiment analysis service, providing scalable and managed cloud infrastructure.
Kubernetes: An orchestration platform used to deploy and manage the Docker containers, ensuring robust and scalable deployment.
CI/CD: Continuous Integration and Continuous Delivery pipelines are integrated to automate testing, building, and deployment processes, ensuring a smooth and efficient workflow.
Setup and Installation
Prerequisites
Docker
Kubernetes
IBM Cloud account
Python (with pip)
Node.js (with npm)
