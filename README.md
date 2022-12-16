# Voice-Chat-Bot-Using-JavaScript
In this project use the API to create an artificial intelligence (AI) voice chat interface in the browser. The app will listen to the user’s voice and reply with a synthetic voice. Because the Web Speech API is still experimental, the app works only in supported browsers. The features used for this article, both speech recognition and speech synthesis, are currently only in the Chromium-based browsers, including Chrome 25+ and Opera 27+, while Firefox, Edge and Safari support only speech synthesis at the moment.

To build the web app, we’re going to take three major steps:

Use the Web Speech API’s SpeechRecognition interface to listen to the user’s voice.
Send the user’s message to a commercial natural-language-processing API as a text string.
Once API.AI returns the response text back, use the SpeechSynthesis interface to give it a synthetic voice.
