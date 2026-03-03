# 🎓 AI Career Guidance Chatbot

An intelligent AI-powered Career Guidance Chatbot built using Flask and Google Gemini API.  
The system provides personalised career advice, skill recommendations, and learning pathways based on user input.

---

## 🚀 Features

- 🤖 AI-powered career advice using Gemini 2.5 Flash
- 💬 Interactive chat interface
- 🧠 Context-aware responses
- 🔐 Secure API key management using environment variables
- 🌐 REST API backend with Flask
- 🎯 Designed for real-time student career guidance

---

## 🛠 Tech Stack

- Python 3
- Flask
- Google Gemini API
- HTML / CSS
- JavaScript (Fetch API)
- dotenv (Environment management)

---

## 📂 Project Structure
project/
│
├── app.py
├── templates/
│ └── index.html
├── static/
│ └── style.css
├── .env (not uploaded)
├── .gitignore
└── README.md


---

## 🔐 Environment Setup

Create a `.env` file in the root directory:


GOOGLE_API_KEY=your_api_key_here


⚠️ Never upload the `.env` file to GitHub.

---

## ▶️ How to Run

1. Clone the repository:


git clone https://github.com/devruhul/career_chatbot_backend


2. Navigate into the folder:


cd your-repo-name


3. Install dependencies:


pip install -r requirements.txt


4. Run the application:


python app.py


5. Open in browser:


http://127.0.0.1:5000/


---

## 🧠 Model Used

`models/gemini-2.5-flash`

Selected for its balance between:
- Low latency
- Strong reasoning capability
- Cost efficiency
- Real-time conversational performance

---

## 🎯 Project Purpose

This project was developed as part of a Computer Science coursework to demonstrate:

- API integration
- Backend development
- Secure credential handling
- AI system design
- Full-stack application structure

---

## 🔒 Security Practice

- API keys stored in `.env`
- `.env` added to `.gitignore`
- Sensitive credentials never committed to repository

---

## 📈 Future Improvements

- User authentication system
- Conversation history storage (database)
- Career roadmap PDF generation
- Deployment to cloud platform (Render / Railway)
- UI/UX enhancement

---

## 👨‍💻 Author

Ruhul Amin  
BSc Computer Science & Cyber Security Student

---

## 📜 License

This project is for educational purposes.