# What Did I Do Today?

AI-powered time tracking with screenshots. See exactly what you did, when you did it, and how long it took. Uses AI to automatically detect and categorize your activities. All screenshots are stored locally for your privacy.

🌐 [Try it online](https://whatdidido.web.app/)

![App Screenshot](assets/ui.png)

## Features

- 🤖 AI-powered activity detection using Google's Gemini AI
- 📸 Automatic screenshots at customizable intervals (1-10 minutes)
- 📊 Activity categorization into:
  - Work (coding, documents, professional tasks)
  - Learn (tutorials, research, educational content)
  - Social (meetings, chat, emails)
  - Entertainment (games, videos, casual browsing)
- 📈 Daily activity statistics and time tracking
- 🖼️ Screenshot history with thumbnails
- 💾 Local SQLite database storage
- 🔒 Privacy-focused: all data stays on your machine
- ⚡ System idle detection to prevent unnecessary captures
- 🎨 Modern, clean UI with dark mode support

## Installation

1. Download the latest release from the [Releases](https://github.com/aladynjr/what-did-i-do/releases) page
2. Run the installer (`What Did I Do Setup.exe`)
3. Launch the application
4. Enter your Gemini API key (see below)

## Getting Started

### API Key Setup
1. Visit [Google AI Studio](https://aistudio.google.com)
2. Sign in with your Google account
3. Click "Get API Key" in the top menu
4. Create a new API key (free)
5. Copy and paste the key into the app's settings

### Usage
1. Configure your preferred screenshot interval (1-10 minutes)
2. Click "Start Recording" to begin tracking
3. The app will automatically:
   - Take screenshots at your set interval
   - Analyze activities using AI
   - Categorize your time
   - Generate daily statistics

## Technical Details

Built with:
- Electron
- Node.js
- Google Gemini AI API
- SQLite
- HTML/CSS/JavaScript

Requirements:
- Windows x64
- Internet connection (for AI analysis)
- Google Gemini API key

## Privacy

- All screenshots and data are stored locally on your machine
- No data is sent to external servers except screenshots to Google's Gemini AI for analysis
- You can delete your data at any time by removing the app's data directory

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](LICENSE)

## Contact

Questions or feedback? Reach out on Twitter [@aladdinnjr](https://twitter.com/aladdinnjr)