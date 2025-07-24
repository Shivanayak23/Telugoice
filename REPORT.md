# 📄 REPORT.md

## 1.1. 📱 Application Overview (MVP Scope)

### **Project Name:** Telugoice

**Telugoice** is an AI-powered bilingual voice assistant that provides real-time **speech-to-speech translation between Telugu and English**.  
Designed for **offline-first** functionality and **low-bandwidth environments**, Telugoice also contributes anonymized **voice-text data** to build open-source corpora for Indian languages.

**Key MVP Goals:**
- Enable **Telugu ↔ English** translation with **STT (Speech-to-Text)** and **TTS (Text-to-Speech)**.
- Provide a lightweight **Streamlit interface** for user interactions.
- Support offline translations using ONNX models.
- Collect voluntary voice-text contributions for building a public dataset.

---

## 1.2. 🤖 AI Integration Details

- **STT (Speech-to-Text):** OpenAI Whisper model for accurate Telugu and English transcription.
- **TTS (Text-to-Speech):** Coqui TTS and gTTS for natural audio output.
- **Translation Engine:** IndicTrans2 and MarianMT for bilingual translation.
- **Frameworks:** Hugging Face Transformers and ONNX for optimized local performance.

---

## 1.3. 🏗 Technical Architecture & Development

- **Frontend:** Streamlit web interface.
- **Backend:** Python with integrated AI pipelines (Whisper + IndicTrans2 + Coqui TTS).
- **Storage:** Local and optional cloud storage for datasets.
- **Deployment:** Hugging Face Spaces (with Streamlit and ONNX runtime).
- **Version Control:** GitLab repository with CI/CD integration.

---

## 1.4. 🧑‍🔬 User Testing & Feedback

- **Week 2 Testing Plan:**
  - Conducted tests with students and rural users.
  - Collected latency and accuracy metrics for low-bandwidth conditions.
  - Used surveys and voice clarity feedback to improve translation accuracy.
- **Insights:**
  - Offline mode (ONNX) provided faster responses in rural areas.
  - Added noise filtering after user feedback.

---

## 1.5. 🗓 Project Lifecycle & Roadmap

### **A. Week 1: Rapid Development Sprint**
- Built core STT + Translation + TTS pipeline.
- Designed Streamlit interface and tested local ONNX models.
- Deployed the MVP to Hugging Face Spaces.

### **B. Week 2: Beta Testing & Iteration Cycle**
- Recruited 20+ testers (students and bilingual speakers).
- Collected user feedback on translation accuracy and voice clarity.
- Fixed bugs, optimized model performance, and improved UI/UX.

### **C. Weeks 3-4: User Acquisition & Corpus Growth**
- Targeted users via **WhatsApp groups, student clubs, and community forums**.
- Promoted with a simple message: *"Translate Telugu ↔ English in real-time and contribute to open-source voice data."*
- **Metrics:** ~120 unique users, ~500 voice-text pairs contributed.

### **D. Post-Internship Vision & Sustainability Plan**
- **Future Features:** Add Hindi and other Indian languages.
- **Community Building:** Collaborate with local communities for corpus growth.
- **Scaling:** Optimize ONNX models for mobile devices.
- **Sustainability:** Open-source contributions and partnerships with NGOs.

---

## 1.6. 🌟 Impact

- Bridges the **Telugu-English language gap** for students and communities.
- Encourages **open data contribution** for AI in Indian languages.
- Demonstrates **offline-first AI deployment** in resource-limited environments.

---

## 1.7. 🚀 Future Scope

- Add support for **more Indian languages** (Hindi, Tamil).
- Build a **mobile app** version.
- Implement **real-time conversational AI** (RAG pipeline).
- Enable **community-driven datasets** and leaderboard for contributors.

---

**Telugoice — Empowering bilingual voice interaction with open AI.**
