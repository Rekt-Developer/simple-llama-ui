# Simple AI 🤖

[![Vercel Deployment](https://img.shields.io/badge/Deploy-Vercel-black?logo=vercel)](https://simple-ai.vercel.app)
[![Telegram Community](https://img.shields.io/badge/Chat-Telegram-blue?logo=telegram)](https://t.me/RektDevelopers)
[![GitHub Stars](https://img.shields.io/github/stars/Rekt-Developer/simple-ai?style=social)](https://github.com/Rekt-Developer/simple-ai)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## 🌟 Project Overview

Simple AI is a comprehensive ChatGPT API-based chat application with streaming support. It provides a simple yet powerful interface for integrating AI chat functionality.

## 🚀 Live Demo

🔗 **Website:** [simple-ai.vercel.app](https://simple-ai.vercel.app)

## 💡 Features

- ChatGPT API integration
- Streaming and standard chat modes
- Multiple AI model support
- Extensible plugin architecture
- Cross-platform compatibility

## 🛠 Project Structure

### API Wrapper (`js/chat_api.js`)
```javascript
// Initialize chat context
const ctx = initChat(apiKey, options);

// Send chat message (standard mode)
async function postChatText(text, ctx, options);

// Send chat message (streaming mode)
async function streamChatText(text, ctx, chunkHandler, options);
```

## 📦 Installation

### Prerequisites
- Web server
- OpenAI API key
- Node.js
- npm or yarn

### Setup Steps
1. Copy files to web server
2. Copy `js/config.templete.js` to `js/config.js`
3. Replace `API_KEY` with your OpenAI API key
4. Customize `HEADER_ELEMENT` (optional)

### Access Methods
- Browser: `server_url/index.html` (standard/stream modes)
- Test URLs:
  - `server_url/test/test_small.html` (no communication test)
  - `server_url/test/test_large.html` (communication test)

## 🔧 Development Status

### ✅ Completed
- UI Improvements
- Streaming support
- Basic error handling
- Context management

### 🚧 Ongoing Tasks
- Message compaction algorithm
- Token count display
- Advanced error handling
- Refactoring
  - Implement JSDoc comments
  - Improve configuration flexibility
  - Enhance token management

## 💰 Support the Project

### 💸 Donation Wallet
**Ethereum Address:** `0x3A06322e9F1124F6B2de8F343D4FDce4D1009869`

### 💳 Supported Cryptocurrencies
- Ethereum (ETH)
- USDT
- USDC

## 🤝 Community

- 📢 **Telegram:** [t.me/RektDevelopers](https://t.me/RektDevelopers)
- 🌐 **Website:** [scripters.shop](https://scripters.shop)

## 🔒 License

MIT License

## 🏆 Promoted Projects

### 🌍 Scripters.shop
**Your One-Stop Shop for AI Tools & Plugins**
- 🤖 AI Models
- 🧩 Plugins
- 💻 Developer Tools

## 🤖 Contribution

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## 📞 Support

For questions, issues, or collaboration:
- Open a GitHub Issue
- Join our Telegram Community
- Email: support@scripters.shop

---

**Made with ❤️ by Rekt Developers**

[![Sponsor](https://img.shields.io/badge/Sponsor-Support_Us-blue?logo=github-sponsors)](https://github.com/sponsors/Rekt-Developer)
