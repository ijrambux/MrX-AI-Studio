# 🎙️ Mr. X - AI Studio

> **Open-source local AI assistant** — chat, image analysis, voice, and coding help.
> Runs **entirely on your machine** — your data never leaves your device.

![Mr. X](assets/mr_x_welcome.png)

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 💬 **Smart Chat** | Natural conversation with multiple LLMs |
| 🖼️ **Image Analysis** | Understand and describe images (LLaVA) |
| 🎙️ **Instant Voice** | Text-to-speech with Algerian Arabic accent (Edge TTS) |
| 🎤 **Voice Mode** | Talk directly to Mr. X (Web Speech API) |
| 🔍 **Fact Checking** | Hallucination detection (groundrails) |
| 🧠 **Auto-Router** | Automatically picks the best model for each task |
| 🎨 **8 Color Themes** | Full UI customization |
| 🌐 **3 Languages** | Arabic, English, French |
| 📁 **Chat History** | Local SQLite storage |
| 🔒 **Full Privacy** | Everything runs locally |

---

## 🚀 Quick Start

### Requirements

- **Python 3.12+**
- **Ollama** ([download](https://ollama.com/download))

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/ijrambux/MrX-AI-Studio.git
cd MrX-AI-Studio

# 2. Create a virtual environment
py -3.12 -m venv .venv
.\.venv\Scripts\Activate.ps1

# 3. Install dependencies
pip install -r requirements.txt

# 4. Download a model
ollama pull qwen2.5:1.5b

# 5. Run the app
python ui\web_app.py
