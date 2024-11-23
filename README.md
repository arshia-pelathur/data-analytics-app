# Data Analytics Application

This repository contains the implementation of a Python-based data analytics application, designed and deployed with a complete CI/CD pipeline. The application uses Docker, Minikube, and Jenkins to automate the processes of building, testing, deploying, and monitoring.

## Objective
Develop and deploy a scalable data analytics application with automated CI/CD pipelines for efficient deployment and monitoring.

## Features
- Python-based data analytics application.
- Containerized using Docker.
- Deployed on a Kubernetes cluster using Minikube.
- CI/CD pipeline configured using Jenkins for automation.
- Automated testing with Pytest.

## Technologies Used
- **Version Control:** GitHub
- **Programming Language:** Python
- **Containerization:** Docker
- **Orchestration:** Minikube (Kubernetes)
- **CI/CD Tool:** Jenkins
- **Testing Frameworks:** Pytest

## Repository Structure
├── data                   # Contains sample data files
│   └── sample.csv         # Sample CSV data for the application
├── src                    # Source code for the application
│   ├── app.py             # Flask-based web app
│   ├── analysis.py        # Data analysis logic
│   └── utils.py           # Utility functions
├── tests                  # Unit tests
│   └── test_analysis.py   # Pytest-based test for analysis
├── k8s                    # Kubernetes manifests
│   ├── deployment.yaml    # Kubernetes deployment configuration
│   └── service.yaml       # Kubernetes service configuration
├── Dockerfile             # Dockerfile to containerize the application
├── requirements.txt       # Python dependencies
├── Jenkinsfile            # Jenkins pipeline definition
└── README.md              # Documentation

data-analytics-app/ ├── data # Contains sample data files │ └── sample.csv # Sample CSV data for the application ├── src # Source code for the application │ ├── app.py # Flask-based web app │ ├── analysis.py # Data analysis logic │ └── utils.py # Utility functions ├── tests # Unit tests │ └── test_analysis.py # Pytest-based test for analysis ├── k8s # Kubernetes manifests │ ├── deployment.yaml # Kubernetes deployment configuration │ └── service.yaml # Kubernetes service configuration ├── Dockerfile # Dockerfile to containerize the application ├── requirements.txt # Python dependencies ├── Jenkinsfile # Jenkins pipeline definition └── README.md #

## Setup Instructions

### Prerequisites
- Python (>=3.8)
- Docker
- Minikube
- Jenkins
- Git

### Step 1: Clone the Repository
```bash
git clone https://github.com/arshia-pelathur/data-analytics-app.git
cd data-analytics-app
```
### Step 2: Set up python Environment
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
### Step 3: Run the application
```bash
python src/app.py
```
