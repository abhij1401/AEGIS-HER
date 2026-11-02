# 🛡️ AEGIS-HER
### Edge-Centric Multimodal Surveillance and Covert Distress Signaling for Women's Safety

**AEGIS-HER** is a proposed AI-powered women's safety framework that combines computer vision, audio analysis, hand gesture recognition, and privacy-preserving security mechanisms to identify potential threats and support timely emergency response.

The system aims to go beyond traditional CCTV surveillance by integrating intelligent threat detection with a covert **Signal for Help** gesture and severity-based emergency alert generation.

---

## 🎯 Project Objectives

- **Violence Detection:** Identify potentially violent activities through CCTV video and audio analysis.
- **Covert Distress Recognition:** Recognise the Signal for Help hand gesture.
- **Multimodal Analysis:** Combine audio and video information for contextual threat assessment.
- **False Alarm Reduction:** Distinguish potentially dangerous incidents from harmless activities.
- **Severity-Based Alerts:** Generate appropriate alerts for designated responders.
- **Secure Evidence Storage:** Protect incident records using encryption and integrity verification.
- **Privacy Protection:** Restrict unauthorised access and minimise unnecessary data collection.
- **Edge Processing:** Support local processing to reduce cloud dependence.

---

## 🧠 Key Features

| Feature | Description |
|---|---|
| Video Analysis | CCTV video processing and threat detection |
| Audio Analysis | Extraction and analysis of relevant audio cues |
| Gesture Recognition | Signal for Help hand gesture recognition |
| Multimodal Fusion | Combining audio and video information |
| Threat Assessment | Severity-based incident classification |
| Emergency Alerts | SMS, WhatsApp and automated call integration |
| Evidence Security | Encrypted evidence and integrity verification |
| Privacy | Local processing and role-based access control |

---

## 🏗️ Proposed System Architecture

```text
       CCTV VIDEO       AUDIO       HAND GESTURE
            │             │              │
            ▼             ▼              ▼
       VIDEO AI       AUDIO AI      MEDIAPIPE
            │             │              │
            └─────────────┼──────────────┘
                          ▼
                  MULTIMODAL FUSION
                          │
                          ▼
                THREAT SEVERITY
                  ASSESSMENT
                          │
                 ┌────────┴────────┐
                 ▼                 ▼
           EMERGENCY ALERT    SECURE EVIDENCE
                 │                 │
                 ▼                 ▼
           RESPONDERS         ENCRYPTED STORAGE
```

---

## ⚙️ Technology Stack

| Category | Technologies |
|---|---|
| Programming | Python |
| Computer Vision | OpenCV |
| Gesture Recognition | MediaPipe |
| Deep Learning | PyTorch / TensorFlow (to be evaluated) |
| Audio Processing | Librosa (candidate tool) |
| Data Processing | NumPy, Pandas |
| Security | AES-256-GCM, SHA-256, TLS 1.3 |
| Access Control | RBAC |
| Backend | Python-based API (to be selected) |
| Infrastructure | Local / Edge Server |

---

## 📊 Datasets

The project synopsis identifies the following datasets for training and evaluation:

- ExtraAnom
- XD-Violence
- RWF-2000
- RLVS

Dataset access, licensing, labels, and suitability will be verified before use.

---

## 🔐 Security and Privacy

AEGIS-HER proposes multiple security mechanisms:

- **AES-256-GCM:** Encryption of stored incident evidence.
- **SHA-256:** Integrity verification and tamper-evident records.
- **TLS 1.3:** Secure communication between services.
- **RBAC:** Role-based access to sensitive information.
- **Edge Processing:** Local data processing where feasible.

---

## 📁 Project Structure

```text
AEGIS-HER/
├── docs/
├── data/
├── models/
├── src/
├── backend/
├── frontend/
├── security/
├── tests/
├── notebooks/
├── scripts/
├── requirements.txt
└── README.md
```

---

## 🚀 Project Status

**Current Stage:** Project Planning and Architecture Design

Planned development milestones:

- [ ] Research and dataset preparation
- [ ] CCTV video processing
- [ ] Audio analysis module
- [ ] Signal for Help gesture recognition
- [ ] Multimodal fusion
- [ ] Threat severity assessment
- [ ] Emergency alert integration
- [ ] Secure evidence management
- [ ] System integration and testing

---

## 🎯 Expected Applications

- Public places and railway stations
- Educational institutions
- Workplaces
- Public transportation
- Residential societies
- Emergency response centres

---

## 👥 Project Team

| Name | Role |
|---|---|
| Samarth Balkrishna Shelkande | Project Team Member |
| Abhishek Gopalrao Jadhav | Project Team Member |
| Aarti Sanjay Navpute | Project Team Member |
| Aishwarya Manohar Sonawane | Project Team Member |

**Project Guide:** Prof. Pallavi Khalde

**Department:** Computer Science Engineering (Artificial Intelligence)

**Institute:** Vishwakarma Institute of Technology, Pune

---

## 📚 References

1. [MDPI Research Article](https://www.mdpi.com/2504-4990/6/4/119)
2. SUSAN: A Deep Learning-Based Architecture for Violence Detection Against Women in Surveillance Videos.
3. Aligning First, Then Fusing: A Novel Weakly Supervised Multimodal Violence Detection Method.

---

## ⚠️ Disclaimer

AEGIS-HER is an academic research and development project. AI-generated alerts indicate potential incidents and must not be treated as definitive proof of criminal activity. Real-world deployment requires extensive validation, human oversight, privacy safeguards, and compliance with applicable laws.

---

**Building technology for safer spaces. 🛡️**
