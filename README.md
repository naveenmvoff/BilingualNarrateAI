# BilingualNarrateAI

**BilingualNarrateAI** is a Flask-based bilingual story narration platform, supporting both English and Tamil. It offers AI-generated storytelling capabilities and speech synthesis, all accessible via a simple frontend interface. This repository includes a modular backend built with Flask, and a static HTML frontend for user interaction.


## Features

- Story generation in English and Tamil
- Text-to-speech narration using AI
- Simple and responsive web interface
- Modular structure for easy development


## Project Structure

```text
├── frontend/
│   └── index.html          # Frontend interface
├── story-backend/
│   ├── app.py              # Main Flask application
│   ├── audio.py            # Audio processing logic (text-to-speech)
│   ├── requirements.txt    # Backend dependencies
│   ├── static/             # Static files (e.g., audio output)
│   ├── wsgi.py             # WSGI entry point for production
│   ├── .env                # Environment variables (not committed)
│   ├── Procfile            # Deployment configuration (Heroku compatibility)
│   └── nixpacks.toml       # Nixpacks container configuration
├── .gitignore              # Git ignore rules
└── requirements.txt        # Project-wide Python dependencies
```

## Application Flow Diagram 
![BilingualNarrateAI - Application Flow Diagram](https://github.com/user-attachments/assets/0331005e-871e-4643-8054-f3e40226c5ef)

## Getting Started

### Prerequisites

- Python 3.7 or above
- pip (Python package manager)

### Installation

Clone the repository:
```python
git clone https://github.com/naveenmvoff/BilingualNarrateAI.git
cd BilingualNarrateAI
```

(Optional but recommended) Create a virtual environment:
``` python
python -m venv venv
source venv\Scripts\activate  #mac venv/bin/activate  
```

Install dependencies:
```python
pip install -r requirements.txt
```

Run the backend server:
```python
cd story-backend
python app.py
```

Open the frontend:
```python
frontend/index.html
```
