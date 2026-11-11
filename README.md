# Real-Time AI Gym Trainer 🏋️

A real-time AI-powered gym trainer designed to assist users during workouts by tracking body movements and supporting exercise monitoring through computer vision.

## 📌 Project Overview

The Real-Time AI Gym Trainer is a Python-based application that uses pose detection and exercise-specific tracking modules to make workout sessions more interactive. It helps users monitor their exercise movements and access AI-based coaching features.

The project combines computer vision, Python, and AI-powered coaching functionality to create a smart workout assistance system.

## ✨ Key Features

- **Real-Time Pose Detection:** Detects body landmarks to support workout movement tracking.
- **Exercise Tracking:** Includes dedicated modules for:
  - Biceps Curl
  - Squats
  - Push-Ups
  - Lunges
  - Shoulder Press
- **Workout Monitoring:** Supports tracking exercise movements and workout metrics.
- **AI Coaching:** Includes an AI-based coaching module.
- **Voice Features:** Includes text-to-speech and voice pipeline modules.
- **Session Management:** Includes session state and exercise data persistence.

## 🛠️ Technologies Used

- Python
- Computer Vision and Pose Detection
- Streamlit
- AI/ML
- Git and GitHub

## 📂 Project Structure

```text
Real-Time-AI-GYM-Trainer/
│
├── core/
├── detectors/
├── ml_models/
├── services/
│   ├── auth/
│   ├── coaching/
│   ├── config/
│   ├── persistence/
│   ├── state/
│   ├── tracking/
│   ├── ui/
│   └── vision/
│
├── static/
├── main.py
├── requirements.txt
└── README.md
```

## ⚙️ Installation and Setup

**1. Clone the repository**

```bash
git clone https://github.com/MuskanKadyan/Real-Time-AI-GYM-Trainer.git
```

**2. Open the project directory**

```bash
cd Real-Time-AI-GYM-Trainer
```

**3. Create a virtual environment**

```bash
python -m venv .venv
```

**4. Activate the virtual environment (Windows)**

```bash
.venv\Scripts\activate
```

**5. Install the required dependencies**

```bash
pip install -r requirements.txt
```

**6. Configure the required environment variables**

Add your required API credentials to
