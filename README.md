![Telugoice Logo](Telugoice.png)

# Telugoice

**Telugoice** is an open-source AI-powered bilingual voice assistant that enables seamless translation between **Telugu and English**. Designed with accessibility and low-bandwidth usage in mind, Telugoice provides speech-to-speech translation and contributes to building a rich open-source voice-text corpus for Indian languages.

---

## 📑 Table of Contents

- [Team Information](#team-information)
- [Project Overview](#project-overview)
- [Features](#features)
- [Planning](#planning)
- [Team Contributions](#team-contributions)
- [Project Roadmap](#project-roadmap)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Contribution](#contribution)
- [License](#license)

---

## 👥 Team Information

| S.No | Name               | Role                     |
|------|--------------------|--------------------------|
| 1    | Shiva Sai Nath     | Team Lead & Developer    |
| 2    | Khushi             | UI/UX Designer           |
| 3    | Pranay             | AI Model Integrator      |
| 4    | Harshith           | Tester & Evaluator       |
| 5    | Khushi             | Documentation Lead       |

---

## 📱 Project Overview

**Telugoice** helps users:
- Speak in **Telugu** → Get **English audio + text**
- Speak in **English** → Get **Telugu audio + text**
- Use the tool even in **low-internet or offline-first environments**
- Contribute to a **public corpus** of voice-text pairs for research & AI training

---

## ✨ Features

### 1. 🎤 Speech-to-Speech Translation (Telugu ↔ English)
- Real-time recognition and bilingual translation with text + voice output.

### 2. 🔊 Text-to-Speech (TTS)
- Input Telugu or English text → Get audio output in the opposite language.

### 3. 📤 Corpus Contribution
- Each translation (with consent) is logged into an open-source corpus for research.

### 4. 📴 Offline-First Mode
- Works in low-bandwidth environments using ONNX models.

---

## 🗓 Planning

- Use open-source speech models (Whisper, Coqui TTS).
- Build MVP with real-time Streamlit interface.
- Log anonymized user data with permission.
- Enable multilingual toggle and accessibility options.

---

## 🧑‍🤝‍🧑 Team Contributions

| Name              | Responsibilities                                |
|-------------------|-------------------------------------------------|
| Shiva Sai Nath M  | Architecture, Translation Logic, Corpus Logging |
| Khushi            | UI/UX Design, Layout                            |
| Pranay            | Whisper, TTS Integration                        |
| Harshith          | Testing, Voice Clarity Checks                   |
| Khushi            | Documentation, Report Writing                   |

---

## 🗺 Project Roadmap (4 Weeks)

**Week 1: MVP Dev**
- Build basic translator and voice module.

**Week 2: Testing**
- Collect feedback from test users with poor internet.

**Week 3: Corpus Campaign**
- Share with student groups, collect voice-text data.

**Week 4: Final Testing + Deployment**
- Host on Hugging Face.
- Record demo video.
- Submit report and corpus sample.

# Telugoice

A simple AI-powered Telugu text-to-speech app built with Streamlit and gTTS.

## How to Use
- Enter any Telugu sentence.
- Click submit to hear the spoken output.

Built for the Summer of AI 2025 project — focuses on low-bandwidth voice synthesis.


---

## ⚙️ Setup Instructions

```bash
# Clone the repository
git clone https://code.swecha.org/ShivaNayakkk/telugoice.git
cd telugoice

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app/app.py

## 📜 License
This project is licensed under the [MIT License](LICENSE).
