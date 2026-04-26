# BridgeBot

BridgeBot is a Python-based backend system developed for real-time sign language gesture recognition and chatbot interaction. The project uses computer vision and hand tracking technologies to detect sign language gestures from webcam input and process them for communication assistance.

The backend is built using Flask and integrates OpenCV and MediaPipe for gesture detection and processing.

---

## Features

- Real-time hand gesture detection
- Sign language recognition system
- Webcam input processing
- AI-assisted gesture interpretation
- Flask backend API
- Lightweight and scalable backend architecture

---

## Tech Stack

### Backend
- Python
- Flask

### AI / Computer Vision
- OpenCV
- MediaPipe

### Additional Libraries
- NumPy

---

## Project Structure

```bash
backend/
│
├── __pycache__/
│
├── asl_converter.py
├── main.py
├── requirements.txt
```

---

## File Description

### `main.py`
Main backend server file responsible for:
- Starting the Flask server
- Handling API routes
- Processing webcam input
- Connecting gesture detection logic

---

### `asl_converter.py`
Contains the core sign language conversion and gesture recognition logic using:
- OpenCV
- MediaPipe
- Hand landmark processing

---

### `requirements.txt`
Stores all required Python dependencies for the project.

Install them using:

```bash
pip install -r requirements.txt
```

---

### `__pycache__/`
Automatically generated Python cache files.

These files are not required for deployment and can be ignored using `.gitignore`.

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/GestureBridge-Chatbot.git
```

### Navigate to the backend folder

```bash
cd GestureBridge-Chatbot/backend
```

---

## Create Virtual Environment

```bash
python -m venv venv
```

---

## Activate Virtual Environment

### Windows

```bash
venv\Scripts\activate
```

### Mac/Linux

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Backend Server

```bash
python main.py
```

---

## Future Improvements

- Sentence-level gesture detection
- Voice output support
- Improved gesture accuracy
- API integration with frontend chatbot
- Real-time translation system
- Database support for chat history

---

## Learning Outcomes

This project helped in understanding:
- Flask backend development
- Computer vision workflows
- Real-time hand tracking
- MediaPipe integration
- Gesture recognition systems
- AI-powered accessibility solutions

---

## License

This project is created for learning and educational purposes.
