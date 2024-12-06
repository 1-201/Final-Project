# Text Formatter

## Description
Text Formatter enhances text accessibility for a diverse range of users by enabling them to:
* Customize font sizes, styles, and colours to improve readability.
* Use text-to-speech functionality to hear input text aloud, supporting individuals with severe vision impairments.
* Leverage speech-to-text conversion to input text using their voice, making it accessible for those unable to type.
Our program is designed with accessibility in mind, catering to neurodivergent users and ensuring inclusivity for all age groups.

## Features
* **Speech-to-Text**: Transcribes spoken words into the input box.
* **Text-to-Speech**: Reads the input text aloud.
* **Formatting Options**: Bold and italic buttons to emphasize or modify the text.
* **Font Customization**: Changes the font style.
* **Font Size Adjustment**: Adjusts the font size between 16-50 px using a slider.
* **Colour Customization**: Change text and highlighter colours by entering colour names (e.g. purple) or hex codes (e.g. #514EDA)

## Installation
* To run the program, you'll need to install the following three Python libraries:
1. pyttsx3 (required)
2. SpeechRecognition (required)
3. PyAudio (recommended)
* If Using Python
1. Open your terminal or command prompt.
2. Install the necessary libraries by running the following command:
  ```python
  pip install pyttsx3 SpeechRecognition pyaudio
  ```
3. If pip is not properly set, you can refer to this website: https://packaging.python.org/en/latest/tutorials/installing-packages/ 
* If using Pycharm
1. Navigate to View > Tool Windows > Python Packages
2. In the search bar, type <code>pyttsx3</code>, <code>SpeechRecognition</code>, <code>PyAudio</code>

## How It Works
1. Input: Users can either type text directly or provide speech input to be transcribed.
2. Processing:
* Change font style, apply formatting (bold and italic), and select font sizes.
* Modify text and highlighter colorus using either colour names or hex codes.
* Read the input text aloud with a button press.
3. Output: The formatted text is displayed live in the output area, reflecting all customizations in real time.

## Instructions
1. The program offers two ways for users to input text:
* **Manual Typing**: Users can type English text directly into the entry box.
* **Speech Input**: Press the "Record" button to capture spoken English, and press the same button again to stop recording.
  <p align="center">
    <img src="https://i.imghippo.com/files/ZaY6259Ac.png" alt="" border="0">
  </p>  
2. **Font Style**: Use the dropdown menu to select from three fonts. The changes will reflect in the output box

3. **Font Size**: Adjust the font size using a slider, ranging from 16 to 50. The updated text will appear in the output box.

4. **Text & Highlighter Colours**: Enter the desired colour names or hex codes/ The changes will display in the output box.

5. **Text Styles**: Apply italic or bold styles by pressing the corresponding buttons. Press the buttons again to return the text to its normal appearance.





