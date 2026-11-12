# Phan Xuan Khoa (Phan Xuân Khoa)

High school student in the Informatics specialization at the **High School for the Gifted, VNU-HCM (PTNK)**, Class of 2028.  
I build applied AI systems end to end, from data pipelines and models to the APIs and interfaces people use. My main areas are **multimodal retrieval, medical imaging and fast inference on ordinary hardware**.

📫 khoaphan.academic@gmail.com · [Codeforces](https://codeforces.com/profile/XKhoa)

---

## 🔬 Research

**Sub-Event Ranking and Whole-Video Candidate Search for Multi-Event Temporal Grounding in a Hybrid Multimodal Retrieval System**  
T. L. Cao, **X. K. Phan**, N. N. Duc, Q. T. Ha, A. Q. Dang. *Accepted for oral presentation at SOICT 2026* (13th International Symposium on Information and Communication Technology). Second author and corresponding author.  
I built the system's retrieval API (FastAPI), its unified search interface and the keyframe-processing pipeline. Code: [Tinhcautoan/aic2026](https://github.com/Tinhcautoan/aic2026)

**Research intern, AIoT Lab Vietnam, International University – VNU-HCM** (Summer 2026)  
Supervisors: Dr. Le Duy Tan, Pham Duc Dat.
- Built a multimodal BI-RADS classifier for mammography (VinDr-Mammo) that fuses the CC and MLO views with clinical metadata: SwinV2 backbone, cross-attention fusion, CatBoost head. Macro-F1 0.454 under patient-grouped 4-fold cross-validation on a heavily imbalanced 3-class task.
- Built most of **mammo-validator**, a full-stack DICOM viewer and review tool (Next.js, TypeScript, SQLite) where radiologists check labels flagged by Confident Learning (Cleanlab).

Code: [s4dz/birads-multimodal-mammography](https://github.com/s4dz/birads-multimodal-mammography)

---

## 🛠️ Selected projects

| Project | What it does | Stack |
| :-- | :-- | :-- |
| [**aic2026**](https://github.com/Tinhcautoan/aic2026) | Multimodal video retrieval system behind the SOICT 2026 paper. First Prize, High School Division, AI Challenge HCMC 2026 | Python, FastAPI |
| [**IELTS essay scoring**](https://github.com/s4dz/ielts-essay-scoring-paic2025) | Scores IELTS Task 1 and Task 2 essays on the 1–9 band scale. Team Mango's winning entry at PAIC 2026. CV MAE 0.415 | DeBERTa-v3, LightGBM, CatBoost |
| [**Dysgraphia early screening**](https://github.com/DavBao-dev/Dysgraphia-Screening-Prototype) | Screens elementary students for dysgraphia from hand movement (MediaPipe landmarks, tremor and kinematic features, Random Forest) and handwriting images (ResNet50). First Prize, Southern Region, National Youth Creativity Competition in AI 2026. Team leader; I built the FastAPI + Next.js web app | MediaPipe, ResNet50, FastAPI, Next.js |
| [**ChildSafe**](https://github.com/Liamislazy/childsafe) | On-device prototype that warns a caregiver when a hand-held object stays near a child's mouth on camera. Leak-free evaluation: 92.0% accuracy on a deduplicated ChildSUn split (vs. 99% on a leaky random split). Built with Cao Tung Lam; I built most of the live multi-person runtime and browser demo, the Android companion app and the play-area check | YOLO11, MediaPipe, EfficientNet, Android |
| [**Volunteer scheduler**](https://github.com/s4dz/sap-xep-tkb) | Offline tool that builds the weekly tutoring timetable for SUGAR Vietnam's two centres, using constraint programming with strictly ordered objectives. Used by the coordinating team | OR-Tools CP-SAT, Streamlit |
| [**TensorTonic solutions**](https://github.com/s4dz/TensorTonic-Solutions) | 32 core deep-learning components written from scratch in NumPy: optimizers, losses, convolution, ResNet blocks | NumPy |

---

## 🏆 Selected honors

- **First Prize, High School Division**, AI Challenge Ho Chi Minh City 2026
- **First Prize, Southern Region (Category B)**, National Youth Creativity Competition in AI 2026. Team leader; advanced to the national final
- **Champion (Team Mango) and Best Individual Award**, PTNK AI Challenge (PAIC) 2026
- **Bronze Medal, AI Challenge Division**, Olympiad in Informatics in Central Vietnam 2026 (6th of 53 teams)
- **One of two outstanding projects out of 22**, AI Foundation Study Program 2025 (HCMC Department of Science and Technology)

---

## 🤝 Community

- **AIQS (High School AI, Quant & Startup Project):** co-founder, vice president and head of the AI division. I mentor the 27 members and review the content of our ML/DL seminars.
- **SUGAR Vietnam:** I coordinate 18 volunteer teachers across 2 social protection centers. I also built the [scheduling tool](https://github.com/s4dz/sap-xep-tkb) that matches volunteers' availability with the children's sessions.
- **The Noders AI Club (PTNK):** academic advisor, R&D (2026–27).

---

## 💻 Toolkit

- **Languages:** Python · C++ · TypeScript · SQL
- **ML:** PyTorch · Hugging Face Transformers · scikit-learn · CatBoost · LightGBM · OpenCV · MediaPipe
- **Deployment:** OpenVINO · ONNX Runtime · FastAPI · Docker · Next.js · SQLite
- **Certifications:** AWS Machine Learning Foundations · Cisco Python Essentials 1 & 2
