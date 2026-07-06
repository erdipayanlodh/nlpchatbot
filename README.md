# 🎓 CDAC College Chatbot

An AI-powered college chatbot built using **Python, Flask, TensorFlow, NLTK, and MySQL**. The chatbot answers common college-related queries such as faculty information, admissions, courses, departments, and other frequently asked questions through a simple web interface.

---
## 📊 Internship Report

The complete internship report explaining the project architecture, implementation, methodology, and results can be accessed here:

**📄 Internship Report**

https://drive.google.com/file/d/1_V6UO89tJXj4qj62PLCmkMTEdbdPp-1i/view?usp=sharing

---

## 🚀 Features

- 🤖 AI-based intent classification using TensorFlow
- 💬 Natural Language Processing (NLP) with NLTK
- 🗄️ MySQL database integration for dynamic responses
- 🌐 Flask web application
- 📚 Faculty information fetched directly from the database
- 🧠 Bag-of-Words based text preprocessing
- 🎯 Intent-based response generation
- 💻 Simple and user-friendly web interface

---

## 🛠️ Tech Stack

- Python
- Flask
- TensorFlow / Keras
- NLTK
- NumPy
- MySQL
- HTML
- CSS
- JavaScript

---

## 📂 Project Structure

```
chatbot/
│
├── app.py
├── training.py
├── intents.json
├── chatbot_model.h5
├── words.pkl
├── classes.pkl
├── README.md
│
├── templates/
│   └── index.html
│
├── static/
│   ├── style.css
│   └── script.js
│
└── venv/
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/cdac-chatbot.git
cd cdac-chatbot
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install flask tensorflow keras numpy nltk mysql-connector-python
```

---

## 📥 Download NLTK Resources

Run Python and execute:

```python
import nltk

nltk.download('punkt')
nltk.download('punkt_tab')
nltk.download('wordnet')
nltk.download('omw-1.4')
```

---


Update the database credentials inside `app.py` if required.

```python
host='localhost'
user='root'
password='your_password'
database='chatbot'
```

---

## 🧠 Train the Model

Run:

```bash
python training.py
```

This generates:

- chatbot_model.h5
- words.pkl
- classes.pkl

---

## ▶️ Run the Application

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

## 💬 Sample Questions

- Who are the faculty members?
- Tell me about admissions.
- What courses are offered?
- What departments are available?
- Hello
- Hi
- Thank you
- Bye

---

## 📦 Dependencies

- Flask
- TensorFlow
- Keras
- NumPy
- NLTK
- MySQL Connector Python

Install using:

```bash
pip install flask tensorflow keras numpy nltk mysql-connector-python
```

---

## 🔮 Future Improvements

- Student Login
- Attendance Module
- Result Information
- Timetable Integration
- Notice Board Updates
- Event Notifications
- Voice-based Interaction
- Admin Dashboard
- Deep Learning-based NLP (BERT/GPT)
- Deployment on Cloud

---

## 👨‍💻 Author

**Dipayan Lodh**

- GitHub: https://github.com/erdipayanlodh
- LinkedIn: https://www.linkedin.com/in/dipayan-lodh-855111212

---

## 📄 License

This project is developed for educational purposes and learning.
