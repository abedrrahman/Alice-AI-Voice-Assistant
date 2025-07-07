# 🤖 Alice - AI Voice Assistant App

Alice is a Flutter-based AI voice assistant powered by **ChatGPT** and **DALL·E**. With speech recognition and text-to-speech integration, Alice listens to your voice, processes your request using OpenAI APIs, and either responds with smart information or generates AI art based on your prompt.

---

## ✨ Features

- 🎙️ **Voice-Activated AI**: Tap the mic and speak your prompt — Alice listens and processes your request.  
- 💬 **ChatGPT Integration**: Get intelligent responses for questions, summaries, ideas, and more.  
- 🎨 **DALL·E Image Generation**: Ask Alice to draw or generate an image — it detects art prompts and returns AI-generated images.  
- 🔊 **Text-to-Speech**: Alice speaks the AI-generated response out loud.  
- 🎉 **Animated UI**: Smooth and fun interactions using animated widgets from `animate_do`.  

---

## 📸 Screenshots

| Home UI | AI Response | Image Generation |
|--------|--------------|------------------|
| ![Home UI](C:\Users\abdalrahman\StudioProjects\AliceAI\assets\screenshots\mainPage.png) | ![AI Response](assets/screenshots/response.png) | ![Image Generation](assets/screenshots/generatedImage.png) |

---

## 🛠️ Built With

- **Flutter** (UI)  
- **speech_to_text** (Voice recognition)  
- **flutter_tts** (Text-to-speech)  
- **http** (API requests)  
- **OpenAI GPT-3.5 + DALL·E API**  
- **animate_do** (UI animations)  

---

## 📁 Project Structure

lib/
├── main.dart # App entry point
├── mainPage.dart # Main UI with assistant logic
├── openai_service.dart # OpenAI GPT + DALL·E API handling
├── feature_box.dart # Reusable UI box for features
├── pallete.dart # App-wide color constants
└── secret.dart # Your OpenAI API key

yaml
Copy
Edit

---

## 🔐 API Key Setup

To run the app, you need an OpenAI API key.

1. Create a file: `lib/secret.dart`  
2. Add the following line:

```dart
const openAIAPIKey = 'YOUR_API_KEY_HERE';
```
🚀 Getting Started
Clone this repo

Run flutter pub get

Replace the placeholder API key in secret.dart

Run the app with flutter run

✅ To-Do
Add support for multilingual prompts

Implement error handling UI

Enable conversation history view

🙌 Author
Made with ❤️ by Abed-aLrahman ALmashrqa

Feel free to contribute, star ⭐, or fork 🍴!
