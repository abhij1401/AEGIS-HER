# 🛡️ AEGIS-HER
### Edge-Centric Multimodal Surveillance and Covert Distress Signaling for Women's Safety

AEGIS-HER is an AI-powered women's safety project that proposes an integrated surveillance framework combining computer vision, audio analysis, covert distress gesture recognition, and secure evidence management.

The system aims to identify potential threats, recognise silent distress signals, assess incident severity, and support timely emergency response through an edge-centric architecture.

## 🎯 Project Objectives

- Detect potentially violent activities through CCTV video analysis.
- Recognise the covert Signal for Help hand gesture.
- Analyse audio cues using deep learning techniques.
- Combine video, audio, and gesture information through multimodal fusion.
- Reduce false alarms using contextual analysis.
- Generate severity-based emergency alerts.
- Secure incident evidence using encryption and integrity verification.
- Support privacy-conscious local processing.

## ✨ Key Features

| Feature | Description |
|---|---|
| Video Processing | CCTV video analysis using OpenCV |
| Violence Detection | Fine-tuned MoViNet model |
| Gesture Recognition | MediaPipe with custom GRU/LSTM |
| Audio Analysis | Librosa and CNN |
| Multimodal Fusion | Late multimodal fusion |
| Edge Processing | ONNX Runtime |
| Threat Assessment | Severity-based incident classification |
| Emergency Alerts | SMS, WhatsApp, automated calls |
| Evidence Security | AES-256-GCM encryption |
| Integrity Verification | SHA-256 hash chain |
| Access Control | Spring Security and RBAC |

## 🏗️ Proposed System Architecture

1. **Input Layer:** CCTV cameras, microphones, and edge capture unit.
2. **Video Processing:** OpenCV-based frame processing and MoViNet violence detection.
3. **Gesture Recognition:** MediaPipe hand landmark detection with custom GRU/LSTM.
4. **Audio Analysis:** Librosa feature extraction and CNN-based classification.
5. **Multimodal Fusion:** Late fusion of video, audio, and gesture outputs.
6. **Threat Assessment:** False-alarm filtering and severity classification.
7. **Alert Generation:** SMS, WhatsApp, and automated calls.
8. **Secure Evidence:** AES-256-GCM, SHA-256 hash chain, and RBAC.

## ⚙️ Technology Stack

| Category | Technology |
|---|---|
| Programming Languages | Python, Java |
| Computer Vision | OpenCV |
| Violence Detection | MoViNet |
| Gesture Recognition | MediaPipe, GRU/LSTM |
| Audio Processing | Librosa |
| Audio Classification | CNN |
| Multimodal Fusion | Late Multimodal Fusion |
| Edge Inference | ONNX Runtime |
| Backend | Spring Boot |
| Authentication & Security | Spring Security |
| Encryption | AES-256-GCM |
| Integrity | SHA-256 Hash Chain |
| Communication Security | TLS 1.3 |

## 📊 Datasets

The project identifies the following datasets for research and evaluation:

- RWF-2000
- XD-Violence
- RLVS
- ExtrAnom

Dataset access, licensing, labels, and suitability will be verified before implementation.

## 🔐 Security and Privacy

- AES-256-GCM for evidence encryption.
- SHA-256 hash chain for evidence integrity.
- TLS 1.3 for secure communication.
- Role-Based Access Control (RBAC).
- Local edge processing to reduce cloud dependency.
- Restricted access to sensitive incident information.

## 📁 Repository Structure

```text
AEGIS-HER/
│
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt
│
├── docs/
│   ├── project_overview.md
│   ├── literature_survey.md
│   ├── research_gap.md
│   ├── objectives.md
│   └── system_architecture.md
│
├── datasets/
│   ├── README.md
│   └── dataset_sources.md
│
├── ai_engine/
│   ├── video_processing/
│   ├── violence_detection/
│   ├── gesture_recognition/
│   ├── audio_analysis/
│   └── multimodal_fusion/
│
├── edge_processing/
│
├── backend/
│   └── spring-boot/
│
├── security/
│   ├── encryption/
│   ├── integrity/
│   └── access_control/
│
├── alert_system/
│   ├── sms/
│   ├── whatsapp/
│   └── calls/
│
├── frontend/
├── models/
└── tests/
```

## 🚀 Development Roadmap

- [ ] Dataset collection and preparation
- [ ] OpenCV video processing
- [ ] MoViNet violence detection
- [ ] Signal for Help gesture recognition
- [ ] Audio analysis using Librosa and CNN
- [ ] Multimodal fusion implementation
- [ ] False-alarm filtering
- [ ] Threat severity assessment
- [ ] ONNX Runtime edge deployment
- [ ] Spring Boot backend development
- [ ] Evidence encryption and integrity verification
- [ ] Emergency alert integration
- [ ] Frontend development
- [ ] System integration and testing

## 👥 Project Team

| Name | Role |
|---|---|
| Samarth Balkrishna Shelkande | Team Member |
| Abhishek Gopalrao Jadhav | Team Member |
| Aarti Sanjay Navpute | Team Member |
| Aishwarya Manohar Sonawane | Team Member |

**Project Guide:** Prof. Pallavi Khalde

**Department:** Computer Science Engineering (Artificial Intelligence)

**Institute:** Vishwakarma Institute of Technology, Pune

## 📚 References

1. https://www.mdpi.com/2504-4990/6/4/119
2. SUSAN: A Deep Learning-Based Architecture for Violence Detection Against Women in Surveillance Videos.
3. Aligning First, Then Fusing: A Novel Weakly Supervised Multimodal Violence Detection Method.
4. An Active Learning Driven Deep Spatio-Textural Acoustic Feature Ensemble Assisted Learning Environment for Violence Detection in Surveillance Videos.
5. A Multimodal Framework for Violent Behavior Recognition in Surveillance Videos.
6. An Analysis Focused on Women's Safety: Can VAD Models Be Enhanced by a Multi-modal Dataset?
7. GVD: General Violence Detection via Semantic Differentiation and Orthogonal Supervision.

## ⚠️ Disclaimer

AEGIS-HER is an academic research and development project. AI-generated alerts represent potential incidents and should not be treated as definitive proof of criminal activity. Real-world deployment requires extensive validation, human oversight, privacy safeguards, and compliance with applicable laws.

---

**Building technology for safer spaces. 🛡️**
