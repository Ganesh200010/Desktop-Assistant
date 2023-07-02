<p align="left">

<img src="https://img.shields.io/badge/Python-3.x-blue.svg?logo=python&logoColor=white">
<img src="https://img.shields.io/badge/Apache-2.0-green.svg?logo=Apache&logoColor=white">
<img src="https://img.shields.io/badge/speech-recorgination-green.svg?logo=&logoColor=white">



</p>

# Desktop-Assistant


## What is a Desktop Assistant?
A Desktop Assistant helps with time and daily management of meetings correspondence and note taking. The role of personal assistant can be varied such as taking notes, opening apps , browsing etc. Upon a user's choice, it would share jokes and facts, manage downloads, sing songs, and talk, among other functions.

 

## Working:
In this Project, A Desktop assistant is designed using python and is customize for personal use. For the assistant to speak “Microsoft Speech API” is used. After taking input from the user, the audio input is converted from “Speech-to-Text” using “Google Speech Recognition API” and basic commands are executed using different python functions and programs.

 

## Packages Used in the program:
- Pyttsx3
- Speech Recognition
- Wikipedia
- Web browser
- Datetime
- OS
- Time
   

## ****Packages Required to be installed:****

# 1. Pyttsx3:
pyttsx3 is a text-to-speech conversion library in Python. An application invokes the pyttsx3.init() factory function to get a reference ta pyttsx3. Engine instance is a very easy to use tool which converts the entered text into speech.The pyttsx3 module supports two voices first is female and the second is male which is provided by “sapi5” for windows.
It supports three TTS engines :

- sapi5 – SAPI5 on Windows
- nsss – NSSpeechSynthesizer on Mac OS X
- espeak – eSpeak on every other platform

## Installation:
To install the pyttsx3 module, first, you have to open the terminal and write:

    pip install pyttsx3
For more information :
https://pypi.org/project/pyttsx3

# 2. Speech Recognition:

Speech Recognition is a library for performing speech recognition, with support for several engines and APIs, online and offline.From theselibraries, we will be working with SpeechRecognition library because of it’s low barrier to entry and it’s compatibility with much availablespeech recognition APIs.

## Installation:
We can install SpeechRecogntion library by running the following line in our terminal window:

## pip install SpeechRecognition
Note : For the speechrecognition to work pyaudio is to be installed

## For more information :
https://pypi.org/project/SpeechRecognition/

# 3. Pyaudio:
PyAudio provides Python bindings for PortAudio, the cross-platform audio I/O library. With PyAudio, you can easily use Python to play andrecord audio on a variety of platforms.

## Installation:
We can install PyAudio library by running the following line in our terminal window:
    
    pip  install pyaudio 
or

    pip install pipwin
    pipwin install pyaudio

## For more information :

https://pypi.org/project/PyAudio/

# 4. Wikipedia:
Wikipedia is a multilingual online encyclopedia created and maintained as an open collaboration project by a community of volunteer editorsusing a wiki-based editing system.

## Installation:
In order to extract data from Wikipedia, we must first install the Python Wikipedia library, which wraps the official Wikipedia API. This can be done by entering the command below in your command prompt or terminal:

    pip install wikipedia
## For more information :
https://pypi.org/project/wikipedia/


# Voice-Assistant

## Requirements of workspace to run the program

## Installing libraries

1.* To give commands and perform tasks.
  
      pip install speechRecognition 

 2.* This module is used to access camera for capturing images.

      pip install opencv-python 
3.* This library helps System to speak ask which task to perform from the user.

      pip install PyAudio 
4.* To make System take screenshots and save easily

      pip install Pillow

## What can a system Perform

- Ask time and day
- Ask to open google,brave,youtube,stack overflow
- Take screenshot of current screen
- Record your voice
- Open calender and look into the calender of any year you desire
- Generate a new password for you
  etc

## Some further details regarding the system that you may explore and test.

The  <code>_**r.pause_threshold**_</code>  argument increases the duration to wait for the assistance in the  <code>_**takeCommand()**_</code>  method so that it won't stop listening if you accept a little break, whether you wish to or not. In other words, the longer you may delay after issuing a command, the higher the pause_threshold.

Another parameter called r.energy_threshold is also utilised in conjunction with it; as its value increases, it reduces the sensitivity of its input. More shouting is required to communicate directives to the system the higher the energy_threshold.
