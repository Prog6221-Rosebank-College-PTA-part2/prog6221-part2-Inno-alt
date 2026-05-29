# CyberGuard - Cybersecurity Awareness Chatbot

A WPF desktop application that educates users about cybersecurity best practices through an interactive chatbot with voice output, memory, and sentiment detection.

## Features

- **GUI Interface** - Modern dark-themed WPF interface with message bubbles
- **Voice Output** - Text-to-speech responses with toggle button
- **Keyword Recognition** - Detects 6 cybersecurity topics (passwords, phishing, safe browsing, 2FA, malware, privacy)
- **Random Responses** - Multiple response variations for engaging conversations
- **Conversation Flow** - Handles follow-up commands like "tell me more" and "another tip"
- **Memory** - Remembers user name and interests throughout the session
- **Sentiment Detection** - Detects worried, frustrated, curious, and positive sentiments with empathy responses
- **ASCII Art** - Console-style logo translated to GUI header

## Requirements

- .NET 6.0 or higher
- Windows OS (for WPF and Speech support)

## Installation
CybersecurityChatbotWPF/
├── MainWindow.xaml          # GUI layout
├── MainWindow.xaml.cs       # UI event handling
├── Chatbot.cs               # Core bot logic
└── CybersecurityChatbotWPF.csproj

1. Clone the repository
```bash
git clone https://github.com/yourusername/cyberguard-chatbot.git
