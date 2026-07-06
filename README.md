# 🤖 Codle AI

> **AI-Powered Coding Mentor & Polyglot Code Translator**

Codle AI is a premium AI-powered developer platform built with **Python**, **Gradio**, and the **Hugging Face Inference API**. It helps developers understand, translate, and analyze code through an elegant glassmorphic interface with interactive visualizations.

---

## ✨ Features

### 🔍 AI Code Explanation
- AI-powered code explanations
- Bug detection
- Time & Space complexity analysis
- Explain Like I'm 10 (ELI5) mode
- Beautiful markdown reports

### 🔄 Code Translation
Translate code between multiple programming languages:

- Python
- JavaScript
- TypeScript
- Java
- C
- C++
- C#
- Go
- Rust

Each translation includes:
- Converted code
- Translation explanation
- Key language differences
- Optimization suggestions

### 📈 Complexity Analyzer
- Automatic Time Complexity detection
- Space Complexity analysis
- Complexity Class identification
- Interactive Big-O visualization
- Animated complexity dashboard

### 🎨 Premium UI
- Neon Aurora Dark Theme
- Glassmorphism design
- Interactive particle background
- Keyboard shortcuts
- Command palette
- Toast notifications
- Smooth animations

---

# 🛠 Tech Stack

| Category | Technology |
|----------|------------|
| Language | Python |
| UI Framework | Gradio |
| AI | Hugging Face Inference API |
| Styling | HTML5 + CSS3 |
| Frontend | JavaScript |
| Visualization | HTML5 Canvas |
| Environment | python-dotenv |

---

# 📁 Project Structure

```
codle_ai/
│
├── app.py
├── utils.py
├── prompts.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── assets/
│   ├── styles.css
│   ├── codle.js
│   └── logo.png
│
└── _verify.py
```

---

# 🚀 Installation

## 1. Clone the repository

```bash
git clone https://github.com/prajju661/codle_ai.git
cd codle_ai
```

---

## 2. Create a virtual environment

### Windows

```powershell
python -m venv venv
.\venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 4. Configure Environment Variables

Create a `.env` file in the project root.

```env
HF_TOKEN=hf_your_huggingface_token
```

> **Important**
>
> Never commit your `.env` file to GitHub.

---

## 5. Run the application

```bash
python app.py
```

The application will start locally at:

```
http://127.0.0.1:7860
```
# 🔐 Security

- HF_TOKEN is never hardcoded
- Token is loaded securely from environment variables
- No secrets are exposed to the frontend
- No secrets are logged
- Application validates configuration before startup

---

# ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| Ctrl + Enter | Analyze Code |
| Ctrl + K | Clear Editor |
| Ctrl + S | Export Markdown Report |
| Ctrl + Shift + C | Copy Report |
| Ctrl + / | Open Command Palette |

---

# 📷 Screenshots

You can add screenshots here after deployment.

Example:

```
screenshots

home
explain
translate
complexity
```

---

# 📌 Supported Languages

- Python
- JavaScript
- TypeScript
- Java
- C
- C++
- C#
- Go
- Rust

---

# 👩‍💻 Author

** Srisailam Prajvalitha **

GitHub:
https://github.com/prajju661
huggung face:

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.
