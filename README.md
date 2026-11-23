🎙️ JULHAS TTS

AI-Powered Text-to-Speech Web Application

JULHAS TTS is a personal web-based Text-to-Speech application developed by JULHAS M using Python, Flask, and Microsoft Edge TTS.

The project aims to make AI-powered voice generation accessible through a simple web interface, with voice selection, model options, and audio generation capabilities.

---

✨ Key Features

JULHAS TTS includes the following 11 notable features:

1. Text-to-Speech Conversion – Convert written text into spoken audio.
2. Multiple Voice Options – Access available voice choices.
3. Voice Character Selection – Select different available voice styles.
4. Voice Preview & Testing – Test voice options before generating audio.
5. Model Selection – Choose from supported available models.
6. MP3 Audio Generation – Generate speech audio in MP3 format.
7. Audio Download – Save generated audio files.
8. API Key Management – Configure supported API credentials.
9. Web-Based Interface – Use the application through a browser.
10. Audio File Organization – Store generated audio files in a dedicated folder.
11. Generation Metadata – Keep associated JSON metadata for generated audio where supported.

Some features depend on the configured provider, model, and application settings.

---

🛠️ Technologies Used

Technology| Purpose
Python| Application logic
Flask| Web server and backend
Microsoft Edge TTS| Text-to-speech engine
Requests| HTTP/API communication
HTML| Webpage structure
CSS| User interface styling
JavaScript| Frontend interactions

---

📂 Project Structure

JULHAS-TTS/
│
├── app.py
├── julhas_tts.py
├── requirements.txt
│
├── templates/
│   └── index.html
│
├── JULHAS_TTS/
│   └── Generated audio files
│
├── .gitignore
├── README.md
└── LICENSE

Generated audio and private configuration files are not included in the public source repository.

---

🚀 Installation & Usage

Requirements

- Python 3.10 or newer
- pip
- Git
- Internet connection

Step 1: Clone the Repository

git clone https://github.com/julhasmiea7-hub/JULHAS-TTS.git

Step 2: Enter the Project Directory

cd JULHAS-TTS

Step 3: Install Dependencies

pip install -r requirements.txt

Step 4: Configure the Application

Configure any required API credentials locally.

Never publish API keys, tokens, or passwords.

Step 5: Run the Application

python app.py

Step 6: Open in Browser

http://127.0.0.1:5000

---

📦 Dependencies

The project uses the following Python packages:

Flask
requests
edge-tts

Install them using:

pip install Flask requests edge-tts

---

🔐 Security & Privacy

Security is important for this project.

- API keys must remain private.
- ".env" must never be uploaded publicly.
- "api_keys.json" must remain private.
- Never commit passwords or access tokens.
- Review files before every public release.
- Do not expose private user information.

---

👨‍💻 Developer

JULHAS M

- GitHub: "@julhasmiea7-hub" (https://github.com/julhasmiea7-hub)
- Project: "JULHAS-TTS" (https://github.com/julhasmiea7-hub/JULHAS-TTS)
- Location: Bangladesh

---

📜 License

This project is distributed under the MIT License.

See the "LICENSE" (LICENSE) file for details.

---

⚠️ Disclaimer

JULHAS TTS is an independent personal project.

It is not officially affiliated with or endorsed by Microsoft or any third-party service provider.

The availability of voices and services depends on the respective providers.

---

⭐ Support

If you find this project interesting or useful:

- Star this repository.
- Explore the source code.
- Share your feedback.
- Contribute improvements.

Built with dedication by JULHAS M 🇧🇩
