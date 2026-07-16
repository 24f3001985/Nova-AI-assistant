# Nova AI - Python Voice Assistant

## Overview

Nova AI is a Python-based voice assistant that performs voice-controlled tasks using speech recognition and artificial intelligence. It listens for the wake word **"Nova"**, processes voice commands, and responds using text-to-speech. The assistant can open websites, play music, fetch the latest news, and answer general questions using the OpenAI API.

---

## Features

* Voice-controlled virtual assistant
* Wake word detection ("Nova")
* Speech-to-Text using SpeechRecognition
* Text-to-Speech using gTTS and Pygame
* Open popular websites (Google, YouTube, Facebook, LinkedIn)
* Play songs from a custom music library
* Fetch the latest news headlines using NewsAPI
* AI-powered responses using the OpenAI API

---

## Technologies Used

* Python
* SpeechRecognition
* PyAudio
* gTTS
* Pygame
* OpenAI API
* Requests
* Webbrowser

---


## Installation

1. Clone the repository:

```bash
git clone https://github.com/24f3001985/Nova-AI-assistant.git
```

2. Move into the project directory:

```bash
cd Nova-AI
```

3. Create a virtual environment:

```bash
python -m venv venv
```

4. Activate the virtual environment.

Windows:

```bash
venv\Scripts\activate
```

Linux/macOS:

```bash
source venv/bin/activate
```

5. Install the required packages:

```bash
pip install -r requirements.txt
```

6. Add your OpenAI API key and NewsAPI key in the project before running the application.

---

## How to Run

```bash
python main.py
```

Say the wake word **"Nova"**, then speak your command.

---

## Example Commands

* Open Google
* Open YouTube
* Open Facebook
* Open LinkedIn
* Play <song name>
* News
* Ask any general question

---

## Future Improvements

* GUI interface
* Weather updates
* Email automation
* Calendar integration
* Better wake-word detection
* Voice customization
* Chat history

---

