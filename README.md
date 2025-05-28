 AI-Based Cybersecurity Threat Detection and Prevention System
 (Revolutionizing Cybersecurity with Artificial Intelligence)


 Overview

This project is an intelligent cybersecurity system built using Artificial Intelligence and Machine Learning to *detect, prevent, and respond to cyber threats in real-time*. It includes modules for:

- Intrusion Detection
- Malware Detection
- Anomaly Detection
- Phishing Detection


 Technologies Used

| Category           | Stack                                     |
|--------------------|-------------------------------------------|
| Language           | Python                                    |
| ML Libraries       | Scikit-learn, Joblib                      |
| Backend Framework  | FastAPI                                   |
| Deployment         | Uvicorn, Docker (optional)                |
| Mobile/Desktop App | Flutter                                   |
| Frontend (Web)     | React.js (Planned)                        |
| Database (Planned) | MongoDB / Firebase                        |


 Folder Structure

AI_Cybersecurity_Project/
├── app/
│   ├── models/-Trained ML models (.pkl)
│   ├── routers/ -FastAPI endpoints
│   ├── _init_.py
│   └── main.py/ -FastAPI app entry point
├── requirements.txt/ -All dependencies
├── README.md/ -Project documentation
└── .gitignore


 API Endpoints

| Endpoint              | Description                  |
|-----------------------|------------------------------|
| /predict_intrusion  | Intrusion Detection          |
| /predict_malware    | Malware Detection            |
| /predict_anomaly    | Anomaly Detection            |
| /predict_phishing   | Phishing Detection           |

> All endpoints expect a JSON payload like:
 json
{
  "features": [feature1, feature2, ..., featureN]
}



How to Run

1. Clone the project

git clone https://github.com/yourusername/AI_Cybersecurity_Project.git
cd AI_Cybersecurity_Project

2. Install dependencies

pip install -r requirements.txt

3. Run FastAPI server

uvicorn app.main:app --reload

> Open your browser at http://127.0.0.1:8000/docs for Swagger UI




Future Scope

Full-featured Flutter Mobile/Desktop App

Web Dashboard in React.js

Real-time threat alerting via WebSockets

Cloud deployment with Docker & Nginx

Threat intelligence feeds (e.g., VirusTotal)



Submitted To Project Supervised

Prof.Dr Syed Hammad Sherazi
Email:syedhamad@hu.edu.pk


Final Year Project by:
Mr.Imad Ud Din
Mr.Sayed Salar Ahmad

Department of CS & IT
HAZARA UNIVERSITY MANSEHRA,PAKISTAN



License

MIT License
