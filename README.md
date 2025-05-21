**LLM Chat Application with Flutter & Flask**
A simple chat application that connects a Flutter frontend to a local GPT-2 model via a Flask API.

**📌 Overview**
This project demonstrates how to integrate a Flutter mobile app with a Python Flask API that serves a GPT-2 language model for text generation. The system allows users to input prompts and receive AI-generated responses in real time.

**✨ Key Features**
✅ Flutter UI – Clean and responsive interface for text input and response display

✅ Flask API – RESTful backend that processes requests using the Hugging Face transformers library

✅ GPT-2 Model – Generates text responses based on user prompts

✅ Cross-Platform – Works on Android, iOS, and web (with additional setup)

✅ Test Client – Python script (client.py) to manually test the API

**🛠️ Tech Stack**
Component	Technology
Frontend	Flutter (Dart)
Backend	Flask (Python)
AI Model	GPT-2 (transformers library)
Networking	HTTP (Flutter http package)

**⚙️ Setup & Usage**

**1. Clone the Repository**
bash
git clone https://github.com/Chaman4211/llm-chat-flutter-flask.git
cd llm-chat-flutter-flask

**2. Set Up the Flask API**
Install Python dependencies:

bash
pip install flask flask-cors transformers torch
Run the API server:
bash
python llm_flask_api.py
(API runs at http://localhost:5000)

**3. Run the Flutter App**
bash
flutter pub get
flutter run

**4. (Optional) Test the API Directly**
Run the Python test client:

bash
python client.py

**📂 Project Structure**
.
├── lib/                  # Flutter app source code
│   └── main.dart         # Main Flutter UI & logic
├── llm_flask_api.py      # Flask API with GPT-2
├── client.py             # Python API test client
├── pubspec.yaml          # Flutter dependencies
├── README.md             # Project documentation
└── ...                   # Other config files

**📜 License**
This project is open-source under the MIT License.

**🔗 Useful Links**
Flutter Documentation

Flask Documentation

Hugging Face Transformers


