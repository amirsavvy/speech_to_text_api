# Speech to Text Conversion API

The application has following technolgies:
Python / Django for server side processing 
RecorderJS for audio recording


# Process
1- Regsiter / Login to the app with unique username and 6 digits password
2- On speech to text conversion screen, record whatever you want
3- then stop the audio
4- this audio will be sent to the server using jQuery AJAX
5- On server side, using SpeechRecognition, pyaudio, ffmpy this audio will be converted into text and will be saved into the Database

