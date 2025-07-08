# SQLMe – Gemini AI Powered SQL Assistant

This project is a Streamlit-based app that leverages Google Gemini (via `google.generativeai`) to provide AI-powered answers for SQL and database-related questions.

---

## 🚀 Features

- Integrates Google Gemini AI (Generative AI)
- Uses Streamlit for a clean web interface
- Environment-variable-based authentication
- SQL/database question and answer system

---

## 📦 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/sqlme.git
cd sqlme



python3 -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
Make sure the requirements.txt includes:

nginx
Copy
Edit
streamlit
google-generativeai
python-dotenv
