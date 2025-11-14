# AI-WebApp-Using-MERN-Python

A full-stack web application integrating AI capabilities using the MERN stack (MongoDB, Express, React, Node.js) and Python. This repository showcases deploying a machine learning model in a web application with seamless communication between the frontend, backend, and AI model server.

![WEBMPy](https://images.ctfassets.net/93e8slakzebf/1QMVZT7y199XopMReqgqd7/1294cd94304f2c73f2d5ec79e0b4bc6c/web-app-development.png?fm=webp&w=1920&q=75)

# Introduction
Integrating artificial intelligence (AI) into web applications has opened new borders in creating intelligent, responsive, and user-centric platforms. This repository, AI-WebApp-Using-MERN-Python, combines the power of modern web development with AI to deliver an innovative solution. Leveraging the MERN stack—MongoDB, Express.js, React.js, and Node.js- the application ensures a robust and scalable foundation for the front-end and back-end infrastructure. Additionally, Python plays a crucial role in embedding AI capabilities, thanks to its rich ecosystem of libraries and frameworks, such as TensorFlow, Scikit-learn, or PyTorch. The AI component enhances the application by performing tasks such as predictive analysis, intelligent recommendations, or data-driven automation, enabling the platform to adapt dynamically to user needs. With MongoDB as the database, the application can efficiently store and process large datasets, while React.js delivers an interactive and responsive user interface. Node.js and Express.js provide a seamless backend experience, ensuring smooth API interactions and communication between the AI models and the web app. This project demonstrates the synergy between AI and web development by bridging advanced computational models with real-world usability. It illustrates how technology stacks can be integrated to build innovative solutions that solve complex situations and deliver exceptional user experiences.

![MPy](https://miro.medium.com/v2/resize:fit:1400/1*jH83DONf_6s0DJS53QZQZA.png)


# 🚀  Features
✅ AI Model Integration

Python FastAPI model server

Ensemble of XGBoost, CatBoost, LightGBM

Real-time predictions with confidence scores

Model metadata exposure (/model-info)

✅ Modular MERN Stack

Express backend with fully modular routes

MongoDB prediction logging

Input validation with Joi

✅ React Frontend (Component-Based)

Clean responsive UI

Prediction form

Confidence bars

Model votes visualizer

✅ API Communication

Backend securely communicates with the AI server

Backend acts as middleware for the frontend

Centralized error handling

✅ Containerization

Fully Dockerized

docker-compose.yml orchestrates all services

MongoDB volume for persistence

🎨 Responsive & Interactive UI

Clean React interface

Real-time validation

Probability bars + class color coding

# 📘 Example Use Case
Iris Flower Classifier (Built-in Example)

Frontend (React)
User enters sepal/petal measurements.

Backend (Express)
Validates input → forwards to AI server → logs to database.

AI Server (FastAPI)
Computes prediction using ensemble ML models.

Database (MongoDB)
Stores predictions for history & analytics dashboards.

# Technologies Used

    Frontend: React.js, Axios
    Backend: Node.js, Express.js, Mongoose
    Database: MongoDB
    AI Model: Python, Flask/FastAPI, scikit-learn, TensorFlow, or PyTorch
    Containerization: Docker, Docker Compose

# Getting Started

    Clone the repository:

git clone https://github.com/MohammadMaftoun/AI-WebApp-Using-MERN-Python
cd AI-WebApp-MERN-Using-Python

# Follow the setup instructions for each component:

    Backend Setup
    Frontend Setup
    AI Model Setup

# Start the services:

    docker-compose up-- build

    Open the web app in your browser at http://localhost

# Contributing

Contributions are welcome! Please fork this repository and submit a pull request for improvements or features.
