# 🏆 Winner of the Council President's Award – Advanced Innovation Convergence University Program  
# SKINNOTT: AI-Powered Skin Diagnosis System for Children and Adolescents  
> **Team NOTT** <br/> **Development Period: 2024.06 ~ 2024.09** <br/> **Note: IRB Review Approved and Completed**

---

## 🧭 Project Slogan  
> **“A dermatologist in your hand.”**

---

## 📌 Project Overview

**SKINNOTT** is a mobile-based AI solution that provides **first-stage diagnosis of pediatric and adolescent skin diseases**. By combining **skin disease images** and **quantified skin condition metrics** (such as hydration, elasticity, and pore count), it supports users in identifying common skin issues early—before they become severe.  

It addresses a growing social issue: **the depletion of national health insurance funds**, which threatens to increase personal healthcare costs. Our app contributes to solving this by reducing unnecessary clinical visits and encouraging early, data-informed care decisions—especially for children and adolescents, who face access limitations and growing medical expenditures.

---

## 🩺 Why Focus on Pediatric Dermatology?

- **Rising costs**: Healthcare spending per child in dermatology is increasing faster than inflation.  
- **Underrated severity**: Skin diseases are often dismissed early, leading to worsening conditions.  
- **Critical detection gap**: Studies show delayed skin treatment (e.g., melanoma) drastically reduces survival rates.  
- **Access challenges**: Adolescents may miss clinic hours due to school, and pediatricians are declining in number.  
- **Need for lightweight triage**: There is a growing need for **pre-clinical diagnostic tools** that are accessible and trustworthy.

---

## 🧠 Solution Highlights

- **Mobile App (Android-based)**  
- **AI-powered Diagnosis (CNN-based classifier)**  
- **Skin Condition Analysis (Numerical parameter extraction)**  
- **GPT Integration (Follow-up care suggestions)**  
- **Data Collection Flow (IRB-approved, de-identified storage)**

---

## 🔬 Key Features

### 1. AI-Based Skin Disease Diagnosis  
- Users submit images of skin lesions.  
- A CNN-based classifier identifies likely conditions.  
- Results include diagnosis name, confidence level, and symptom description.

### 2. GPT-Based Follow-Up Recommendation  
- Through **ChatGPT API**, the app delivers user-friendly explanations and next-step care advice.

### 3. Skin Condition Monitoring  
- The app uses skin sensors or image-based estimation to track:  
  - **Hydration level**, **elasticity**, **pore density**, **skin type**, and **age group**.  
- This data is **stored per user (with consent)** and used for statistical analysis and future diagnosis enhancement.

### 4. Integrated Dataset Labeling  
- Unlike existing datasets where skin disease and skin condition are separated, SKINNOTT allows us to collect both types for the **same individual**, enabling unique insights into **condition-symptom correlations**.

---

## 💾 Datasets Used

| Dataset Type       | Description                          | Source        |
|--------------------|--------------------------------------|---------------|
| Skin Disease Images (Pediatric) | Disease-labeled images for children and adolescents | AI-Hub (Offline Safe Zone, IRB Approved) |
| Skin Condition Metrics          | Data on moisture, elasticity, pore count, etc.      | Commercial beauty skin scanners |
| Combined Dataset                | Self-collected via SKINNOTT app users               | Planned collection post-release |

---

## 🧪 Sample Analysis & Visualizations

### Skin Disease & Symptom Correlation  
- Preliminary visualizations (due to encoding errors, Korean labels may be corrupted):  
![image](https://github.com/user-attachments/assets/48457cdd-8446-4c5e-b4b9-80fb891fe52c)

### Skin Condition by Age/Gender  
- Collected skin state metrics show trends based on **age**, **gender**, and **body area**.  
![image](https://github.com/user-attachments/assets/05150a5a-b9da-40e4-a693-367b838718f5)  
![image](https://github.com/user-attachments/assets/87b6d49c-936f-4e5a-b4bc-a90a52cebef4)  
![image](https://github.com/user-attachments/assets/b0fc19c6-dee7-4d5f-88ea-b1b474ba6d63)

---

## 📲 App Flow

![flow](https://github.com/user-attachments/assets/8dc7e680-c262-42ea-b47e-49e3c9cd4fc4)

---

## 🧩 System Design

- **Frontend**: Android Kotlin (Material UI, Camera API, Graph Libraries)  
- **Backend**: Flask, SQLite  
- **AI**: CNN-based image classifier + GPT API  
- **Deployment**: Offline prototype with future expansion for beta testing

---

## 📈 Expected Outcomes

### Direct Impact
- **Reduce unnecessary dermatology visits**  
- **Encourage early detection and intervention**  
- **Relieve national health insurance system pressure**

### Indirect Impact
- **Enable medical research on pediatric dermatology**  
- **Provide structured healthcare logs per region for public health planning**  
- **Expand medical aesthetic market through quantified skin care insights**

---

## 🏗️ Future Roadmap

- Improve AI accuracy by integrating skin condition labels  
- Deploy public beta and collect user feedback  
- Add visual report features for caregivers and dermatologists  
- Explore sustainable business models (e.g., premium skin health report subscriptions)  
- Partner with local clinics, EdTech, and public health authorities

---

## 📚 References

- [AI-Hub Pediatric Skin Disease Dataset (Offline)](https://www.aihub.or.kr)  
- [KOSIS 2022: YouTube Consumption Data](https://kosis.kr)  
- [IRB Policy Info (NMC Bioethics)](https://www.nmc.or.kr)  

---

## 👨‍💻 Development Team – Team NOTT

| 서재오 (Jaeoh Seo) | 임한빈 (Hanbin Im) | 최재원 (Jaewon Choi) |
|-------------------|-------------------|---------------------|
| ![](https://avatars.githubusercontent.com/u/90062866?v=4) | ![](https://avatars.githubusercontent.com/u/123966795?v=4) | ![](https://avatars.githubusercontent.com/u/95406268?v=4) |
| [@seojaeohcode](https://github.com/seojaeohcode) | [@Hanbeeen](https://github.com/Hanbeeen) | [@ppre1ude](https://github.com/ppre1ude) |
| AI Dept, Chonnam National Univ. (3rd Year) | AI Dept, Chonnam National Univ. (3rd Year) | AI Dept, Chonnam National Univ. (3rd Year) |

---

## 🛡️ Legal & Ethics

- **IRB Approval**: Granted (Bioethics Committee, July 2024)  
- **Data Handling**: Fully anonymized with user consent  
- **App Classification**: Pre-diagnostic tool only (not a certified medical device)

---

## 📌 Acknowledgment

> This project was awarded the **Council President’s Prize** at the 2024 Advanced Innovation Convergence University Program (Bio-Health Track).

