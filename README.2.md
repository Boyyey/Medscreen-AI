# 🧠 MedScreen AI — Cancer Risk Assessment That Could Save Lives

Welcome to **MedScreen AI**, a cutting-edge AI-powered platform designed for **early cancer risk detection** using **biomarker analysis** and intelligent visualization. 🧬

🎯 This tool is **not just software** — it's a mission. A mission to **support early detection**, empower healthcare professionals, and ultimately, help save lives.

> ⚠️ **DISCLAIMER**: This is a clinical prototype designed for research and demonstration. It must **not** replace professional medical advice. All predictions must be interpreted by qualified physicians.

---

## 🔍 Why This Project Matters

Every year, millions of lives are affected by **late-stage cancer diagnosis**. Often, early warning signs are missed — not because they weren’t there, but because they weren’t understood in time.

**MedScreen AI** aims to bridge that gap by:
- Making biomarker data **understandable and actionable**
- Visualizing complex cancer risks in **simple, clear dashboards**
- Providing **AI-assisted support** for more confident clinical decisions

This tool empowers doctors and researchers to ask the right questions, **earlier**. Because in the fight against cancer, **time is everything.**

---

## 🚀 Features That Make a Difference

- ✅ **Multi-Cancer Risk Assessment**
  - Supports risk prediction for 7 types of cancer:
    - 🧬 Ovarian
    - 🦷 Pancreatic
    - 💪 Prostate
    - 💗 Breast
    - 💨 Lung
    - 🧻 Colorectal
    - 🫀 Liver

- 🔬 **Biomarker Intelligence**
  - Inputs 15+ key biomarkers like CRP, CA125, PSA, AFP, Hemoglobin & more
  - Real-time alerts for **abnormal or critical levels**

- 🧠 **AI Prediction Engine**
  - Uses `RandomForestClassifier` + `CalibratedClassifierCV` for precision probability estimation
  - Trained on synthetic medical data for demo purposes

- 📊 **Smart Visualizations**
  - Dynamic **risk bar graphs**
  - **Radar plots** for biomarker deviation
  - **3D molecular models** for select biomarkers

- 🗂️ **Patient Profiles**
  - Save medical history, biomarker entries, and generate **print-ready reports**

- 🔐 **Built-in Medical Guidelines**
  - Access curated clinical screening protocols

---

## 📈 Sample Biomarkers (with 3D Structures 🧬)

| 🧪 Biomarker | 📏 Unit | 🔥 Critical Level | 🔍 3D View |
|-------------|---------|-------------------|------------|
| CRP         | ng/L    | >10               | ✅ (1B09)   |
| CA125       | U/mL    | >35               | ✅ (3W2S)   |
| PSA         | pg/mL   | >4                | ✅ (2ZCH)   |
| AFP         | pg/mL   | >10               | ✅ (2LGV)   |
| Albumin     | g/dL    | <3.5              | ✅ (1AO6)   |

⚠️ More biomarkers are available in-app.

---

## 🖥️ How to Run:

python luad.file.2.py

🛠️ Built With:

Python, Tkinter, ttk

scikit-learn, NumPy, Pandas

matplotlib, seaborn

py3Dmol, PIL, tkinterweb

Optional: MDAnalysis, BioPython, imbalanced-learn

📚 Roadmap
🚧 Upcoming Features:

Genetic marker integration 🧬

Real-time patient monitoring via cloud ☁️

Web version with hospital dashboard 🏥

Integration with EHR/EMR systems 📁
