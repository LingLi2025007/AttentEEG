# 🧠 EEG-Based Attention State Monitoring and Digital Interventions for English Learners in Public Health Education

## 🌐 Project Overview

The integration of **EEG-based attention state monitoring** with **digital interventions** offers a transformative approach to enhancing **public health education**, particularly for **English learners**. Public health education is crucial for promoting individual and community well-being; however, traditional frameworks often struggle to address the diverse **cognitive** and **linguistic** needs of learners.

**Non-native English speakers** face challenges such as:  
- 🌐 **Language Barriers**  
- 🧠 **Cognitive Overload**  
- 🚧 **Cultural Differences**  
- 📉 **Low Engagement & Knowledge Retention**  

To overcome these challenges, we introduce a novel framework that **personalizes** and **adapts** content delivery based on learners' **real-time attention states**.

### 🚀 **Our Framework Combines Two Key Components:**

1. **Attention Dynamics Learning Model (ADLM)**  
   - 📡 **EEG-based monitoring** to track real-time fluctuations in attention.  
   - 📊 **Dynamic attention state analysis** to identify optimal learning periods.  

2. **Adaptive Attention Feedback Mechanism (AAFM)**  
   - 🔍 **Personalized feedback delivery** based on cognitive state.  
   - 🧠 **Adaptive content adjustments** for improved learning outcomes.  

**🎯 Goal:** To **improve engagement, comprehension, and retention** of public health information among English learners through adaptive, attention-aware digital interventions.

---

## 🎯 Key Features

- 🧠 **EEG-Based Attention Monitoring:** Tracks learners' attention levels in real-time.  
- ⚙️ **Adaptive Content Delivery:** Adjusts pace, complexity, and modality based on cognitive state.  
- 🌍 **Linguistic Adaptation:** Tailors content for English learners based on language proficiency.  
- 📊 **Real-Time Feedback:** Provides immediate and meaningful feedback to maintain engagement.  
- 🔍 **Cross-Cultural Sensitivity:** Ensures content is accessible to diverse audiences.  
- 📡 **User-Friendly Interface:** Interactive and intuitive dashboard for educators and researchers.  

---

## 🧠 System Architecture

The system consists of four interconnected modules:

### 1️⃣ **EEG Data Acquisition Module**  
- **Hardware:** EEG headsets (e.g., Muse 2, OpenBCI).  
- **Signal Processing:** Noise filtering, artifact removal (e.g., eye blinks, muscle movement).  

### 2️⃣ **Attention State Analysis Engine (ADLM)**  
- **Feature Extraction:** Power spectral density, theta-beta ratio, and engagement indices.  
- **Model:** Attention state prediction via **LSTM** and **CNN-based classifiers**.  

### 3️⃣ **Adaptive Feedback Controller (AAFM)**  
- **Feedback Mechanism:** Personalized cues and content adjustments.  
- **Algorithms:** Reinforcement learning for dynamic content adaptation.  

### 4️⃣ **Interactive Dashboard (User Interface)**  
- **Visualization:** Real-time attention graphs and learning progress.  
- **User Interaction:** Simple interface for educators to track learner performance.  

---

## ⚙️ Installation Guide

### 🛠️ **Prerequisites**

- Python 3.9+  
- PyTorch / TensorFlow  
- OpenBCI SDK (for EEG integration)  
- NumPy / SciPy / Pandas  
- Matplotlib / Plotly / Streamlit  

### 🖥️ **Installation Steps**

1. **Clone the Repository**
    ```bash
    git clone https://github.com/your-username/EEG-Attention-PublicHealthEdu.git
    cd EEG-Attention-PublicHealthEdu
    ```

2. **Create a Virtual Environment**
    ```bash
    python -m venv venv
    source venv/bin/activate    # Linux/macOS
    .\venv\Scripts\activate     # Windows
    ```

3. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4. **Verify Installation**
    ```bash
    python main.py --test
    ```

---

## 🚀 Quickstart Guide

### 🧠 **Run Real-Time EEG Monitoring**
```bash
python main.py --mode monitor
