# ChatAI - Multi-Model AI Chat App

Ứng dụng chat AI hỗ trợ nhiều model và đa ngôn ngữ, được xây dựng bằng React + Capacitor.

## ✨ Tính năng

- 🤖 Hỗ trợ 4 AI models: Groq, Cohere, Gemini Flash, Gemini Pro
- 🌍 Đa ngôn ngữ: Tiếng Việt, English, 日本語, 中文
- 📸 Upload và gửi ảnh
- 📄 Upload file (PDF, DOC, DOCX, XLS, XLSX)
- 🎤 Voice input với Speech Recognition
- 💬 Quản lý nhiều cuộc hội thoại
- 💾 Lưu trữ lịch sử chat

## 🚀 Cài đặt

```bash
# Clone repository
git clone https://github.com/yourusername/chatai-capacitor.git
cd chatai-capacitor

# Cài dependencies
npm install

# Build React app
npm run build

# Sync với iOS
npx cap sync ios

# Mở Xcode
npx cap open ios
```

## 🛠️ Development

```bash
# Start dev server
npm start

# Build production
npm run build

# Sync changes to iOS
npx cap sync ios
```

## 📱 Build iOS

1. Mở project trong Xcode: `npx cap open ios`
2. Chọn team để sign app
3. Chọn device/simulator
4. Run (⌘R)

## 🔧 Cấu hình

API endpoint được cấu hình trong `src/App.js`:
```javascript
const API_URL = 'http://www.smilebody.sakura.ne.jp/app/chat/api.php';
```

## 📄 License

MIT
