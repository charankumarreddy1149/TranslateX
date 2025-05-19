# TranslateX
similar to speakEasy but focuses more on features 
# TranslateX: Advanced Translation and Speech Utility

## Overview

TranslateX is a Streamlit application designed for seamless text translation with integrated speech capabilities. It allows users to translate text between various languages and offers options for text-to-speech synthesis of the translated text.

## Features

* **Text Translation:**
    * Supports translation between a wide range of languages.
    * User-friendly interface for inputting text and selecting source and target languages.
    * Utilizes a robust translation backend (e.g., Google Translate API, or a similar service).
* **Text-to-Speech (TTS) for Translated Text:**
    * Synthesizes speech from the translated text.
    * Supports multiple languages for speech output, matching the translation target.
    * Offers options for voice selection (if available from the TTS engine).
    * Provides controls for speech rate (if supported).
    * Allows users to play the synthesized speech directly within the application.
    * Option to download the synthesized audio.
* **User Interface:**
    * Clean and intuitive Streamlit interface.
    * Clear language selection dropdowns.
    * Dedicated area for displaying the original and translated text.
    * Playback controls for the synthesized speech.

## File

* `speech.py` (now considered the main file for TranslateX): Contains all the application logic for translation and text-to-speech.

## Dependencies

* streamlit
* googletrans  *(Assuming this is used for translation)*
* pyttsx3 or gTTS *(Assuming one of these is used for TTS)*

You might need to install these libraries using pip:

```bash
pip install streamlit googletrans pyttsx3  # Or pip install streamlit googletrans gTTS
