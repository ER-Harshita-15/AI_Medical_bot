# AI Medical Bot

AI Medical Bot is a multimodal AI-powered application that combines speech-to-text, image analysis, and text-to-speech capabilities to simulate a virtual doctor. Users can speak to the bot, upload medical images, and receive a voice response with medical insights.

## Features

1. **Speech-to-Text (STT)**: Converts user speech into text using the Groq API and Whisper model.
2. **Image Analysis**: Analyzes uploaded medical images using a multimodal large language model (LLM) to provide insights.
3. **Text-to-Speech (TTS)**: Converts the AI's response into speech using ElevenLabs or gTTS.
4. **Gradio Interface**: Provides an easy-to-use web interface for interaction.

## Project Structure

- `gradio_main.py`: Main script to run the Gradio interface.
- `voice_of_patient.py`: Handles audio recording and speech-to-text conversion.
- `voice_of_doctor.py`: Handles text-to-speech conversion.
- `brain_of_doctor.py`: Encodes images and interacts with the multimodal LLM for image analysis.
- `.env`: Stores API keys for Groq and ElevenLabs.
- `requirement.txt`: Lists all the dependencies required for the project.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ER-Harshita-15/AI_MEDICAL_BOT
   cd AI-Medical-Bot
2. Install dependencies:

pip install -r requirement.txt

3. Set up the .env file with your API keys:

GROQ_API_KEY=<your-groq-api-key>
ELEVENLABS_API_KEY=<your-elevenlabs-api-key>

## USAGE

1. Run the Gradio interface:
python gradio_main.py

2. Open the provided URL in your browser (e.g., http://127.0.0.1:7860).

3. Interact with the bot:

-Speak into the microphone.
-Optionally upload a medical image.
-Receive a text and voice response from the AI.

## Dependencies
The project requires Python 3.12 and the following libraries:

-gradio
-groq
-pydub
-speechrecognition
-gtts
-elevenlabs
-Additional dependencies listed in requirement.txt.
## Notes
Ensure ffmpeg and portaudio are installed for audio processing.
The project is for educational purposes and should not be used for real medical diagnosis.
# AI_MEDICAL_BOT
# AI_MEDICAL_BOT
