## Title of the Project

**BioPrint: Smart Biometric-Based Blood Group Detection**

A smart, non-invasive biometric system that instantly predicts a person's ABO and Rh blood group using fingerprint patterns and deep learning techniques.

---

## About

BioPrint is an intelligent biometric-based blood group identification system designed to overcome the limitations of conventional blood typing methods. Traditional blood group detection requires invasive blood sample collection, laboratory testing, and skilled personnel, which leads to delays—especially in emergency medical situations.

This project leverages the scientific correlation between fingerprint dermatoglyphic patterns and genetically inherited blood groups. By using image processing and a Convolutional Neural Network (CNN), BioPrint predicts blood groups accurately within seconds using only a fingerprint scan. The system is non-invasive, cost-effective, portable, and suitable for deployment in emergency care units, blood donation camps, and remote healthcare centers.

---

# 🩸 BioPrint: Smart Biometric-Based Blood Group Detection

## ⚡️ Know Your Blood Group in Seconds—Just with a Touch.

This repository contains the code and resources for **BioPrint**, an intelligent, non-invasive system designed to predict a person's **ABO and Rh blood group** instantly using their unique **fingerprint patterns**. We leverage the power of Deep Learning to transform critical medical diagnostics, making blood typing faster, safer, and universally accessible.

-----

## ❓ Why This Project Is Necessary: The Problem in Diagnostics

In emergency medicine and trauma care, **time is the most critical resource**. Traditional methods for blood group identification create dangerous and costly delays:

1. **The Critical Wait Time:** Conventional blood typing requires drawing blood, transporting it, and running complex serological tests in a lab. This process can take **30 minutes or more**, causing fatal delays where instant transfusion decisions are needed.
2. **Invasive & Resource-Heavy:** The process requires needles, syringes, chemical reagents, and specialized lab equipment. This makes testing difficult, costly, and sometimes unavailable in remote areas or disaster zones.
3. **Risk of Human Error:** Manual handling of samples and visual interpretation increases the risk of misdiagnosis, which is unacceptable for patient safety.

**BioPrint solves this by replacing the lab and the needle with an advanced AI algorithm.**

-----

## 🔬 How The System Works: The AI-Driven Solution

The BioPrint system is built on the scientific correlation between an individual's unique **dermatoglyphic patterns** (fingerprint features) and their genetically determined blood group.

1. **Capture (The Biometric Input):** A high-resolution **biometric scanner** non-invasively captures a digital image of the user’s fingerprint.
2. **Clean (The Image Processing Pipeline):** The image is instantly processed using techniques like **Grayscale Conversion** and **Noise Reduction** (e.g., Gabor filtering).
3. **Predict (The CNN Core):** The cleaned image is fed into a specialized **Convolutional Neural Network (CNN)** trained on labeled fingerprint datasets.
4. **Instant Result:** The blood group prediction is delivered in **just a few seconds**.

---

## Features

- Implements advanced **Convolutional Neural Network (CNN)** architecture for classification.
- Non-invasive and needle-free biometric-based identification.
- Fast prediction with low time complexity.
- High scalability and portability for real-world deployment.
- Secure identification using unique fingerprint patterns.
- Framework-based application suitable for web deployment.

---

## Requirements

* **Operating System:** 64-bit Windows 10 / Ubuntu
* **Development Language:** Python 3.8 or later
* **Deep Learning Frameworks:** TensorFlow / Keras
* **Image Processing Library:** OpenCV
* **Version Control:** Git and GitHub
* **IDE:** Visual Studio Code
* **Additional Dependencies:** NumPy, scikit-learn, Flask (if API-based deployment is used)

---

## System Architecture

<!-- Embed system architecture diagram here -->

<img width="957" height="508" alt="image" src="https://github.com/user-attachments/assets/3fe2741f-b869-46f8-b2e7-33ea2e1ea142" />

---

## Output

#### Output 1 – Fingerprint Capture Interface

<img width="682" height="326" alt="image" src="https://github.com/user-attachments/assets/21439b0e-72be-48d8-ad3d-231994b64769" />

#### Output 2 – Blood Group Prediction Result

<img width="555" height="343" alt="image" src="https://github.com/user-attachments/assets/61e295c8-a752-4baa-8832-a4514073af0e" />



---

## 💻 Tech Stack

| Component | Technology |
|--------|------------|
| Deep Learning | Python, TensorFlow / Keras |
| Image Processing | OpenCV |
| Backend | Python / Flask |
| Hardware | Biometric Fingerprint Scanner |
| Deployment | Web-based Interface |

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Fingerprint dataset mapped to blood groups
- Required Python libraries

### Installation and Setup

```bash
# 1. Clone the repository
git clone *repo_name*
cd smart-biometric-based-blood-group-detection

# 2. Install dependencies
pip install -r requirements.txt

# 3. Training the model (if starting from scratch)
# Ensure your dataset is configured correctly before running.
python train_model.py

# 4. Run the prediction application (API or UI)
python app.py
```

-----
## Live Link :
https://smart-biometric-based-blood-group-d.vercel.app/
## 🤝 Contribution & Team

We welcome suggestions and contributions\! Please feel free to fork the repository and submit a pull request if you want to help improve the model accuracy, expand the dataset, or enhance the user interface.

**Project Team Members:**

  * **JOSHITHA Y** (Project Design, Integration, and Testing)
  * **POOJASREE B** (Project Coding Module 1, Execution)
  * **SANJANA R** (Project Coding Module 2, Execution)

*Developed for the Mini Project at Saveetha Engineering College.*
