# PDF to Audio Converter: Transform Your PDFs into Personalized Audiobooks

## Description
This project is a **Text-to-Audio converter** application that extracts text from PDF files and converts it into an audio file. The application utilizes **Streamlit** for the frontend, **PyPDF2** for PDF text extraction, and **gTTS** (Google Text-to-Speech) for audio conversion. The user can upload PDF files, choose a target language for the text, and save the resulting audio files to a specified directory.

## Features
- Upload PDF files and extract text.
- Translate the extracted text into the selected language using **GoogleTranslator**.
- Convert the translated text into audio using **gTTS**.
- Option to save both the translated text and audio in a custom output directory.
- Audio playback within the app after conversion.
- Download the translated text file.
- Customizable UI with modern styles.

## Requirements
- Python 3.x
- Streamlit
- PyPDF2
- gTTS
- deep_translator
- googletrans
- os

To install the required libraries, run:

```bash
pip install streamlit PyPDF2 gtts deep_translator googletrans
