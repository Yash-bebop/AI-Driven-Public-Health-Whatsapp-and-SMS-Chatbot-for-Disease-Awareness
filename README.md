# 🏥 Medicos AI Health Assistant
## AI-Driven Public Health Chatbot for Disease Awareness

<div align="center">

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Flask](https://img.shields.io/badge/Flask-3.0.0-green.svg)
![Google AI Studio](https://img.shields.io/badge/Google%20AI-Studio-orange.svg)
![React](https://img.shields.io/badge/React-19.0+-61DAFB.svg)
![MIT License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

**🚀 Access Now**: [Visit Medicos AI Health Assistant](https://aistudio.google.com/apps/drive/1So0n4GwIg7dD3ph5PGaOAYQxBqkhVfW4?showPreview=true)

An intelligent, multilingual healthcare chatbot accessible via **Web Interface** | **WhatsApp** | **SMS**

**🏆 Developed by Team Matrix Mavericks**  
*Parth Ajmera • Yashvardhan Dobhal • Aashu Joshi • Anshika Bijalwan*  
*B.Tech Computer Science, Doon University, Dehradun*

---

[🌐 Live Website](#-quick-start) • [📱 Features](#-core-features) • [🔧 Tech Stack](#-tech-stack) • [💾 Repository Files](#-repository-contents) • [📖 Documentation](#-documentation)

</div>

---

## 🎯 Quick Start

### Option 1: Use Live Web App (Recommended - No Setup Required!)
👉 **[Open Medicos AI Health Assistant](https://aistudio.google.com/apps/drive/1So0n4GwIg7dD3ph5PGaOAYQxBqkhVfW4?showPreview=true)**

1. Visit the link above
2. Select your language
3. Start asking health questions
4. Access WhatsApp & SMS bots through the web interface

**✨ Works on Desktop, Tablet, and Mobile**

### Option 2: Run Locally (For Developers)

```bash
# Clone repository
git clone https://github.com/ajmeraparthofficial-star/AI-Driven-Public-Health-Whatsapp-and-SMS-Chatbot-for-Disease-Awareness.git
cd AI-Driven-Public-Health-Whatsapp-and-SMS-Chatbot-for-Disease-Awareness

# Backend setup
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py

# In another terminal - Start Ngrok tunnel
ngrok http 5000 --domain=sheiklike-magnus-cheliferous.ngrok-free.dev

# Access locally at http://localhost:5000
```

### Option 3: Contact Bot Directly

- **WhatsApp**: Send message to +91 XXXXXXXXXX
- **SMS**: Text +91 XXXXXXXXXX
- **Web**: [Medicos AI Health Assistant](https://aistudio.google.com/apps/drive/1So0n4GwIg7dD3ph5PGaOAYQxBqkhVfW4?showPreview=true)

---

## 📱 Core Features

### 🤖 AI-Powered Health Assistant
- **Symptom Analysis**: Describe symptoms, get AI-powered health insights
- **Disease Information**: Learn about diseases, causes, prevention, and treatment
- **Emergency Detection**: Bot identifies urgent situations and recommends immediate medical help
- **Preventive Care**: General wellness advice and health tips
- **Context-Aware**: Maintains conversation history for better understanding

### 🌍 Multilingual Support (13+ Indian Languages)
English • Hindi (हिंदी) • Marathi (मराठी) • Bengali (বাংলা) • Gujarati (ગુજરાતી) • Telugu (తెలుగు) • Tamil (தமிழ்) • Kannada (ಕನ್ನಡ) • Malayalam (മലയാളം) • Odia (ଓଡ଼ିଆ) • Punjabi (ਪੰਜਾਬੀ) • Urdu (اردو) • Hinglish

### 📲 Multi-Channel Access

| Channel | Access | Features |
|---------|--------|----------|
| **🌐 Web App** | [Click Here](https://aistudio.google.com/apps/drive/1So0n4GwIg7dD3ph5PGaOAYQxBqkhVfW4?showPreview=true) | Chat, image upload, voice input, dark mode, history, export |
| **💬 WhatsApp** | +91 XXXXXXXXXX | Text, images, group chats, instant responses |
| **📱 SMS** | +91 XXXXXXXXXX | Works without internet, 160 chars limit, universal |

### 🎨 Web Interface Features
- ✅ Modern, responsive design (desktop, tablet, mobile)
- ✅ Real-time chat with message history
- ✅ Language auto-detection and manual selection
- ✅ Image upload for symptom analysis
- ✅ Voice input/output support
- ✅ Dark mode & accessibility options
- ✅ Share health information securely
- ✅ FAQ section and emergency resources
- ✅ One-click WhatsApp/SMS integration

### 🛡️ Privacy & Security
- HTTPS encrypted communication
- No personal health data stored permanently
- Session-based data management
- Medical disclaimer on every interaction

---

## 🛠 Tech Stack

| Component | Technology |
|-----------|------------|
| **Frontend** | Google AI Studio for rapid prototyping, React 19+, TypeScript, Tailwind CSS |
| **Backend** | Flask 3.0.0, Python 3.9+, Ngrok (tunneling) |
| **AI Model** | Google Gemini 2.0 Flash |
| **APIs** | WaSender (WhatsApp), Fast2SMS (SMS) |
| **Deployment** | Railway / Render / AWS / Google Cloud |
| **Code Repository** | GitHub |

---

## 📂 Repository Contents

### 🌐 Web App Files
- **File Name**: `medicos-ai-health-assistant_web-app`
- **Location**: GitHub repository
- **Framework**: Google AI Studio
- **Features**: All web interface functionality, WhatsApp/SMS integration

### 🤖 Backend & APIs
- **Backend**: `backend/app.py` - Main Flask application
- **Chat API**: `/api/chat` - Web chat endpoint
- **Health Check**: `/api/health` - System status
- **Webhooks**: WhatsApp & SMS incoming message handlers

### 💬 SMS & WhatsApp Chatbot Module
- **Location**: `healthcare_chatbot/` folder
- **Contents**:
  - `whatsapp_chatbot.py` - WhatsApp bot logic
  - `sms_chatbot.py` - SMS bot logic
  - `gemini_integration.py` - Google Gemini API wrapper
  - `config.py` - API configurations
  - `utils.py` - Helper functions

### 📊 Project Documentation
- **Full PPT**: Complete PowerPoint presentation with design, workflow, and architecture
- **API Documentation**: `docs/API_DOCUMENTATION.md`
- **Test Files**: `backend/test_api.py`, `backend/test_sms_only.py`

### 📁 Directory Structure
```
AI-Driven-Public-Health-Whatsapp-and-SMS-Chatbot-for-Disease-Awareness/
├── 📄 README.md                              # Project documentation
├── 📊 Project_Presentation.pptx              # Full project PPT
├── 📜 LICENSE                                # MIT License
│
├── 📁 backend/
│   ├── app.py                               # Flask main app
│   ├── requirements.txt                     # Dependencies
│   ├── test_api.py                          # API tests
│   ├── test_sms_only.py                     # SMS tests
│   └── .env                                 # Config (create this)
│
├── 📁 healthcare_chatbot/                   # SMS & WhatsApp Module
│   ├── whatsapp_chatbot.py                  # WhatsApp handler
│   ├── sms_chatbot.py                       # SMS handler
│   ├── gemini_integration.py                # AI wrapper
│   ├── config.py                            # Configuration
│   └── utils.py                             # Utilities
│
├── 📁 medicos-ai-health-assistant_web-app/  # Web App (AI Studio)
│   ├── src/                                 # React components
│   ├── public/                              # Static files
│   ├── package.json                         # Dependencies
│   └── README.md                            # Deployment notes
│
└── 📁 docs/
    └── API_DOCUMENTATION.md                 # Full API docs
```

---

## 📖 API Reference

### Web Chat
```http
POST /api/chat
Content-Type: application/json

{
  "userId": "user-123",
  "message": "I have fever and headache",
  "language": "en"
}
```

### WhatsApp Webhook
```http
POST /webhook/whatsapp
```
Triggered automatically when messages received via WaSender

### SMS Webhook
```http
POST /webhook/sms
```
Triggered automatically when SMS received via Fast2SMS

### System Health Check
```http
GET /api/health
```

**Response**: Service status and active connections

### Full API Documentation
See `docs/API_DOCUMENTATION.md` in repository for complete endpoint details

---

## 🔧 Setup & Configuration

### Environment Variables (`.env` file)
```env
# Google Gemini AI
GEMINI_API_KEY=your_gemini_api_key

# WhatsApp (WaSender)
WASENDER_API_KEY=your_wasender_key
WHATSAPP_NUMBER=+91XXXXXXXXXX

# SMS (Fast2SMS)
SMS_API_KEY=your_fast2sms_key
SMS_NUMBER=+91XXXXXXXXXX

# Ngrok Tunnel
NGROK_DOMAIN=sheiklike-magnus-cheliferous.ngrok-free.dev
NGROK_AUTHTOKEN=your_ngrok_token
```

### Getting API Keys

| API | Steps |
|-----|-------|
| **Google Gemini** | Visit https://makersuite.google.com/app/apikey → Create new key |
| **WaSender** | Visit https://www.wasenderapi.com → Sign up → Get API key |
| **Fast2SMS** | Visit https://www.fast2sms.com → Sign up → Add ₹100 credit → Get key |
| **Ngrok** | Visit https://dashboard.ngrok.com → Sign up → Get authtoken |

### Webhook Configuration

**WaSender Dashboard**:
1. Settings → Webhooks
2. Add URL: `https://your-ngrok-domain/webhook/whatsapp`
3. Select "Message Received" event
4. Save

**Fast2SMS Dashboard**:
1. API Settings
2. Add URL: `https://your-ngrok-domain/webhook/sms`
3. Save

---

## 🧪 Testing

### Web Interface Testing
1. Open: https://aistudio.google.com/apps/drive/1So0n4GwIg7dD3ph5PGaOAYQxBqkhVfW4?showPreview=true
2. Type test query in English/Hindi OR IN ANY OTHER LISTED LANGUAGE
3. Verify response

### WhatsApp Testing
```bash
# In backend directory
curl -X POST http://localhost:5000/test/whatsapp \
  -H "Content-Type: application/json" \
  -d '{"phone": "917017067297", "message": "Hello test"}'
```

### SMS Testing
```bash
curl -X POST http://localhost:5000/test/sms \
  -H "Content-Type: application/json" \
  -d '{"phone": "917895032847", "message": "Hello test"}'
```

### Automated Tests
```bash
cd backend
python test_api.py
```

---

## 🚀 Deployment Options

### 1️⃣ Railway.app (Easiest)
```bash
git push origin main
# Login to railway.app
# Connect GitHub repo
# Add environment variables
# Deploy!
```

### 2️⃣ Render.com
1. Visit render.com
2. Create Web Service from GitHub
3. Set build command: `pip install -r requirements.txt`
4. Set start command: `python backend/app.py`
5. Add environment variables
6. Deploy

### 3️⃣ AWS EC2
```bash
ssh -i key.pem ubuntu@your-ip
sudo apt update && sudo apt install python3-pip
git clone <repo-url>
cd backend
pip3 install -r requirements.txt
gunicorn -w 4 -b 0.0.0.0:5000 app:app
```

### 4️⃣ Google Cloud / Azure
Follow cloud provider's containerization guides for Flask apps

---

## 🐛 Troubleshooting

| Issue | Solution |
|-------|----------|
| **Port 5000 in use** | `lsof -ti:5000 \| xargs kill -9` (Mac/Linux) or find process in Task Manager (Windows) |
| **Module not found** | `pip install -r requirements.txt` and check virtual environment activation |
| **WhatsApp not sending** | Verify API key, check rate limits (1 msg/min free), ensure webhook URL is correct |
| **SMS not sending** | Add ₹100 credit to Fast2SMS account and wait 5-10 mins for activation |
| **Ngrok domain issue** | Re-authenticate: `ngrok config add-authtoken YOUR_TOKEN` |
| **CORS errors** | Backend already has CORS enabled; check frontend URL in backend config |
| **healthcare_chatbot module not found** | Ensure you're in correct directory; check `__init__.py` exists in healthcare_chatbot folder |

---

## 📝 Important Files to Know

| File | Purpose |
|------|---------|
| `README.md` | Main project documentation |
| `Project_Presentation.pptx` | Complete visual overview of the project |
| `medicos-ai-health-assistant_web-app/` | AI Studio web application source code |
| `healthcare_chatbot/` | SMS & WhatsApp bot implementation |
| `backend/app.py` | Flask backend server |
| `backend/requirements.txt` | Python dependencies |
| `.env` | Configuration (you must create this) |

---

## 👥 Team & Credits

### 🏆 Matrix Mavericks

| Name | LinkedIn | Email |
|------|----------|-------|
| **Parth Ajmera** | [Profile](#) | ajmeraparth.official@gmail.com |
| **Yashvardhan Dobhal** |  [Profile](#) | dobhalyashvardhan06@gmail.com |
| **Aashu Joshi** |  [Profile](#) | aashujoshisbps@gmail.com |
| **Anshika Bijalwan** |  [Profile](#) | anshika.bij12@gmail.com |

**Institution**: B.Tech Computer Science, Doon University, Dehradun  
**Project Duration**: October 2024 - Present  
**Project Type**: Academic Research & Development

---

## 📞 Contact & Support

- **GitHub**: [Matrix Mavericks Repository](https://github.com/ajmeraparthofficial-star/AI-Driven-Public-Health-Whatsapp-and-SMS-Chatbot-for-Disease-Awareness)
- **Website**: [Medicos AI Health Assistant](https://aistudio.google.com/apps/drive/1So0n4GwIg7dD3ph5PGaOAYQxBqkhVfW4?showPreview=true)
- **Email**: matrixmavericks@doonuniversity.ac.in
- **Institution**: Doon University, Dehradun, Uttarakhand, India

**WhatsApp Bot**: +91 XXXXXXXXXX  
**SMS Bot**: +91 XXXXXXXXXX

---

## 📋 Features Comparison

| Feature | Web App | WhatsApp | SMS |
|---------|---------|----------|-----|
| Chat Interface | ✅ Modern UI | ✅ Native | ✅ Text-based |
| Image Upload | ✅ Yes | ✅ Yes | ❌ No |
| Voice Support | ✅ Voice input/output | ✅ Voice messages | ❌ No |
| Language Support | ✅ All 13+ | ✅ Auto-detect | ✅ All 13+ |
| History | ✅ Persistent | ✅ Per session | ❌ Per SMS |
| Response Speed | ⚡ Real-time | ⚡ Near real-time | ⚡ 2-5 seconds |
| No Internet | ❌ No | ❌ No | ✅ Works offline |
| Group Chat | ❌ No | ✅ Yes | ❌ No |
| Installation | ❌ None | ✅ Just text | ✅ Just text |

---

## 🎓 Learning Resources

- **Google Gemini API Docs**: https://ai.google.dev
- **Flask Documentation**: https://flask.palletsprojects.com
- **WaSender API Guide**: https://www.wasenderapi.com/docs
- **Fast2SMS Documentation**: https://www.fast2sms.com/dev/docs
- **React & TypeScript**: https://react.dev

---

## 📜 License

This project is licensed under the **MIT License** - see the LICENSE file for details.

You are free to use, modify, and distribute this project for educational and commercial purposes.

---

## ⚠️ Important Disclaimer

**DISCLAIMER**: This chatbot is an **educational project** and provides **general health information only**. It is **NOT a substitute for professional medical advice**.

**Always seek professional medical advice** from a qualified healthcare provider for any medical concerns.

**In emergencies**, call emergency services immediately.

---

## 🌟 Star & Fork

If you find this project helpful, please:
- ⭐ **Star** this repository on GitHub
- 🍴 **Fork** to contribute
- 🔔 **Watch** for updates

---

## 🚀 Future Roadmap

- [ ] Advanced symptom analysis with ML
- [ ] Integration with hospital appointment systems
- [ ] Medicine reminder & dosage tracking
- [ ] Health records management
- [ ] Telemedicine video consultation
- [ ] Offline mode for SMS
- [ ] Push notifications
- [ ] Multi-language voice support
- [ ] Wearable device integration

---

<div align="center">

### Made with ❤️ by Team Matrix Mavericks

**Parth Ajmera • Yashvardhan Dobhal • Aashu Joshi • Anshika Bijalwan**

B.Tech Computer Science, Doon University, Dehradun

---

**[👉 Try Now: Medicos AI Health Assistant](https://aistudio.google.com/apps/drive/1So0n4GwIg7dD3ph5PGaOAYQxBqkhVfW4?showPreview=true)**

© 2024 Matrix Mavericks. All Rights Reserved.

</div>
