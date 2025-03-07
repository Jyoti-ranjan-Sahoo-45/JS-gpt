# JS-gpt 🤖

A multi-platform AI assistant powered by Google's Gemini API. Chat with AI through web interface or Android app!

![Demo](https://via.placeholder.com/800x400.png?text=Web+and+Mobile+Demo) <!-- Replace with actual screenshots -->

## Features ✨
**Web Version:**
- Natural language conversations with Gemini
- File attachments (images, PDF, text, CSV)
- Light/dark theme toggle
- Response copying functionality
- Mobile-responsive design
- Real-time typing simulation
- Conversation history management

**Android App:**
- Native mobile experience
- Offline capabilities
- Push notifications
- System integration
- Optimized for mobile devices

## Technologies Used 🛠️
- **Web:** HTML5, CSS3, JavaScript, Gemini API
- **Android:** Kotlin/Java, Android SDK, Gemini API
- Material Design Icons
- Webpack (for production builds)

## Prerequisites
- Google API Key ([Get from Google AI Studio](https://makersuite.google.com/app/apikey))
- Modern web browser (for web version)
- Android 8.0+ (for mobile app)

## Installation 📦

### Web Version
1. Clone the repository:
```bash
git clone https://github.com/Jyoti-ranjan-Sahoo-45/JS-gpt.git
```
2. Add your API key in `script.js`:
```javascript
const API_KEY = 'YOUR_GOOGLE_API_KEY';
```
3. Open `index.html` in your browser

### Android App
1. Download the [app-release.apk](https://github.com/Jyoti-ranjan-Sahoo-45/JS-gpt/raw/main/app-release.apk)
2. Enable "Unknown sources" in Android settings
3. Install and launch the APK

## Usage 🚀
**Web:**
1. Type or click suggestions
2. Attach files if needed
3. Press ⬆️ to send
4. Use 🗑️ to clear history
5. Toggle theme with 🌓 button

**Android:**
1. Open the app
2. Start chatting immediately
3. Long-press messages to copy
4. Swipe to access settings

## Configuration ⚙️
Customize in `script.js`:
```javascript
// Adjust response behavior
const generationConfig = {
  temperature: 0.9,
  maxOutputTokens: 2048,
  topP: 1,
};

// Modify UI settings
const UISettings = {
  typingSpeed: 40, // ms per word
  responseDelay: 600, // ms before bot responds
};
```

## Android App Details 📱
- Minimum SDK: 26
- Target SDK: 34
- Permissions: 
  - Internet access
  - File storage (for attachments)
  - Camera (optional for future features)

## Contributing 🤝
1. Fork the repository
2. Create feature branch (`git checkout -b feature/NewFeature`)
3. Commit changes (`git commit -m 'Add NewFeature'`)
4. Push to branch (`git push origin feature/NewFeature`)
5. Open Pull Request

## License 📄
MIT License - see [LICENSE](LICENSE) for details

## Notes ⚠️
- API key required for both versions
- Mobile app may require enabling unknown sources
- Responses may vary based on Gemini's training data

## Contact 📧
**Jyoti Ranjan Sahoo**  
- GitHub: [@Jyoti-ranjan-Sahoo-45](https://github.com/Jyoti-ranjan-Sahoo-45)
- Email:Sahoojyotiranjan114@gmail.com

```

Key changes from previous version:
1. Added Android app section
2. Updated API references to Gemini
3. Added mobile-specific features
4. Included APK installation instructions
5. Added generation configuration parameters
6. Added Android permissions info
