Atlas AI – Dockerized Chatbot Application

Atlas AI is a Generative AI chatbot application built with vanilla JavaScript and the Gemini API, deployed on Apache server using Docker on a Linux VM in Azure. This project demonstrates building a cloud-hosted AI chatbot from scratch.

Features

🤖 AI-Powered Chatbot: Interact with the chatbot using natural language, powered by Gemini API

💻 Front-End: Built with HTML, CSS, and JavaScript for a responsive, user-friendly interface

🐳 Containerized Deployment: Dockerized the app for consistent deployment across environments

☁️ Cloud Deployment: Hosted on Azure VM with Linux OS for real-world cloud experience

🚀 Version Control: Docker image pushed to Docker Hub for easy distribution and management

Getting Started

Clone this repository:

git clone [your-repo-link]


Obtain your Gemini API Key and replace it in script.js:

const GOOGLE_API_KEY = "YOUR_API_KEY";


Build and run the Docker container:

docker build -t atlas-ai .  
docker run -p 80:80 atlas-ai

Screenshots

Technologies Used

Docker & Apache Server

Linux (Ubuntu)

Azure VM

HTML, CSS, JavaScript

Gemini API
