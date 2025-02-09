<style>
    body {
        background-image: url('DALL·E 2025-02-09 13.36.25 - A modern web application interface for uploading audio files. The interface has a clean and user-friendly design with an upload button, a language sel.webp');
        background-size: cover;
        background-repeat: no-repeat;
        background-attachment: fixed;
        color: white;
    }
</style>![Description of Image](DALL·E%202025-02-09%2013.36.25%20-%20A%20modern%20web%20application%20interface%20for%20uploading%20audio%20files.%20The%20interface%20has%20a%20clean%20and%20user-friendly%20design%20with%20an%20upload%20button,%20a%20language%20sel.webp)

# Audio Translation Project

## Description
This project is a Flask web application that allows users to upload audio files for translation using OpenAI's Whisper API. The application provides a user-friendly interface for uploading audio files and specifying the language for translation.

## Features
- Upload audio files in various formats.
- Specify the language for translation.
- Utilizes OpenAI's Whisper API for audio translation.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/kri-sh27/Audio-transilation.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Audio-transilation
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the application:
   ```bash
   python app.py
   ```
2. Open your web browser and go to `http://localhost:8080`.
3. Upload your audio file and specify the language.

## Requirements
- Python 3.x
- Flask
- OpenAI Python client
- dotenv
