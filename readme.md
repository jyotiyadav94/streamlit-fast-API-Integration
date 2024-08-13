## Machine Learning Model Deployment with FastAPI, Streamlit, and Docker

### Overview
This project demonstrates how to build and deploy a web application leveraging machine learning using FastAPI, Streamlit, and Docker. It features a backend service built with FastAPI for handling model predictions and a frontend service using Streamlit for user interaction. Docker is employed to containerize these components, and Docker Compose orchestrates their deployment.

### Project Structure

```plaintext
backend/
│
├── main.py              # FastAPI app that serves the machine learning model
├── model_preprocessing.py # Script to train and save a simple RandomForest model
└── Dockerfile            # Defines the backend Docker image
│
frontend/
│
├── streamlit_app.py      # Streamlit app for user input and prediction display
└── Dockerfile            # Defines the frontend Docker image
│
docker-compose.yml        # Defines and manages multi-container Docker applications
```

Credits : https://medium.com/latinxinai/fastapi-and-streamlit-app-with-docker-compose-e4d18d78d61d
