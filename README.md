# Python Speech-to-Text

A Python project containing two speech recognition applications that convert spoken audio into text using Google's Speech Recognition service.

## Features

### 1. Streamlit Speech-to-Text App
- Record audio directly through a web interface.
- Select a language: English, Hindi, Malayalam, or Kannada.
- Convert recorded speech into text.
- Display the transcription in the application.
- Download the transcription as a text file.

### 2. Terminal Speech Recognition
- Capture speech through a microphone.
- Adjust for ambient noise.
- Recognize spoken words and print the transcription in the terminal.
- Handle microphone and speech recognition errors.

## Technologies Used

- Python
- Streamlit
- SpeechRecognition
- PyAudio
- Google Speech Recognition

## Project Structure

```text
python-speech-to-text/
├── app.py
├── speechtext.py
├── requirements.txt
├── README.md
└── .gitignore
```

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/python-speech-to-text.git
cd python-speech-to-text
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

## How to Run

### Streamlit Application

```bash
streamlit run app.py
```

Open the local URL displayed in the terminal. Allow microphone access when prompted.

### Terminal Application

```bash
python speechtext.py
```

Ensure your microphone is connected and configured correctly.

## Supported Languages

The Streamlit application includes:

- English
- Hindi
- Malayalam
- Kannada

The terminal application uses Google's default recognition language because no language parameter is specified in its current code.

## Requirements

- Python installed on your computer.
- An internet connection for Google's speech recognition service.
- Microphone access.
- PyAudio installed for the terminal-based application.

## Learning Objectives

- Understand speech recognition using Python.
- Capture and process microphone audio.
- Build interactive applications with Streamlit.
- Convert spoken language into text.
- Handle common speech recognition errors.

## Author

Add your name and GitHub profile here.

## Disclaimer

This project is intended for educational purposes. Recognition accuracy depends on audio quality, language selection, internet connectivity, and service availability.
