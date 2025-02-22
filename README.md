# Video-Translator

## 🎯 Overview
**Video-Translator** is a Python-based tool that automatically translates videos into multiple languages using AI. It extracts speech, translates it, and overlays the translated audio onto the original video.

## ✨ Features
- 🎤 **Automatic Speech Recognition (ASR)**: Converts speech from video to text.
- 🌍 **Multilingual Translation**: Translates extracted text into multiple languages.
- 🔊 **Text-to-Speech (TTS)**: Generates translated voice-over audio.
- 🎥 **Seamless Video Processing**: Replaces original audio with translated speech.

## 📂 File Structure
```
Video-Translator/
│── app.py                   # Main application script
│── requirements.txt         # Dependencies
│── obama.mp4                # Sample video
│── video_translated_de.mp4  # Translated video (German)
│── video_translated_es.mp4  # Translated video (Spanish)
│── video_translated_it.mp4  # Translated video (Italian)
│── video_translated_ja.mp4  # Translated video (Japanese)
│── videos/                  # Directory for processing videos
```

## 🚀 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ShantanuisCoding/Video-Translator.git
   cd Video-Translator
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 🎬 Usage
Run the script with:
```bash
python app.py
```
Upload a video file, select the target language, and the script will generate a translated version of the video.

## 📜 License
This project is licensed under the MIT License.

## 🤝 Contributing
Pull requests are welcome! Feel free to open issues for improvements and feature requests.

---
Made with ❤️ by [ShantanuisCoding](https://github.com/ShantanuisCoding)
