# 🏥 4-PILLAR CLINICAL ASSESSMENT MODEL (4-PCAM)

**Developer(s):**  
Dr. Smitrajsinh Jadeja, Dr. Anirudh Bhatt, Dr. Yogesh Valaki, Dr. Diksha Kanani  
**Guided By:**  
Dr. Prakash Kumbar  

---

## 📌 Overview

The **4-PILLAR CLINICAL ASSESSMENT MODEL (4-PCAM)** is an **Ayurvedic diagnostic and scoring tool** designed to help clinicians perform structured assessments of patients based on the classical Ayurvedic approach.

It evaluates a patient across **four key pillars**:

1. **Agni Dusti** – Digestive Fire Assessment  
2. **Dosha Dusti** – Constitutional Assessment  
3. **Dhatu Dusti** – Tissue Assessment (Framework ready)  
4. **Srotas Dusti** – Channel Assessment (Framework ready)  

---

## ✨ Features

- **Patient Record Entry Form** – Basic demographic & clinical details.
- **Step-by-Step Pillar Assessment** – Each pillar unlocks after the previous one is completed.
- **Agni Dusti Assessment** – Interactive symptom-based scoring system.
- **Dosha Dusti Assessment (NEW)**:
  - Each parameter has **severity buttons**:  
    `0 = Normal`, `1 = Mild`, `2 = Marked Abnormality`
  - Live score calculation for **Vata**, **Pitta**, **Kapha**
  - Severity interpretation shown dynamically
  - Max 20 points per dosha
- **Progress Tracking** – Visual progress bar & completion status.
- **Final Report Generation** – Summary of all completed pillars.
- **Responsive UI** – Works on desktop and mobile devices.

---

## 📂 Project Structure

---

## 🚀 How It Works

### 1. **Patient Information**
Before starting, the user must fill:
- Patient Name
- Age/Sex
- Chief Complaints  
(If incomplete, Pillar 1 remains locked)

### 2. **Pillar Navigation**
- Start with **Agni Dusti**  
- Completing a pillar unlocks the next one
- Pillar 4 completion generates the **final report**

### 3. **Agni Dusti**
- Click on the symptom cell that best describes the patient
- One selection per parameter
- Scores update automatically

### 4. **Dosha Dusti (Enhanced)**
- For each symptom:
  - Click severity: **0**, **1**, or **2**
  - Color-coded severity indicators
  - Live scores for **Vata**, **Pitta**, **Kapha**
  - “Complete Assessment” button activates only when all parameters are scored

### 5. **Final Report**
- Shows all scores and interpretations for Agni & Dosha (Dhatu and Srotas pending full implementation)
- Ready to print

---

## 🛠️ Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/meditool.git

