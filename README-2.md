# Persona Chatbot

This project is a **persona-based chatbot** built with **Streamlit** and **Gemini (google-generativeai)**.  
It allows you to chat with a predefined persona and leverages the power of LLMs to provide contextual responses.

## 🚀 Features
- Streamlit frontend for chatbot UI.
- Integration with Google Generative AI (Gemini).
- Persona-based responses with customizable system prompt.
- Easy deployment.

## 📦 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/persona-chatbot.git
   cd persona-chatbot
   ```

2. Create a virtual environment (recommended):
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # On Windows use .venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## ▶️ Running the App

```bash
streamlit run main.py
```

The app will start locally, and you can access it in your browser.

## ⚙️ Environment Variables

You need to set your **Gemini API key** before running the app:

```bash
export GOOGLE_API_KEY="your_api_key_here"
```

On Windows (PowerShell):

```powershell
$env:GOOGLE_API_KEY="your_api_key_here"
```

## 📁 Project Structure

```
persona-chatbot/
│── main.py              # Streamlit app entry point
│── requirements.txt     # Dependencies
│── README.md            # Documentation
│── uv.lock / pyproject.toml (if using uv or poetry)
```

## 🛠️ Dependencies

- streamlit
- openai
- google-generativeai

## ⚡ Notes

- If you are using **uv.lock** or **pyproject.toml**, Streamlit Cloud may try to prioritize them over `requirements.txt`.  
  If installation fails, try removing `uv.lock` and rely only on `requirements.txt`.

---
💡 Built with ❤️ using **Streamlit** and **Gemini API**.
