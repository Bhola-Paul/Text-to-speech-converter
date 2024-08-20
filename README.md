# Text-to-speech-converter
A basic web application that transforms written text into spoken audio using HTML, CSS, and JavaScript. Leveraging the Web Speech API, this project offers a hands-on experience with speech synthesis. Explore the fundamentals of text-to-speech conversion without external APIs.
Files
index.html: Contains the HTML structure of the application, including the text input area, voice selection dropdown, and play button.
style.css: Styles the HTML elements, providing the visual appearance of the converter.
script.js: Contains the JavaScript logic for handling text input, voice selection, and speech synthesis.
Functionalities
Text Input: Users can input any text they want to be converted to speech.
Voice Selection: The application provides a dropdown menu to select different available voices for speech synthesis.
Speech Output: Clicking the "Speak" button initiates the text-to-speech conversion, and the input text is spoken aloud using the selected voice.
Voice Selection
The Web Speech API provides a list of available voices on the user's system. The JavaScript code accesses this list and populates the voice selection dropdown. Users can then choose the desired voice from the options.

How it Works
The user enters text into the input field.
The user selects a desired voice from the dropdown.
Clicking the "Listen" button triggers the JavaScript code.
The JavaScript code creates a SpeechSynthesisUtterance object with the input text and selected voice.
The SpeechSynthesisUtterance object is passed to the speechSynthesis.speak() method to initiate speech output.
