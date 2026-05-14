# 🤖 AI TOEFL Simulator

Simulasi tes TOEFL online gratis dengan analisis berbasis AI. Latihan Listening, Structure, dan Reading untuk persiapan TOEFL ITP.

## ✨ Fitur

### 📚 Practice Modes
- **🎧 Listening** — Latihan listening dengan audio TTS
- **✍️ Structure** — Latihan grammar dan struktur kalimat
- **📖 Reading** — Latihan reading comprehension
- **🚀 Full Test** — Simulasi tes TOEFL lengkap

### 🤖 AI-Powered Features
- **Penjelasan per Soal** — Analisis otomatis untuk setiap jawaban
- **Performance Analysis** — Analisis performa dengan rekomendasi belajar
- **Question Generator** — Generate soal baru dengan AI
- **AI Scoring** — Skor otomatis untuk writing/speaking

### 📊 Practice Sets
| Set | Level | Listening | Structure | Reading |
|-----|-------|-----------|-----------|---------|
| 1 | Beginner | 10 | 10 | 10 |
| 2 | Medium | 20 | 20 | 20 |
| 3 | Advanced | 30 | 30 | 30 |
| 0 | Mixed Full | 50 | 40 | 50 |

## 🚀 Quick Start

### 1. Clone Repository
```bash
git clone https://github.com/YOUR_USERNAME/ai-toefl-simulator.git
cd ai-toefl-simulator
```

### 2. Open di Browser
```bash
# Langsung buka index.html di browser
# Atau gunakan live server
npx live-server
```

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **TTS**: Web Speech API
- **Storage**: LocalStorage untuk progress
- **AI**: Ready for integration with any LLM API

## 📁 Struktur Project

```
ai-toefl-simulator/
├── index.html          # Halaman utama
├── admin.html          # Admin panel
├── css/
│   └── style.css       # Stylesheet
├── js/
│   ├── app.js          # Logic utama aplikasi
│   ├── tts.js          # Text-to-Speech
│   ├── scoring.js      # Scoring system
│   ├── timer.js        # Timer
│   └── storage.js      # Local storage
└── data/
    ├── manifest.json   # Konfigurasi sets
    ├── listening-set-*.json
    ├── structure-set-*.json
    └── reading-set-*.json
```

## 📈 AI Integration Ready

Project ini dirancang untuk mudah diintegrasikan dengan berbagai LLM API:
- OpenAI GPT
- Anthropic Claude
- Google Gemini
- Dan lainnya

Cukup tambahkan API key dan endpoint di konfigurasi untuk mengaktifkan fitur AI.

## 🤝 Contributing

1. Fork repository
2. Create feature branch (`git checkout -b feature/xxx`)
3. Commit changes (`git commit -m 'Add xxx'`)
4. Push to branch (`git push origin feature/xxx`)
5. Open Pull Request

## 📄 License

MIT License — feel free to use and modify!

---

**Built with ❤️**
