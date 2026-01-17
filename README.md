# 🌐 Modern Translator Pro

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Tkinter](https://img.shields.io/badge/Tkinter-GUI%20Framework-green)
![Google Translate](https://img.shields.io/badge/Google-Translate%20API-orange)
![Text-to-Speech](https://img.shields.io/badge/TTS-Pyttsx3-purple)
![License](https://img.shields.io/badge/License-MIT-yellow)

A modern, feature-rich text translator with GUI, supporting 20+ languages, text-to-speech, history, and professional tools. Ideal for translators, students, travelers, and professionals.

## ✨ Key Features

### 🌍 Multilingual Translation
- **20+ languages**: English, French, Arabic, Spanish, German, Chinese, Japanese, etc.
- **Auto-detection**: Automatic source language recognition
- **Real-time translation**: Instant results
- **Confidence score**: Translation accuracy estimation
- **Unicode support**: Special characters & emojis

### 🔊 Audio Features
- **Text-to-speech**: Read translations aloud
- **Speech control**: Play/Stop with button
- **Natural voices**: Clear output using pyttsx3
- **Multilingual TTS**: Read in target language

### 📋 Translation Management
- **Complete history**: Save all translations
- **Undo function**: Revert to previous state
- **Favorites**: Save frequently used languages
- **Clipboard**: Quick copy of translations
- **Export**: Save to text files

### 🎨 Modern Interface
- **Customizable themes**: Light/dark mode
- **Responsive design**: Adapts to all screen sizes
- **Visual effects**: Modern animations & colors
- **Intuitive UI**: Clear, logical organization

## 🚀 Quick Installation

```bash
# Clone repository
git clone https://github.com/username/modern-translator-pro.git
cd modern-translator-pro

# Create virtual environment
python -m venv venv

# Activate (Windows)
venv\Scripts\activate
# Activate (Linux/Mac)
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

## ⚙️ Requirements

`requirements.txt`:
```txt
deep-translator>=1.11.4
pyttsx3>=2.90
langdetect>=1.0.9
pyperclip>=1.8.2
```

## 🎮 Basic Usage

1. **Launch:**
```bash
python translator.py
```

2. **Enter text** in the top area

3. **Select target language** from dropdown

4. **Click "Translate"**

5. **View results** in bottom area

## 🔧 Key Functions

- **Auto-detect**: Checkbox for automatic source language detection
- **Text-to-speech**: Click "Speak" to hear translation
- **Quick copy**: "Copy" to clipboard
- **History**: "History" to view previous translations
- **Favorites**: Add frequent languages to favorites
- **Theme toggle**: "Dark Mode"/"Light Mode" button
- **Export**: Save translations as .txt files

## 📊 Supported Languages

| Language | Code | TTS |
|----------|------|-----|
| 🇬🇧 English | `en` | ✓ |
| 🇫🇷 French | `fr` | ✓ |
| 🇪🇸 Spanish | `es` | ✓ |
| 🇩🇪 German | `de` | ✓ |
| 🇦🇪 Arabic | `ar` | ✓ |
| 🇮🇹 Italian | `it` | ✓ |
| 🇯🇵 Japanese | `ja` | ✓ |
| 🇨🇳 Chinese | `zh-cn` | ✓ |
| 🇷🇺 Russian | `ru` | ✓ |
| 🇵🇹 Portuguese | `pt` | ✓ |
| 15+ additional languages | | |

## 🛡️ Privacy & Security

- **No data storage**: Translations not saved externally
- **Local history**: History stays on your machine
- **No tracking**: No personal data collection
- **HTTPS encryption**: Secure Google Translate API calls

## 📁 Project Structure
```
modern-translator-pro/
├── translator.py          # Main application
├── requirements.txt      # Dependencies
├── README.md            # Documentation
└── LICENSE              # MIT License
```

## 🔧 Troubleshooting

### Common Issues:
- **Connection errors**: Check internet/firewall settings
- **TTS not working**: Install system dependencies (espeak on Linux/Mac)
- **Characters not displaying**: Ensure UTF-8 encoding
- **Slow performance**: Reduce text length, close other apps

## 📄 License

MIT License - see [LICENSE](LICENSE) for details.

**Note**: Uses unofficial Google Translate API. For commercial use, consider official Google Cloud Translation API.

## 👤 Author

**omar badrani**  
- GitHub: https://github.com/omarbadrani  
- Email: omarbadrani770@gmail.com

---

⭐ **If this tool is helpful, please star the repository!** ⭐

---

**Version**: 1.0.0  
**Python**: 3.8+  
**OS**: Windows, Linux, macOS

*Modern Translator Pro - Breaking language barriers with style & efficiency* 🌐✨
