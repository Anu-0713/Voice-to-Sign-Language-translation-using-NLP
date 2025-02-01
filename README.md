# Voice-to-Sign-Language-translation-using-NLP
## Overview

This project aims to bridge the communication gap between the hearing and speech-impaired community and the general public by translating spoken language into sign language using Natural Language Processing (NLP) techniques.

## Features

- **Speech Recognition**: Converts spoken language into text.
- **Text Processing**: Utilizes NLP to process and interpret the transcribed text.
- **Sign Language Translation**: Maps processed text to corresponding sign language representations.


Project Demo Video: https://youtu.be/YiHhD0QGrno

## Prerequisites

> - Python >= 3.7
> - Browser supports Web Speech API
> - Download all required packages for python script A2SL/views.py

## Installation Guide:
1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Anu-0713/Voice-to-Sign-Language-translation-using-NLP.git
   cd Voice-to-Sign-Language-translation-using-NLP
   ```

2. **Set Up a Virtual Environment**:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the Application**:

   ```bash
   python manage.py runserver
   ```

2. **Access the Web Interface**:

   Open your browser and navigate to `http://127.0.0.1:8000/` to interact with the application.

## Project Structure

- `A2SL/`: Contains the main application code.
- `Animations/`: Stores animations or visual representations of sign language.
- `Web page/`: Includes static files and templates for the web interface.
- `manage.py`: Django's command-line utility for administrative tasks.
- `requirements.txt`: Lists the Python dependencies required for the project.
- `setup.py`: Script for setting up the project.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes.
