🗣️ Kinya Voice Assistant
An intelligent voice assistant designed for native Kinyarwanda interaction, enabling natural communication through speech recognition and synthesis.

🌟 Features
Voice Input: Captures and processes spoken Kinyarwanda

Speech-to-Text (STT): Converts speech into text using NeMo-powered models

Natural Language Understanding: Combines rule-based processing and ChatGPT for smart query handling

Text-to-Speech (TTS): Produces natural Kinyarwanda speech using MB-iSTFT-VITS2

Interactive UI: Simple and intuitive Gradio-based web interface

📝 Overview
Kinya Voice Assistant delivers an immersive voice interaction experience in Kinyarwanda. It follows a three-stage process:

Recognition: Translates spoken Kinyarwanda to text

Processing: Understands and responds to the text

Synthesis: Converts the response into natural Kinyarwanda speech

🖼️ Demonstration
Terminal Launch


Web Interface


Real-Time Interaction


⚙️ Architecture
🔊 Speech-to-Text (STT)
Powered by NVIDIA NeMo

Pretrained Kinyarwanda model from RW-DEEPSPEECH-API

Supports multiple audio formats

🧠 NLP Engine
Hybrid design:

Rule-based logic for standard queries

OpenAI ChatGPT for complex understanding

Custom intent classification

Handles a wide range of conversational topics

🔉 Text-to-Speech (TTS)
Built with KinyaTTS

Uses the MB-iSTFT-VITS2 model for realistic speech synthesis

🛠️ Setup Guide
Requirements
Python 3.x

NVIDIA GPU (recommended)

Google Colab (for ease of use)

Installation
bash
Copy
Edit
pip install -e /path/to/Inference/  # For KinyaTTS
pip install "numpy<2.1.0,>1.26.0"
pip install Cython
pip install gradio
pip install openai
🚀 How to Use
Open the project in Google Colab

Mount Google Drive with model files

Run all cells to initialize

Interact via the Gradio interface

⚠️ Known Limitations
Noise Sensitivity: Works best in quiet settings

Language Confusion: May misinterpret similar languages like Kiswahili

Sampling Rate Issues: Initial hiccups with certain models resolved through alternatives

📁 Resources
Source code and TTS models: Google Drive

Colab notebook: kin_assistant.ipynb

👏 Acknowledgements
Platform: Google Colab

STT Engine: RW-DEEPSPEECH-API

TTS System: KinyaTTS by Rwanda MIT contributors

NLP: ChatGPT by OpenAI

📄 License
Licensed under the MIT License.
