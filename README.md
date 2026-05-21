# 📚 Research Paper Summarizer

Research Paper Summarizer is an AI-powered web application that generates concise and meaningful summaries of research papers based on the paper title, explanation style, and desired summary length. Built with Python, Streamlit, LangChain, and the Gemini API, the project helps users quickly understand academic topics without reading full research papers.

---

## 🚀 Features

- Generate summaries using only the research paper title
- Select different explanation styles
  - Beginner Friendly
  - Technical
  - Academic
  - Simple Explanation
- Customize summary length
  - Short
  - Medium
  - Detailed
- AI-powered summarization using Gemini API
- Interactive and clean Streamlit interface
- Fast and easy-to-use workflow

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit**
- **LangChain**
- **Google Gemini API**

---

## 📸 Demo

![alt text](Screenshot.png)

## Project Structure

Research_Paper_Summarizer/
│── prompt_generator.py
|── prompt_ui.py
│── README.md
│── requirements.txt
│── template.json
│── images/
│   └── Screenshot.png

⚙️ Installation

1️⃣ Clone the Repository

git clone https://github.com/your-username/research-paper-summarizer.git
cd research-paper-summarizer

2️⃣ Create Virtual Environment

python -m venv venv

3️⃣ Activate Virtual Environment

Windows

venv\Scripts\activate

macOS/Linux

source venv/bin/activate

📦 Install Dependencies

pip install -r requirements.txt

🔑 Setup Environment Variables

Create a .env file in the root directory and add your Gemini API key.

GOOGLE_API_KEY=your_api_key_here

▶️ Usage

Run the Streamlit application:

streamlit run app.py

Open the local URL displayed in the terminal:

http://localhost:8501

🧠 How It Works

1. Enter the research paper title
2. Choose the explanation style
3. Select the summary length
4. Gemini API processes the request
5. The generated summary is displayed instantly

📋 Requirements

Python 3.10+
pip
Internet connection
Gemini API Key
