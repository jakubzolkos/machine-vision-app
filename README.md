## Object Recognizer App

# How It Works
An android application that uses a phone camera to recognize objects in real-time and uses text-to-speech engine to speak it out loudly. The application utilizes a private Flask server that receives Base64 image strings as POST request from the app once every few seconds and sends it for analysis to Google Cloud Vision. Then, it returns a string containing the most likely prediction and its relative position on the screen (e.g to your right, to your center).  

# Plugins and Libraries Used
- Flask
- OkHTTP
