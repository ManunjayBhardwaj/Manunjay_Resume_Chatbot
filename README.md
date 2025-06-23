
# 🤖 Manunjay Bhardwaj – Persona Chatbot

Working Link: https://manunjay-resume-chatbot.streamlit.app

Hi! Kaise ho! I’m Manunjay Bhardwaj — and this is a fully personalized AI chatbot that talks like me, thinks like me, and responds only about my background, skills, projects, education, and experiences.

This bot uses the Groq API with the blazing-fast **LLaMA3-8B** model to deliver real-time answers — built entirely using Python and Streamlit.

---

## 🧠 Features

- 💬 First-person responses — as if you're chatting with Manunjay himself  
- ❌ Strictly rejects any non-personal questions (e.g., coding help, math, news, etc.)  
- 🧱 Based on hardcoded system prompt containing verified resume data only  
- 🔒 No hallucinations — responds only with facts present in the prompt  
- ⚡ Powered by [Groq](https://groq.com) + OpenAI-compatible API with LLaMA3

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Groq API (OpenAI-compatible)
- LLaMA3-8B model
- dotenv for environment variables

---

## 🚀 How to Run Locally

1. **Clone the repository**  
```bash
git clone https://github.com/ManunjayBhardwaj/persona-chatbot.git
cd persona-chatbot
```

2. **Install dependencies**  
```bash
pip install -r requirements.txt
```

3. **Set up your `.env` file**  
Create a `.env` file with your Groq API key:
```
GROQ_API_KEY=your_groq_api_key_here
```

4. **Run the app**  
```bash
streamlit run app.py
```

---

## 📁 Project Structure

```
├── app.py              # Streamlit app
├── .env                # Your API key (not committed)
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
```

---

## 🙋‍♂️ About Me

I'm Manunjay Bhardwaj — an aspiring AI/ML engineer, currently pursuing B.E. in Computer Engineering at TIET, Patiala.  
You can reach out here:

- 📧 Email: manunjay09@gmail.com  
- 🌐 Portfolio: [manunjaybhardwaj.netlify.app](https://manunjaybhardwaj.netlify.app/)  
- 💼 LinkedIn: [linkedin.com/in/manunjaybhardwaj](https://linkedin.com/in/manunjaybhardwaj)  
- 💻 GitHub: [github.com/ManunjayBhardwaj](https://github.com/ManunjayBhardwaj)  

---

## ⚠️ Disclaimer

This chatbot is limited to answering only questions about **Manunjay Bhardwaj**.  
It will refuse any unrelated queries like code help, math problems, news, or general AI explanations.

---
