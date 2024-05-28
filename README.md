# AccentLingua

[![AccentLingua Logo](https://assets-global.website-files.com/5fac161927bf86485ba43fd0/6229d40f625c70840c12bcd7_BlogGif_2.gif)](https://accentlingua.streamlit.app/)

AccentLingua is a web application designed for audio transcription and translation. Users can upload or record audio, transcribe it, and translate the transcribed text into multiple languages with various accents. It also includes account management features using Firebase Authentication.

## Features

- **Account Management**: Sign up, login, email verification, and password reset functionalities.
- **Audio Transcription**: Transcribe pre-recorded audio files or record and transcribe audio in real-time.
- **Translation and Text-to-Speech**: Translate transcribed text into multiple languages and generate speech with various English accents.
- **User Interface**: Sleek and responsive UI with Bootstrap styling.

## Getting Started

### Prerequisites

- Python 3.8 or later
- Streamlit
- Requests
- gTTS
- googletrans
- firebase-admin
- smtplib

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/AccentLingua.git
   cd AccentLingua
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Configure Firebase:
   - Place your Firebase service account JSON file in the project directory.
   - Update `st.secrets` with your Firebase credentials and API keys.

4. Run the app:

   ```bash
   streamlit run app.py
   ```

### Using AccentLingua

1. **Sign Up:**
   - Select "Sign up" from the dropdown.
   - Enter your email, password, and a unique username.
   - Click "Create my account".
   - Check your email for a verification link and verify your email.

2. **Login:**
   - Select "Login" from the dropdown.
   - Enter your email and password.
   - Click "Login".

3. **Forgot Password:**
   - Enter your email and click "Forgot Password".
   - Check your email for a password reset link.

4. **Transcribe Pre-recorded Audio:**
   - Upload an audio file (MP3, WAV, etc.).
   - The app will display the transcription in real-time.
   - Translate and generate speech from the transcribed text.

5. **Record & Transcribe:**
   - Click "Record" to start recording your voice.
   - Play back the recorded audio.
   - Transcribe the recorded audio.

## Hardware Requirements

- Computer with an internet connection
- Microphone (for recording audio)

## Contact

For any issues or questions, please contact:
- **Adi**: [LinkedIn](https://www.linkedin.com/in/adityapuri10/)
- **GitHub**: [Adi1042003](https://github.com/Adi1042003)

Thank you for using AccentLingua! We hope it helps you in your language learning and audio transcription needs.

### Hosted Version

AccentLingua is hosted on Streamlit Cloud and can be accessed [here](https://accentlingua.streamlit.app/).
