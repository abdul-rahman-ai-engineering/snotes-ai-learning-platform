# snotes-ai-learning-platform
AI-powered platform that transforms lectures into summaries, flashcards, quizzes &amp; mind maps using Whisper, GPT, and LangChain. Built with FastAPI + React.

# 🎓 Snotes - AI-Powered Learning Platform

> Transform long lecture recordings into clear, concise study materials with AI

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![FastAPI](https://img.shields.io/badge/FastAPI-0.104+-green.svg)
![React](https://img.shields.io/badge/React-18+-61dafb.svg)

## 🌟 Overview

Snotes is an AI-powered web application that automatically converts lecture recordings and presentations into comprehensive study materials including summaries, flashcards, quizzes, and mind maps. Built to help students learn more efficiently and effectively.

### ✨ Key Features

- 📤 **Multi-Format Upload** - Support for video, audio, and presentation files
- 📝 **AI Summaries** - Automatic generation of clear, concise lecture summaries
- 🎴 **Flashcards** - Create study flashcards from key concepts
- ❓ **Practice Quizzes** - Generate quizzes to test understanding
- 🧠 **Mind Maps** - Visual hierarchical concept mapping
- 📊 **Chapter Breakdowns** - Organized content sections for easy navigation

## 🚀 Demo

[Live Demo](https://your-demo-link.com) | [Video Walkthrough](https://your-video-link.com)

## 🛠️ Tech Stack

### Backend
- **FastAPI** - High-performance Python web framework
- **Whisper** - OpenAI's speech-to-text model
- **GPT** - Advanced language model for content generation
- **LangChain** - Framework for LLM application development
- **AWS S3** - Cloud storage for files and generated content

### Frontend
- **React** - Modern UI framework
- **Tailwind CSS** - Utility-first CSS framework
- **Lucide Icons** - Beautiful icon library

## 📋 Prerequisites

- Python 3.8+
- Node.js 16+
- AWS Account (for S3 storage)
- OpenAI API Key

## 🔧 Installation

### Backend Setup
```bash
# Clone the repository
git clone https://github.com/[your-username]/snotes-ai-learning-platform.git
cd snotes-ai-learning-platform

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Edit .env with your API keys and configurations
```

### Frontend Setup
```bash
# Navigate to frontend directory
cd frontend

# Install dependencies
npm install

# Start development server
npm run dev
```

## ⚙️ Configuration

Create a `.env` file in the root directory:
```env
# OpenAI Configuration
OPENAI_API_KEY=your_openai_api_key

# AWS Configuration
AWS_ACCESS_KEY_ID=your_aws_access_key
AWS_SECRET_ACCESS_KEY=your_aws_secret_key
AWS_S3_BUCKET_NAME=your_bucket_name
AWS_REGION=us-east-1

# Application Configuration
DEBUG=True
HOST=0.0.0.0
PORT=8000
```

## 🎯 Usage

1. **Start the Backend Server**
```bash
   uvicorn main:app --reload
```

2. **Start the Frontend**
```bash
   cd frontend
   npm run dev
```

3. **Access the Application**
   - Open your browser to `http://localhost:3000`
   - Upload your lecture files (video/audio/slides)
   - Wait for AI processing
   - View and download your study materials

## 📁 Project Structure
```
snotes-ai-learning-platform/
├── backend/
│   ├── main.py                 # FastAPI application entry
│   ├── routes/                 # API route handlers
│   ├── services/               # Business logic
│   │   ├── transcription.py   # Whisper integration
│   │   ├── summarization.py   # GPT summarization
│   │   ├── flashcards.py      # Flashcard generation
│   │   └── quiz.py            # Quiz generation
│   ├── utils/                  # Utility functions
│   └── requirements.txt
├── frontend/
│   ├── src/
│   │   ├── components/        # React components
│   │   ├── pages/             # Page components
│   │   └── App.jsx            # Main app component
│   └── package.json
├── .gitignore
├── README.md
└── LICENSE
```

## 👥 Team

- **Jefferson** - Backend Lead (FastAPI, LLM integration, chunking logic)
- **Abdul Rahman** - Frontend Lead (Web UI, upload interface, output display)
- **Sohib** - AI/ML Integration (Whisper setup, GPT prompts, mind map logic)
- **Merna Magdi** - DevOps & Storage (AWS S3 setup, deployment, file management)

## 📅 Development Timeline

- **Week 1-2:** Upload system + Speech-to-Text integration
- **Week 3:** Summaries + Flashcards generation
- **Week 4:** Mind Map generator + Quiz engine
- **Week 5:** Frontend UI development + Backend integration
- **Week 6:** Testing, bug fixes, and final demo preparation

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- OpenAI for Whisper and GPT models
- Anthropic for Claude assistance
- LangChain team for the amazing framework
- All contributors and testers

## 📞 Contact

Project Link: [https://github.com/[your-username]/snotes-ai-learning-platform](https://github.com/[your-username]/snotes-ai-learning-platform)

---

⭐ If you find this project helpful, please give it a star!
```

---

## 🏷️ **GitHub Topics to Add:**

After creating the repository, add these topics:
```
ai
education
machine-learning
nlp
whisper
gpt
langchain
fastapi
react
study-tools
edtech
speech-to-text
summarization
flashcards
quiz-generator
student-tools
learning-platform
