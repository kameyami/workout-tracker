# Workout Tracker Microservice

# Overview
This microservice allows users to record and retrieve workout sessions.  
Implemented using **Python + Flask**.

---

# API Specification

# **POST /workouts**
- **Description**: Add a new workout record.
- **Request Body (JSON)**:
```json
{
  "exercise": "Running",
  "duration": 30
}

**Response:**
{
  "message": "Workout added",
  "workout": {
    "exercise": "Running",
    "duration": 30
  }
}

**GET /workouts

Description: Retrieve all recorded workouts.
Response:**

[
  {
    "exercise": "Running",
    "duration": 30
  }
]


**Communication Contract

Protocol: HTTP
Data Format: JSON
Endpoints:

POST /workouts
GET /workouts**

**UML Sequence Diagram**
<img width="3371" height="2268" alt="image" src="https://github.com/user-attachments/assets/095340ee-ce5d-4997-83fc-135576dcd52c" />


**How to Run**

Install dependencies:
pip install flask requests

Start the service:
python workout_service.py

Run the test program:
python test_workout_service.py


**Team Contributions**

Ikumi Kameyama: Implemented Workout Tracker microservice, wrote test program, created UML diagram.


**Demo Video**

[Link or file name: workout_service_demo.mp4]
