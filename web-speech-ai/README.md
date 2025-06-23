# VoiceGPT – Voice Based AI Chatbot 🎤🤖

A simple yet powerful AI chatbot application that combines **Web Speech API** with **OpenAI GPT-3.5** to create an interactive voice-based conversation experience. Perfect for English language learning and improving communication skills.

## 🌟 Features

- **🎤 Voice Recognition** - Uses Web Speech API to convert speech to text
- **🤖 AI-Powered Responses** - Integrates with OpenAI GPT-3.5 via OpenRouter API
- **🔊 Text-to-Speech** - Bot responses are spoken back to you
- **💬 Real-Time Chat** - Instant communication using Socket.IO
- **🎯 Communication Skills Training** - Designed to help improve English speaking abilities
- **📱 Responsive Design** - Works on desktop and mobile browsers
- **⚡ Fast & Lightweight** - Simple Node.js backend with minimal dependencies

## 🚀 Live Demo

The application runs locally on `http://localhost:3000` after setup.

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js
- **Real-time Communication**: Socket.IO
- **AI Integration**: OpenRouter API (OpenAI GPT-3.5)
- **Frontend**: HTML5, CSS3, JavaScript
- **Speech Processing**: Web Speech API
- **HTTP Client**: Axios

## 📋 Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- OpenRouter API key
- Modern web browser with microphone support

## ⚙️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Abhijayshah/AI-voice-chatbot.git
   cd web-speech-ai
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory:
   ```env
   OPENAI_API_KEY=your_openrouter_api_key_here
   ```

4. **Start the application:**
   ```bash
   npm start
   ```

5. **Open your browser:**
   Navigate to `http://localhost:3000`

## 🎯 Usage

1. **Click the microphone button** to start voice input
2. **Speak your message** clearly into the microphone
3. **Wait for the AI response** - it will appear as text and be spoken aloud
4. **Continue the conversation** by clicking the microphone button again

### Example Conversation Flow:
```
👤 User: "Hello, how can you help me improve my communication skills?"

🤖 Bot: "Hello! I can help you improve your communication skills through:
- Practice conversations
- Vocabulary building
- Pronunciation feedback
- Public speaking tips
- Active listening techniques"
```

## 🎓 Perfect for English Learning

This application is specifically designed to help users:
- **Practice English conversation** in a comfortable environment
- **Improve pronunciation** through speech recognition feedback
- **Build confidence** in speaking English
- **Learn new vocabulary** through AI responses
- **Develop communication skills** with structured practice

## 📁 Project Structure

```
web-speech-ai/
├── index.js              # Main server file
├── package.json          # Dependencies and scripts
├── views/
│   └── index.html        # Frontend HTML
├── public/
│   ├── css/
│   │   └── style.css     # Styling
│   ├── js/
│   │   └── script.js     # Frontend JavaScript
│   └── images/
│       └── geometry.png  # UI assets
├── .env                  # Environment variables
└── README.md            # This file
```

## 🔧 Configuration

### Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| `OPENAI_API_KEY` | Your OpenRouter API key | Yes |
| `PORT` | Server port (default: 3000) | No |

### API Configuration

The app uses OpenRouter API with the following settings:
- **Model**: `openai/gpt-3.5-turbo`
- **System Prompt**: "You are a helpful assistant."
- **Max Tokens**: Default OpenAI limits
- **Temperature**: Default (1.0)

## 🌐 Browser Compatibility

- ✅ Chrome 25+
- ✅ Firefox 44+
- ✅ Safari 14.1+
- ✅ Edge 79+

**Note**: Web Speech API requires HTTPS in production environments.

## 🚀 Deployment

### Heroku Deployment

This app is ready for Heroku deployment:

1. **Install Heroku CLI**
2. **Login to Heroku:**
   ```bash
   heroku login
   ```
3. **Create a new app:**
   ```bash
   heroku create your-app-name
   ```
4. **Set environment variables:**
   ```bash
   heroku config:set OPENAI_API_KEY=your_api_key
   ```
5. **Deploy:**
   ```bash
   git push heroku main
   ```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## 👨‍💻 Author

**Tomomi Imura** (@girlie_mac)
- Enhanced by: **Abhijay Shah**

## 🙏 Acknowledgments

- Web Speech API for voice recognition capabilities
- OpenRouter for providing access to OpenAI models
- Socket.IO for real-time communication
- Express.js for the web framework

## 📞 Support

If you encounter issues or have questions:
1. Check the browser console for error messages
2. Ensure your microphone is properly configured
3. Verify your OpenRouter API key is valid
4. Make sure you're using a supported browser

---

**Happy chatting! 🎉** Start improving your communication skills with VoiceGPT today! 