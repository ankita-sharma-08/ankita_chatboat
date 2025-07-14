# ankita_chatboat
Link for the chat bot
* https://ankitachatboat-doctor.streamlit.app/

#  Health Symptom Checker

A simple **Streamlit** web application that allows users to describe their symptoms and receive general health advice powered by **OpenAI GPT-3.5-turbo**.

---

##  Features

* Conversational interface using **Streamlit Chat UI**
* Session-based chat memory
* Uses **OpenAI's API** to provide general health remedies or advice
* Clean and intuitive interface for symptom input and response

---

##  Requirements

* Python 3.7+
* Streamlit
* OpenAI 

---

##  Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/health-symptom-checker.git
   cd health-symptom-checker
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Set up Streamlit secrets:**

   Create a `.streamlit/secrets.toml` file and add your OpenAI API key:

   ```toml
   [general]
   OPENAI_API_KEY = "your-openai-api-key"
   ```

---

##  How to Run

```bash
streamlit run streamlit_app.py
```

Once the app starts, open the provided local URL in your browser. You can now chat with the assistant by describing your symptoms.

---

##  How It Works

* The app listens for user input describing symptoms.
* It maintains a chat history using `st.session_state`.
* It sends the prompt (with symptoms) to the OpenAI API using the GPT-3.5-turbo model.
* It returns and displays a general remedy or health advice.

---

##  Disclaimer

This application is intended for **informational purposes only** and does **not** provide medical diagnosis or treatment. Always consult a qualified healthcare provider for professional medical advice.

---

##  Powered By

* [Streamlit](https://streamlit.io/)
* [OpenAI GPT-3.5-turbo](https://platform.openai.com/)
