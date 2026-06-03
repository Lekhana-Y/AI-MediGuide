# 🩺 AI MediGuide
### Where AI Meets Safer Medication

AI MediGuide is an AI-powered mobile healthcare application that digitizes printed prescriptions and provides intelligent medication assistance. The system leverages OCR, NLP, and AI technologies to extract medication information, improve patient understanding, and reduce medication errors.

---

## 📌 Problem Statement

Patients often struggle to understand handwritten prescriptions, medical abbreviations, dosage instructions, and medication schedules. Misinterpretation can lead to medication errors and health risks.

AI MediGuide addresses this challenge by converting prescription images into structured digital information and providing AI-assisted explanations.

---

## 🚀 Features

### 📸 Prescription Digitization
- Capture prescription using camera
- Upload prescription image
- OCR-based text extraction using Tesseract
- Automatic medicine identification
- Structured JSON output generation

### 💊 Medication Management
- Prescription history tracking
- Dosage information extraction
- Medication schedule management
- Offline access to stored prescriptions

### 🤖 AI Assistant
- Medicine explanations
- Dosage guidance
- Side-effect information
- Drug interaction queries
- Context-aware responses

### 🔍 Additional Capabilities
- Medical abbreviation expansion (OD, BID, etc.)
- OpenFDA integration
- Offline-first architecture
- Local data storage

---

## 🏗️ Project Structure

```text
AI-MediGuide/
│
├── README.md
│
├── frontend/
│   ├── components/
│   ├── screens/
│   ├── navigation/
│   ├── assets/
│   └── App.tsx
│
├── backend/
│   ├── api/
│   ├── services/
│   ├── database/
│   ├── models/
│   └── main.py
│
├── screenshots/
│   ├── home-screen.png
│   ├── upload-screen.png
│   ├── extracted-data.png
│   ├── chatbot-screen.png
│   └── history-screen.png
│
├── docs/
│   ├── architecture-diagram.png
│   └── workflow-diagram.png
│
└── LICENSE
```

---

## ⚙️ Technology Stack

### Frontend
- React Native
- Expo
- TypeScript
- React Navigation
- AsyncStorage

### Backend
- FastAPI
- Python
- SQLite
- Uvicorn

### AI & OCR
- Tesseract OCR
- Ollama
- LLaMA 3

### APIs
- OpenFDA API

---

## 🔄 System Workflow

```text
User Uploads Prescription
            │
            ▼
      Mobile Application
            │
            ▼
      FastAPI Backend
            │
            ▼
      Tesseract OCR
            │
            ▼
      NLP Processing
            │
            ▼
      Structured JSON Data
            │
            ▼
      SQLite Database
            │
            ▼
      AI Assistant (LLaMA 3)
            │
            ▼
       User Response
```

---

## 🧠 AI Assistant Workflow

```text
User Question
      │
      ▼
Backend Receives Query
      │
      ▼
Retrieve Prescription Context
      │
      ▼
Send Context to LLaMA 3
      │
      ▼
Generate AI Response
      │
      ▼
Display Response to User
```

---

## 📷 Prescription Processing Workflow

```text
Prescription Image
        │
        ▼
Image Upload
        │
        ▼
OCR Extraction (Tesseract)
        │
        ▼
Medicine Parsing (NLP)
        │
        ▼
JSON Generation
        │
        ▼
SQLite Storage
        │
        ▼
Display Results
        │
        ▼
Offline Access via AsyncStorage
```

---

## 🏆 Key Achievements

- Automated prescription digitization
- Intelligent medicine information extraction
- AI-powered medication guidance
- Offline-first mobile application
- Cross-platform support (Android & iOS)
- Context-aware healthcare assistant

---

## 💪 Technical Strengths

- Modular architecture
- Scalable backend design
- Offline-first implementation
- Cross-platform mobile development
- Open-standard integrations
- Robust error handling

---

## ⚠️ Challenges Addressed

### Handwriting Recognition
- OCR handles varying prescription formats

### Medical Terminology
- Expands abbreviations and explains complex terms

### Data Privacy
- Local storage for improved security

### Network Reliability
- Offline support using AsyncStorage

### User Experience
- Simple and intuitive interface suitable for all age groups

---

## 🔮 Future Enhancements

- Medication reminders & notifications
- Multi-language OCR support
- Text-to-speech prescriptions
- Disease pattern prediction
- Pharmacy locator integration
- Cloud synchronization
- User authentication
- Enhanced security & encryption

---

## 👩‍💻 Contributors

- Y. Lekhana
- C. Maheshwari
- V. Komali
- P. Sravya
- P. Sri Lekha

---

## 📄 License

This project is developed for academic and learning purposes.
