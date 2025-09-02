# 🧠 MedBot – AI Mental Health Support Agent

MedBot is an AI-powered mental health support assistant built with **LangChain**, **Groq LLMs**, and custom tools for therapy guidance, emergency intervention, and therapist recommendations.  
It is designed to provide empathetic, evidence-based support while prioritizing user safety.

---

## ✨ Features
- 🤝 **Conversational Mental Health Guidance** using MedGemma model  
- 📍 **Find Nearby Therapists** based on user location  
- 🚨 **Emergency Escalation** with Twilio call integration for crisis situations  
- 🔗 Powered by **LangChain + LangGraph + Groq LLMs**  
- 🛡️ System prompt ensures safety, empathy, and vigilance  

---

### 1. Clone Repository

git clone https://github.com/yourusername/med_bot.git

cd med_bot

### 2. Create & Activate Virtual Environment
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows

### 3. Install Dependencies
pip install -r requirements.txt

### 4. Add Configuration

Create a .env file or edit config.py with:

GROQ_API_KEY = "your-groq-api-key"

TWILIO_ACCOUNT_SID = "your-twilio-account-sid"

TWILIO_AUTH_TOKEN = "your-twilio-auth-token"

TWILIO_PHONE_NUMBER = "+1xxxxxxxxxx"

### 5. Run MedBot
python main.py



## 👤 Author
**Siddharth Bhimpure**  
- 🎓 B.Tech in AI & Data Science  
