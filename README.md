Voice Assistant
This is a simple voice assistant program created using Python. The program allows users to interact with the assistant using voice commands to perform various tasks such as retrieving information from Wikipedia, opening web browsers, playing music, checking the time, and more.

Features
Voice Recognition: The assistant uses the speech_recognition library to recognize voice commands spoken by the user.
Text-to-Speech: Utilizes the pyttsx3 library to convert text responses into spoken words.
Wikipedia Search: Users can ask the assistant to search for information on Wikipedia by providing a query.
Web Browsing: The assistant can open YouTube and Google based on user commands.
Music Playback: Users can ask the assistant to play music from a specified directory.
Time Reporting: The assistant can tell the current time.
Requirements
Python 3.x
pyttsx3 library
speech_recognition library
wikipedia library
Usage
Clone the repository to your local machine.

Make sure you have Python installed.

Install the required libraries using pip:

Copy code
pip install pyttsx3 speech_recognition wikipedia
Run the voice_assistant.py file:

Copy code
python voice_assistant.py
Once the assistant is running, you can speak commands to interact with it.

Supported Commands
"Wikipedia [query]": Searches Wikipedia for the specified query.
"Open YouTube": Opens YouTube in the default web browser.
"Open Google": Opens Google in the default web browser.
"Play music": Plays music from a predefined directory.
"The time": Reports the current time.
"Open code": Opens a specified directory (codepath).
Author
Kasula Devika
