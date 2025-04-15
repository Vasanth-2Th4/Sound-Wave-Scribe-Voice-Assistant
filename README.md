# Sound-Wave-Scribe-Voice-Assistant
Developed Sound-Wave-Scribe, an advanced voice assistant powered by AI for real-time speech recognition and natural language processing. It transcribes spoken words into text, integrates with various APIs for enhanced functionalities, and provides seamless voice command execution for daily tasks.

# Voice Assistant Project

This project implements a voice assistant that can perform various tasks, including:

* Getting weather information
* Fetching news headlines
* Telling the current time
* Taking and showing notes
* Finding antonyms and synonyms
* Setting timers
* Managing a calendar
* Sending and receiving emails
* Managing tasks
* Converting currencies
* Performing basic calculations

## Project Structure

The project consists of the following files:

* `main.py`: The main script that handles voice input, processes user queries, and orchestrates the different functionalities.
* `weather.py`: Module responsible for fetching weather information from Bing.
* `news.py`: Module responsible for fetching news headlines from Bing.
* `voice-assis(interface).html`: HTML file providing the user interface with input, microphone, and visual elements.
* `backend.css`: CSS file for styling the HTML interface.
* `mainn.py`: An older version of the `main.py` file, kept for potential reference.

## Dependencies

The project requires the following Python libraries:

* `speech_recognition`
* `pyttsx3`
* `webbrowser`
* `requests`
* `bs4` (BeautifulSoup4)
* `imaplib`
* `smtplib`
* `email`

You can install these dependencies using pip:

```bash
pip install SpeechRecognition pyttsx3 requests beautifulsoup4
