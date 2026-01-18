![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Chrome](https://img.shields.io/badge/chrome-extension-green)
![Backend](https://img.shields.io/badge/backend-FastAPI-blue)

# Thread AI — Smart Email Reply Assistant (Gemini Powered)
**Thread AI** is a smart, Chrome-based email reply generator that crafts intelligent, context-aware responses using the Gemini AI API. Paste your email thread, choose your tone and role, and let AI generate thoughtful replies tailored to your style — no login or signup required.

## Features

- **Auto-generates multiple reply suggestions**
- Supports 3 modes:
  - `generate`: generate replies only
  - `analyze`: analyze new message only
  - `both`: combine context + new message
- Tone selector: friendly, formal, witty, etc.
- Role selector: recruiter, team lead, developer, etc.
- Local API key storage (secure, browser-only)
- One-click copy to clipboard
- Instant results with Gemini Pro LLM
- Minimal & modern UI with intuitive UX

## Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/ashankgupta/threadwise-ai
cd threadwise-ai
```

### 2. Load the Extension in Chrome

- Open chrome://extensions/
    
- Enable Developer mode

- Click Load unpacked

- Select the extension/ folder inside this repo

### 3. Set Up Gemini API Key

Get your key from [Here](https://aistudio.google.com/apikey)

- Open the extension popup

- Go to the Settings tab

- Paste your key and click Save

Your key is stored securely using chrome.storage.local and is never shared with any server.

## Folder Structure
```
threadwise-ai/
├── popup.html        # Main UI
├── popup.js          # Core logic and fetch call
├── styles.css        # Tailwind styling
└── manifest.json     # Chrome extension manifest
```
## Tech Stack

- Chrome Extension (Manifest V3)

- TailwindCSS

- Gemini Pro (via FastAPI backend)

- Vanilla JS

## Related Repos

- [Backend](https://github.com/ashankgupta/threadwise-ai-backend)


## Demo
[![Watch the demo](https://img.youtube.com/vi/HCNJ8we0uG0/maxresdefault.jpg)](https://youtu.be/HCNJ8we0uG0)


## License

- This project is licensed under the MIT License.
