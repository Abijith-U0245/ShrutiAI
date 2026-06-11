# ShrutiAI

### Offline Privacy-Preserving Hindi Voice Assistant

ShrutiAI is a fully offline Hindi voice assistant designed for edge devices such as the Raspberry Pi. It performs speech recognition, intent handling, and text-to-speech entirely on-device — with no internet connectivity and no cloud dependency, ensuring complete user privacy.

> Repository: [ShrutiAI](https://github.com/Abijith-U0245/ShrutiAI)

> Built for the **ARM Bharat AI SoC Student Challenge** — Finalist

---

## Why ShrutiAI

Most voice assistants depend on cloud APIs — sending raw audio to remote servers for processing. This raises privacy concerns and fails completely without internet access, a real constraint in large parts of rural India.

ShrutiAI flips this model: speech recognition, natural language understanding, and speech synthesis all run locally on constrained edge hardware. No data ever leaves the device.

---

## Features

- Offline Hindi speech recognition
- Privacy-first — zero cloud calls, zero data transmission
- Lightweight architecture suited for single-board computers
- Command-based intent handling for everyday queries
- Fully offline operation, start to finish

---

## Tech Stack

| Component | Technology |
|---|---|
| Language | Python |
| Speech-to-Text | Whisper / Vosk |
| Text-to-Speech | Offline TTS engine |
| Target Hardware | Raspberry Pi (ARM-based SoC) |

Languages: Python (100%)

---

## Project Structure

```
ShrutiAI/
├── project/
│   ├── hindi_chatbot.py     # Core conversational logic
│   ├── intents.py            # Intent definitions and matching
│   ├── local_data.py         # Local knowledge base / responses
│   ├── speech_input.py       # Offline speech recognition (STT)
│   ├── speech_output.py      # Offline speech synthesis (TTS)
│   └── utils.py              # Shared utilities
├── whisper_hindi_test/       # Whisper Hindi STT experiments
└── .gitignore
```

---

## Getting Started

### Prerequisites
- Python 3.9+
- Raspberry Pi (recommended) or any Linux-based edge device
- Microphone and speaker/audio output

### Installation

```bash
git clone https://github.com/Abijith-U0245/ShrutiAI.git
cd ShrutiAI/project

pip install -r requirements.txt
```

### Running

```bash
python hindi_chatbot.py
```

---

## Future Improvements

- Wake word detection
- Accent-robust Hindi recognition across dialects
- Deeper hardware integration (GPIO-based interactions)
- Optimized, lower-latency Raspberry Pi deployment

---

## Recognition

Developed for and selected as a finalist in the **ARM Bharat AI SoC Student Challenge** — recognizing on-device AI solutions built for accessibility and privacy on constrained ARM hardware.

---

## Author

**Abijith U**
- GitHub: [@Abijith-U0245](https://github.com/Abijith-U0245)
- LinkedIn: [abijithu45](https://www.linkedin.com/in/abijithu45)
- Portfolio: [abijithu.netlify.app](https://abijithu.netlify.app/)

---

## License

This project is open for educational and demonstration purposes. Feel free to fork and build upon it.
