# HealthLink Central
**One patient. One record. Anywhere.**
---
## 🏥 Overview
HealthLink Central is a centralized, consent-based health record system designed to enable secure, real-time access to patient medical information across healthcare facilities in South Africa.
In many healthcare facilities today, patient records are still stored as physical files within individual hospitals or clinics. This creates fragmented medical histories, as patients must often have to recreate a files when visiting a different facility. This leads to delays in treatment, repeated medical tests, and inefficient communication between healthcare providers and/or facilities.
HealthLink Central solves this by introducing a single, unified digital health record per patient that can be securely accessed from any authorized healthcare institution. This ensures continuity of care, improves efficiency, and supports better clinical decision-making.
---
## 🎯 Problem Statement
Healthcare facilities that rely on physical or isolated digital records face several challenges:
- Patient records are not shared between hospitals or clinics
- Medical history is often incomplete or inaccessible in emergencies
- Patients must repeatedly register and recreate files
- Delays occur in diagnosis and treatment
- Increased administrative workload for healthcare staff
These challenges negatively impact the quality and speed of healthcare delivery.
---
## 💡 Our Solution
HealthLink Central introduces a **centralized national-style health record system** where:
- Each patient has one unified digital medical record (file)
- Records can be accessed across multiple healthcare facilities
- Access is strictly controlled and consent-based
- Patients remain in full control of their medical data
### 🔄 How it works (simple flow)
HealthLink Central is designed with both a web-based system and a mobile application to support patient registration, identity verification, and secure access to medical records.
---
### 📝 1. Patient Registration (Web System – Clerks)
- A patient is registered **once** at any healthcare facility
- A clerk uses the web platform to capture:
- Patient details (e.g., name, ID)
- Medical baseline information
- The patient’s identity is verified using a webcam (Face ID/biometric scan)
- A **unique digital health record** is created for the patient
This record becomes the patient’s **single, centralized file** across all healthcare institutions.
---
### 📱 2. System Access (Mobile Application)
During a consultation, users access the system via the mobile app by selecting their role:
- **“I am a Patient”**
- **“I am a Healthcare Provider”**
---
### 👤 Patient Access
When a patient selects **“I am a Patient”**:
- They can view their medical records
- Use Face ID to verify identity
- Access the AI health assistant to better understand their condition
---
### 🧑‍⚕️ Healthcare Provider Access
When a provider selects **“I am a Healthcare Provider”**:
- They search for the patient in the system
- Request access to the patient’s record
---
### 🔐 3. Consent & Verification
The system supports multiple consent methods:
#### 📱 Mobile Consent (Smartphone Users)
- Patient approves access using Face ID on their device
#### 🏥 Clinic-Based Consent (No Smartphone)
- Patient is verified in person using the web system and webcam
- Clerk assists with approval
#### 🚨 Emergency Access
- In critical cases, controlled access is granted using predefined protocols
---
### 🔓 4. Secure Record Access
Once verification and consent are complete:
- The healthcare provider is granted **secure, temporary access** to the patient’s centralized medical record
---
This approach ensures that HealthLink Central is inclusive, secure, and adaptable, supporting both digital and non-digital users across all healthcare environments.
---
## 🔐 Security & Privacy
Security and privacy are central to the system design:
- No healthcare provider can access records without consent
- Face ID authentication is used for secure patient approval
- Access is time-bound and controlled
- Patient data is protected using secure authentication layers
In emergency situations where a patient is unable to respond:
- The system supports controlled emergency access mechanisms
- Family or authorized contacts may provide consent where applicable
---
## 📡 CAMARA API Integration (Network-as-Code)
HealthLink Central integrates Nokia-hosted CAMARA APIs via the Network-as-Code Developer Portal to enhance identity verification, device trust, and system security.
### 🔐 Identity & Trust Verification
- **KYC Match API**
Used to verify that the patient’s identity matches telecom-verified records before granting access.
- **Number Verification API**
Confirms that the mobile number used in the request belongs to the registered patient.
### 📱 Device & Access Validation
- **Device Status API**
Checks whether the patient’s device is active and reachable for consent approval.
- **SIM Swap API (optional enhancement)**
Detects potential fraud or SIM change activity to prevent unauthorized access.
### 📍 Location-Based Security (optional enhancement)
- **Location Verification API**
Ensures that access requests are made from valid healthcare environments (e.g., hospitals or clinics).
---
## 🤖 AI Health Assistant (Patient Chatbot)
HealthLink Central includes an AI-powered healthcare assistant designed to support patients in understanding their medical information.
When a user selects **“I am a patient”**, they gain access to a chatbot that interacts only with healthcare-related information from their record.
### 🧠 What the AI assistant does:
- Explains diagnoses in simple, understandable language
- Breaks down medical terms and prescriptions
- Provides guidance based on the patient’s recorded condition
- Helps patients understand treatment instructions
### ⚠️ Important limitation:
The AI assistant does not replace medical professionals. It only provides informational support based on existing patient data and is designed to assist, not diagnose or prescribe.
---
## 🧑‍⚕️ User Roles
### 👤 Patient
- View personal health records
- Approve or deny access requests
- Use AI health assistant
- Manage consent-based sharing
### 🏥 Healthcare Provider
- Request access to patient records
- View records after approval
- Update medical information (authorized access only)
---
## ⚙️ Key Features
- Centralized patient health records
- Consent-based access control
- Face ID authentication
- Cross-facility record sharing
- Emergency access support
- Telecom-powered identity verification (CAMARA APIs)
- AI health assistant for patients
---
## 🚀 Future Improvements
- Full national healthcare integration
- Advanced AI clinical summarization (RAG-based system)
- Offline emergency record access
- Expanded interoperability between hospitals
- Predictive health insights using AI
---
## 🧠 Vision
To build a unified digital healthcare ecosystem where patient data is secure, portable, and accessible anywhere, ensuring faster, safer, and more efficient healthcare delivery for all.
---
## 👨‍💻 Project Status
This project is currently in prototype development as part of a hackathon focused on healthcare innovation using telecom-powered APIs and AI-assisted systems.
