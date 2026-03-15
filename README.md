# ⚖️ Legal Lens AI

> **Understand any legal document in seconds — not hours.**

Legal professionals, students, and everyday people often face the same problem: legal documents are dense, complex, and time-consuming to understand. **Legal Lens AI** solves this by instantly extracting, summarizing, and voice-reading any legal PDF — in multiple languages — using AI.

---

## 🧩 The Problem → The Solution

| Problem | Legal Lens Solution | Result |
|---|---|---|
| Legal PDFs are unreadable walls of text | AI-powered extraction + structured summarization | Clear, plain-English summaries in **under 10 seconds** |
| Non-English speakers can't access legal content | Multilingual summarization via DeepSeek API | Summaries in the user's preferred language |
| Reading is slow or accessibility is limited | Voice synthesis via gTTS | Fully narrated document summaries, hands-free |

---

## 🚀 What It Does

**Legal Lens AI** is a Streamlit web app that takes any legal PDF and turns it into something a human can actually understand:

1. 📄 **Upload** — Drop in any legal PDF (contracts, court filings, terms of service, etc.)
2. 🤖 **Summarize** — The DeepSeek API extracts and summarizes the key clauses, obligations, and risks in plain language
3. 🌍 **Translate** — Get the summary in your chosen language
4. 🔊 **Listen** — Have the summary read aloud using text-to-speech (gTTS)

---

## 🛠️ Tech Stack

| Layer | Tool |
|---|---|
| Frontend / UI | [Streamlit](https://streamlit.io) |
| AI Summarization | [DeepSeek API](https://platform.deepseek.com) |
| PDF Extraction | Python PDF libraries |
| Voice Synthesis | [gTTS](https://pypi.org/project/gTTS/) (Google Text-to-Speech) |

---

## ⚙️ Getting Started

### Prerequisites
- Python 3.8+
- A [DeepSeek API key](https://platform.deepseek.com)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Yahiya-Analytics/Legal-Lens.git
cd Legal-Lens

# 2. Install dependencies
pip install -r requirements.txt

# 3. Set up your environment variables
cp .env.example .env
# Then open .env and add your DeepSeek API key:
# DEEPSEEK_API_KEY=your_key_here

# 4. Launch the app
streamlit run app.py
```

The app will open in your browser at `http://localhost:8501`.

---

## 📁 Project Structure

```
Legal-Lens/
├── app.py               # Main Streamlit application
├── requirements.txt     # Python dependencies
├── .env.example         # Environment variable template
└── README.md
```

---

## 🎯 Example Use Cases

- **Freelancers** reviewing client contracts before signing
- **Students** studying legal documents or case filings
- **Non-native English speakers** needing translated legal summaries
- **Accessibility users** who prefer audio over reading

---

## 🔑 Environment Variables

Create a `.env` file in the root directory:

```env
DEEPSEEK_API_KEY=your_deepseek_api_key_here
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repo
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add your feature'`
4. Push and open a PR

---

## 📄 License

This project is open source. See the [LICENSE](LICENSE) file for details.

---

## 👤 Author

Built by **[Yahiya Analytics](https://github.com/Yahiya-Analytics)**
