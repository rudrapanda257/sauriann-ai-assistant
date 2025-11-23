# Sauriann - AI Meeting Assistant

Hi I am rudra narayan panda, I make it for myself, But you can use it, Make sure You follow the below steps Properly.
It's Silent, Smart, and Always On Top - Your AI-powered meeting companion.

## 🚀 Features

- **Voice Input**: Real-time speech-to-text transcription
- **Speaker Audio Capture**: Record system/speaker audio
- **Screenshot Analysis**: Capture and ask questions about screenshots
- **Text Input**: Type your questions directly
- **AI Responses**: Powered by Google Gemini AI with code formatting
- **Always-on-Top**: Stays visible over other apps
- **Collapsible Controls**: Hide controls for minimal distraction
- **Screen Sharing Mode**: Hide from screen recordings

## ⚡ Keyboard Shortcuts

| Key              | Action                     |
| ---------------- | -------------------------- |
| **Space**        | Start/Stop voice recording |
| **Alt**          | Start/Stop speaker audio   |
| **S**            | Take screenshot            |
| **R**            | Reset conversation         |
| **T**            | Focus text input           |
| **M**            | Minimize window            |
| **F**            | Toggle fullscreen          |
| **H**            | Hide/Show controls         |
| **Ctrl+Shift+A** | Show app from anywhere     |

## 📥 Installation

### Windows

1. Download `Angel AI Meeting Assistant Setup 1.0.0.exe` from [Releases](https://github.com/YOUR_USERNAME/YOUR_REPO/releases)
2. Run the installer
3. Launch the app

### macOS

1. Download `Angel AI Meeting Assistant.dmg` from [Releases](https://github.com/YOUR_USERNAME/YOUR_REPO/releases)
2. Drag to Applications
3. Launch the app

## 🔧 Setup

You need a **Google Gemini API key** (free):

1. Get it from [Google AI Studio](https://aistudio.google.com/app/apikey)
2. Add to `main.js`: `const GEMINI_API_KEY = 'your-key-here'`

You also need **Google Cloud credentials** for speech-to-text:

- Place your service account JSON file in project root
- Name it: `lazy-job-seeker-4b29b-eb0b308d0ba7.json`

## 💻 Usage

1. **Voice**: Press Space or click mic button
2. **Speaker Audio**: Press Alt or click speaker button
3. **Screenshot**: Press S or click camera button
4. **Text**: Press T or type in input box
5. **Ask AI**: Your question gets answered instantly!

## 🛠️ Development

```bash
# Install dependencies
npm install

# Run app
npm start

# Build for Windows
npm run build-win

# Build for Mac
npm run build-mac
```

## 📋 System Requirements

- **Windows**: 10 or newer (64-bit)
- **macOS**: 10.14+ (Intel & Apple Silicon)
- **RAM**: 4GB minimum
- **Internet**: Required for AI features

## 🔒 Privacy

- Audio processed in real-time (not stored)
- All data stays on your device
- API calls follow Google's privacy policies

## 📝 License

© 2025 Rudra Narayan Panda. All rights reserved.

---

Made with ❤️ by [Rudra Narayan Panda]
