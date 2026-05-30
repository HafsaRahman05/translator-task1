# 🌐 Urdu to English Translator Agent (Gemini + OpenAI Agents)

An AI-powered translator built using **Gemini API (OpenAI-compatible)** and the **Agents framework**.  
This project translates Urdu text into English using an automated agent pipeline.

---

## 🎯 Objective

To build an AI translator that:

- Takes Urdu input text
- Uses Gemini 2.0 Flash model via OpenAI-compatible API
- Processes translation using an Agent system
- Outputs accurate English translation

---

## 🚀 Features

✅ Urdu to English translation  
✅ Powered by Gemini 2.0 Flash model  
✅ Agent-based architecture  
✅ Secure API key handling using `.env`  
✅ OpenAI-compatible API integration  
✅ Synchronous execution using Runner  
✅ Lightweight and fast response  

---

## 🛠️ Technologies Used

- Python 3.x  
- Gemini API (Google Generative AI)  
- OpenAI-compatible SDK (`AsyncOpenAI`)  
- Agents Framework  
- dotenv (.env file handling)  

---

## 📁 Project Structure

```text
translator-task1/
│
├── main.py              # Main translator agent script
├── .env                 # API key storage (not shared)
├── requirements.txt     # Dependencies
└── README.md            # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/HafsaRahman05/translator-task1.git
cd translator-task1
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Setup Environment Variables

Create a `.env` file:

```env
GEMINI_API_KEY=your_api_key_here
```

---

## ▶️ How to Run

```bash
python main.py
```

---

## 🔄 How It Works

1. Load API key from `.env`
2. Initialize Gemini model using OpenAI-compatible client
3. Create a Translator Agent with instructions:
   - "translate Urdu to English"
4. Send Urdu text input to the agent
5. Get translated English output

---

## 🧠 Example Input

```
میرا نام علی ہے اور میں ایک سافٹ ویئر انجینئر ہوں۔
```

## 📤 Example Output

```
My name is Ali and I am a software engineer.
```

---

## 🌍 Deployment

This project can be extended for deployment using:

- Flask / FastAPI backend
- Streamlit UI
- Docker container
- Cloud deployment (Render / AWS / Vercel backend)

---

## 👩‍💻 Author

**Hafsa Rahman**  
Software Engineering Student  
Interested in AI, Machine Learning & Full Stack Development  

---

## ⭐ Future Improvements

- Add multi-language support (English, Arabic, French, etc.)
- Build Streamlit web interface
- Add voice-to-text translation
- Improve accuracy with prompt tuning
- Deploy as public API service

---
