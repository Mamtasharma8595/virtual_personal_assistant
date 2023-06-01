# Voice Assistant

This Python script acts as a voice assistant that performs various tasks based on user commands. It utilizes speech recognition, text-to-speech conversion, and integrates with several APIs for features like retrieving news, weather information, searching on Google and Wikipedia, sending emails and WhatsApp messages, playing videos on YouTube, and more.

## Requirements

The script requires the following Python libraries to be installed:
- requests
- pyttsx3
- speech_recognition
- decouple
- datetime
- pywhatkit
- wikipedia
- email
- smtplib

Make sure to set up the necessary API keys and credentials for email and other services by creating a `.env` file and populating it accordingly.

## Usage

1. Run the script `voice_assistant.py` in a Python environment.
2. The assistant will greet the user based on the time of the day.
3. Speak out commands or questions, and the assistant will perform the corresponding tasks or provide the requested information.
4. You can interact with the assistant using voice commands for various functionalities, such as opening applications, searching the web, retrieving news, sending messages, and more.
5. To exit the assistant, say "exit" or "stop."

## Functionality

The script provides the following functionality:
- Opening applications like Notepad, Discord, Command Prompt, and Camera.
- Retrieving IP address information.
- Searching and summarizing information from Wikipedia.
- Playing videos on YouTube.
- Searching on Google.
- Sending WhatsApp messages.
- Sending emails.
- Getting random jokes and advice.
- Retrieving trending movies.
- Reading out and displaying the latest news headlines.
- Getting weather reports.

