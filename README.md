# 🌍 LinguaMood — Mapping Global Emotions through Language & Culture
<img width="1024" height="1024" alt="ChatGPT Image Jul 11, 2025, 11_41_02 PM" src="https://github.com/user-attachments/assets/747c14ee-9427-4b7e-adbb-ae5dae814e0b" />

LinguaMood is a unique AI-powered platform that detects how different cultures emotionally express themselves across languages. Using multilingual NLP, emotion lexicons, and real-world social data, LinguaMood builds a global emotional map — uncovering how people from different countries *feel, speak,* and *express*.

---

## 📌 Project Highlights

- 🌐 Multilingual Emotion Detection using Transformers (mBERT, XLM-R)
- 🧠 Cultural Emotion Fingerprints (emotion + region analysis)
- 🔍 Real-world Data (YouTube/Reddit comments, WHO reports)
- 📊 Interactive Dashboard (map + charts)
- 🧪 “What-if” Emotion Simulation based on policy changes

---

| Feature                                              | Why It’s Different & Valuable                                                                                                                          |
| ---------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 🌐 **Multilingual + Multicultural Emotion Modeling** | You detect *how people from different cultures emotionally express themselves* — this hasn’t been done practically across languages with transformers. |
| 🧠 **Cultural Emotion Fingerprint**                  | Not just sentiment — you cluster countries by *how they feel and express specific emotions*, e.g. *"grief in Japan vs. grief in Brazil"*.              |
| 🔁 **Live Data from YouTube/Reddit**                 | You bring *real-world emotion* in response to real events (elections, holidays, sports).                                                               |
| 📊 **Emotion + Policy Simulation**                   | What happens if a country increases mental health spending? You simulate emotional impact — *that’s innovation*.                                       |
| 📍 **Interactive Emotion Map**                       | You let users **explore how cultures express emotion**, not just read scores. Think "Spotify Wrapped" for national emotions.                           |                                                   
| 🧪 **Open-source + Expandable**                      | You're packaging it as a clean, reproducible GitHub repo for future research or startup prototypes.                                                    

---


## 🧱 Folder Structure

<img width="838" height="652" alt="Screenshot 2025-07-11 234753" src="https://github.com/user-attachments/assets/e73390bd-55c3-4152-8b2e-57b85fba66ae" />




## 🔄 Workflow Overview

Here’s how LinguaMood works step-by-step:

### 🔁 Step 1: Collect & Preprocess Data
- YouTube & Reddit multilingual comments per country
- World Happiness & Mental Health Statistics (WHO, UN)
- Emotion Lexicons (NRC)

### 🔍 Step 2: Detect Emotions
- Use `mBERT` or `XLM-RoBERTa` to tag emotions
- Combine with NRC lexicon for hybrid sentiment scoring

### 🌎 Step 3: Map Cultural Fingerprints
- Aggregate emotions per country, cluster emotion styles
- Analyze topics: e.g., joy in festivals vs. grief in politics

### 🧪 Step 4: Predictive Simulation
- Model future emotion trends using policy inputs (e.g., increase mental health budget)

### 📊 Step 5: Dashboard Visualization
- Interactive dashboard with maps, charts, and simulation tools (Streamlit )

---

## 📊 Pipeline Diagram (ASCII Preview)


          +----------------------+
          |  Social Media Data   |
          | (YouTube, Reddit)    |
          +----------+-----------+
                     |
                     v
       +-----------------------------+
       | Language Detection & Filter |
       +-----------------------------+
                     |
                     v
       +-----------------------------+
       | Emotion Detection (XLM-R)   |
       | + NRC Emotion Lexicon       |
       +-----------------------------+
                     |
                     v
       +-----------------------------+
       | Cultural Aggregation & Map  |
       +-----------------------------+
                     |
         +-------------------+-----------------+
         |                   |                 |
         v                   v                 v
    Geo Dashboard     Topic Insights     Simulation (RL)



| Type       | Stack / Tools                                   |
| ---------- | ----------------------------------------------- |
| Language   | Python 3.10+                                    |
| NLP Models | XLM-RoBERTa, mBERT, GoEmotions, DeBERTa         |
| Data Viz   | Plotly, Streamlit, Geopandas, Cursur.ai         |
| ML Tools   | Scikit-learn, Pandas, HuggingFace, Transformers |
| Dashboard  | Streamlit / Cursur                              |
| Deployment | (Optional) Docker / Cloud (GCP, AWS)            |


# 1. Clone the repo
git clone https://github.com/2KRISHNAYADAV/LinguaMood.git
cd LinguaMood

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install requirements
pip install -r app/requirements.txt

# 4. Run dashboard
streamlit run app/dashboard.py


## 🚀 How to Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/yourusername/LinguaMood.git
cd LinguaMood

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install requirements
pip install -r app/requirements.txt

# 4. Run dashboard
streamlit run app/dashboard.py
```

Or deploy agents in **Cursur.ai** using the `agents/` folder.

---

## 📈 Future Scope

* 🌍 Expand to voice emotion analysis (Wav2Vec + XLS-R)
* 🎙️ Detect emotion from multilingual podcasts and radio
* 🤖 RL-based emotion optimizer agent
* 🧠 Fine-tune cultural emotion model on native datasets

---

## 🙏 Credits

* HuggingFace Transformers
* WHO Global Data Observatory
* NRC Emotion Lexicon by Saif Mohammad
* Kaggle & Reddit multilingual corpora

---

## 📄 License

This project is licensed under the **MIT License**. Feel free to use and contribute!

---

## ⭐ Contribute & Share

If you like this project, give it a ⭐ on GitHub and share it with your community! PRs and feature ideas are always welcome.



