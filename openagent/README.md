# 🌟 OpenAgent – AI Frontend Developer Assistant

This project is a simple and effective implementation of an AI agent using the [OpenAgent SDK](https://github.com/OpenAgent/openagent). The agent is designed to act like a **frontend development expert**, using Gemini 2.0 via a chat-compatible API.

---

## 🚀 Key Features

- ✅ Custom **AI Agent** with defined role and instructions  
- 🔁 Synchronous execution using `Runner.run_sync()`  
- 🔐 Environment-based API key loading via `dotenv`  
- 🤝 Powered by **Gemini 2.0 Flash** through OpenAI-compatible chat model  
- ⚙️ Easy to configure and extend for other roles

---

## 📁 Project Structure

```
openagent/
│
├── .env                # Environment variables (API key)
├── main.py             # Main Python script to run the agent
└── README.md           # Project documentation
```

---

## ⚙️ Setup Instructions



### 1. Create and Activate Virtual Environment

```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate
```

### 2. Install Required Packages

```bash
     uv init .
```

### 3. Add Your API Key

Create a `.env` file in the root directory and add your Gemini API key:

```
GEMINI_API_KEY= AIzaSyAsy6yBAb14nWhlwFafvINUZTAaLKY2S4I
```

---

## ▶️ Run the App

```bash
uv run main.py
```

You'll get a response from your AI agent to the input message `"Hello, how are you?"`.

---

## 💬 Example Output

```
Frontend Developer Agent: I'm doing great! How can I help you with frontend development today?
```

---

## 🛠 Tech Stack

- **Python 3**
- **OpenAgent SDK**
- **Gemini 2.0 Flash (chat-compatible model)**
- **python-dotenv**

---

## 📌 Use Cases

- Chat assistant for frontend developers  
- Learning tool for beginners in web development  
- Can be adapted for other roles (backend, designer, mentor, etc.) by changing instructions

---

## 👩‍💻 Author

**Neha Fahim**  
Frontend Developer | Educator | Content Writer  
🔗 [GitHub](https://github.com/NehaFahim) | [LinkedIn](https://linkedin.com/in/nehafahim)

---


