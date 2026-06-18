## AI DEMENTIA CARE WITH MULTIMODAL INTERACTIONS AND SMART REMINDERS

### Project Introduction

DementiaCare AI is an AI-driven healthcare platform designed to support dementia patients and their caregivers through intelligent monitoring, cognitive assistance, and safety-focused features.

Dementia affects memory, reasoning, communication, and daily living abilities. Managing these challenges often requires continuous support from family members and healthcare professionals. DementiaCare AI addresses this need by combining Machine Learning, Deep Learning, Computer Vision, and Natural Language Processing into a unified healthcare assistance system.

The platform provides dementia risk assessment, family member recognition, conversational support, cognitive training, medication reminders, and real-time location monitoring to enhance patient well-being and caregiver awareness.

---

## Core Functionalities

### AI-Based Dementia Assessment

The system evaluates patient symptoms, behavioral indicators, and cognitive assessment results to estimate dementia risk and severity.

**Technology Used:** Random Forest Classifier

#### Features

- Dementia risk prediction
- Cognitive health evaluation
- Symptom analysis
- Severity level estimation
- Early intervention support

---

### Family Recognition System

An AI-powered facial recognition module helps patients identify familiar family members and caregivers.

**Technology Used:** Convolutional Neural Network (CNN)

#### Features

- Face detection through webcam input
- Relative recognition
- Relationship identification
- Familiarity assistance
- Reduced patient confusion

---

### Virtual AI Assistant

A conversational AI assistant provides healthcare-related support and guidance through natural language interaction.

**Technology Used:** BERT-Based NLP Model

#### Features

- Interactive conversations
- Medication guidance
- Appointment assistance
- Daily activity support
- General health-related information

---

### Smart Reminder Management

The platform helps patients maintain regular schedules through automated reminders.

#### Features

- Medicine reminders
- Doctor appointment alerts
- Daily routine notifications
- Personalized scheduling support

---

### Cognitive Enhancement Activities

Interactive activities are provided to encourage memory retention and mental engagement.

#### Features

- Memory exercises
- Attention improvement tasks
- Cognitive performance tracking
- Progress monitoring

---

### Caregiver Monitoring Dashboard

A centralized dashboard allows caregivers to monitor patient health and activities efficiently.

#### Features

- Patient report viewing
- Activity monitoring
- Medication adherence tracking
- Cognitive progress analysis
- Emergency notifications

---

### Patient Safety and Location Tracking

Real-time tracking features improve patient safety and help caregivers respond quickly during emergencies.

#### Features

- GPS location monitoring
- Geofencing support
- Wandering detection
- Emergency alert generation

---

## System Workflow

1. Patient submits symptoms and assessment information.
2. Data is processed and analyzed by the prediction model.
3. Dementia risk level is generated.
4. Facial recognition identifies registered relatives.
5. The AI assistant responds to patient queries.
6. Reminder services manage medications and appointments.
7. GPS tracking monitors patient location.
8. Caregivers access reports and alerts through the dashboard.

---

## Technologies Used

### Programming Language

- Python 3

### Machine Learning

- Scikit-Learn
- NumPy
- Pandas

### Deep Learning

- TensorFlow
- Keras

### Computer Vision

- OpenCV

### Natural Language Processing

- Transformers
- NLTK
- spaCy

### Web Development

- Flask
- HTML
- CSS
- JavaScript

### Database

- MySQL

### APIs

- Google Maps API (Optional)

---

## Project Structure

```text
dementiacare-ai/
│
├── app.py
├── train_model.py
├── train_relative_model.py
│
├── dementia_dataset.xlsx
├── dementia_knowledge.xlsx
│
├── dementia_model.pkl
├── dementia_encoders.pkl
├── relative_face_model.pkl
├── relative_label_encoder.pkl
│
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── dashboard.html
│   └── additional HTML files
│
├── static/
│   ├── assets/
│   │   ├── css/
│   │   ├── js/
│   │   ├── images/
│   │   └── libraries/
│   │
│   ├── accuracy_plot.png
│   ├── feature_importance.png
│   └── memory.mp4
│
├── dataset/
│   └── relatives/
│       └── Training images
│
├── database/
│   └── dementia_care.sql
│
└── README.md
```

---

## Users of the System

### Dementia Patient

- Receives dementia assessment results
- Uses chatbot assistance
- Participates in cognitive exercises
- Receives reminders and notifications

### Caregiver

- Monitors patient activities
- Tracks patient location
- Receives emergency alerts
- Reviews health reports

### Healthcare Professional

- Reviews patient information
- Validates assessment outcomes
- Monitors patient progress
- Supports treatment planning

### Administrator

- Maintains the system
- Updates AI models
- Manages database operations
- Ensures platform security

---

## Future Enhancements

- Mobile application support
- Voice-enabled interactions
- Wearable device integration
- Cloud deployment
- Multilingual chatbot support
- Advanced healthcare analytics
- Real-time health sensor integration

---

## Project Objective

The primary objective of DementiaCare AI is to demonstrate the practical application of Artificial Intelligence in dementia care. The platform aims to improve patient independence, support caregivers with meaningful insights, and promote safer healthcare management through intelligent technologies.

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/DEMENTIA_CARE.git
```

### Install Required Packages

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

---




## Author

### Sree Shankari V

B.Tech – Artificial Intelligence and Data Science

---

## License

This project is intended for academic and research use.
