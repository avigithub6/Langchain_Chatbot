# Langchain Chatbot with OpenAI API

## 📌 Project Overview
This project is a **Streamlit web application** that integrates **Langchain and OpenAI's GPT-3.5 Turbo** to create an interactive chatbot. Users can input a query, and the AI model will generate responses dynamically.

---

## 🚀 Features
- **Interactive Chatbot**: Uses OpenAI's GPT-3.5 Turbo for generating responses.
- **Streamlit UI**: User-friendly interface for seamless interaction.
- **Langchain Integration**: Structured prompt handling with Langchain.
- **Environment Variable Support**: API keys are securely managed using `.env`.

---

## 📂 Files in Repository
- **app.py**: The main application script.
- **.env**: Stores API keys (not included in the repo).
- **requirements.txt**: Lists required Python dependencies.
- **README.md**: Documentation for setup and usage.

---

## 🛠️ Technologies Used
- **Python**
- **Streamlit** (UI Framework)
- **Langchain** (Prompt Handling & AI Integration)
- **OpenAI API** (GPT-3.5 Turbo)
- **Dotenv** (Environment Variable Management)

---

## 🔧 Installation & Setup

1️⃣ **Clone the Repository**
```sh
git clone https://github.com/yourusername/langchain-chatbot.git
cd langchain-chatbot
```

2️⃣ **Create a Virtual Environment** (Recommended)
```sh
python -m venv myenv
```

3️⃣ **Activate the Virtual Environment**
- **Windows (PowerShell):**
  ```sh
  myenv\Scripts\Activate.ps1
  ```
- **Mac/Linux:**
  ```sh
  source myenv/bin/activate
  ```

4️⃣ **Install Dependencies**
```sh
pip install -r requirements.txt
```

5️⃣ **Set Up API Key**
- Create a `.env` file and add:
  ```sh
  OPENAI_API_KEY=your_actual_openai_api_key_here
  LANGCHAIN_API_KEY=your_actual_langchain_api_key_here
  ```

6️⃣ **Run the Application**
```sh
streamlit run app.py
```

---

## 📸 How It Works
1. **Enter a topic or question in the text input field.**
2. **Click 'Enter'** to submit the query.
3. **View AI-generated responses** based on the input.

---

## ⚠ Troubleshooting
### 1️⃣ API Key Not Found
Check if `.env` contains a valid API key and restart VS Code.
```sh
import os
print(os.getenv("OPENAI_API_KEY"))
```

### 2️⃣ Streamlit App Not Running
Make sure you are in the correct project folder and run:
```sh
streamlit run app.py
```

---

## 📜 License
This project is **open-source** under the MIT License.

---

## 🤝 Contributing
Pull requests are welcome! Feel free to submit issues and feature requests.

---

