# Emotion Detection System using Watson NLP

A Python-based web application that leverages the **IBM Watson NLP Library** to analyze emotions in text. This project provides a RESTful interface using **Flask** to process user input and return emotional insights.

<img width="809" height="525" alt="Image" src="https://github.com/user-attachments/assets/8219fcf9-a1cb-4595-ade4-95b013948c98" />
<img width="1085" height="496" alt="Image" src="https://github.com/user-attachments/assets/6dc68918-e17d-4b46-a4bb-1366fd4ad8cb" />

## 📝 Project Description
This application was developed as the Capstone Project for the "IBM Developing AI Applications with Python and Flask Certificate." The system takes a text string as input and analyzes it to provide scores for five key emotions:
* **Anger**
* **Disgust**
* **Fear**
* **Joy**
* **Sadness**

The application also identifies the **Dominant Emotion**, providing a clear summary of the sentiment expressed in the text.

## 🚀 Key Features
- **Real-time Analysis:** Instant emotion scoring via a web interface.
- **Robust Error Handling:** Specifically manages blank or invalid inputs (HTTP 400) to ensure system stability.
- **Clean Architecture:** Modular package design with a clear separation of concerns between the logic and the server.
- **High Quality Standards:** - Verified through **Unit Testing**.
    - Achieved a **10/10 Pylint score** for static code analysis.

## 🛠 Technology Stack
- **Language:** Python 3.11
- **Web Framework:** Flask
- **API:** IBM Watson NLP Runtime Service
- **Testing:** Unittest
- **Formatting & Linting:** Pylint (PEP 8 compliant)

## 📦 Installation & Setup
1. Clone the repository:
   ```bash
   git clone <Your-GitHub-Repo-URL>
