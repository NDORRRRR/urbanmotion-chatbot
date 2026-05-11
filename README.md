# UrbanMotion AI

Multi-model AI chatbot dengan support dokumen, GitHub repo analysis, dan OAuth login.

## ✨ Fitur

- 🤖 **4 AI Models**: Fast (Claude Haiku), Balanced (DeepSeek), Smart (Claude Sonnet), Coding (Qwen Coder)
- 📄 **Document Upload**: PDF, DOCX, TXT, Markdown, code files
- 🔍 **GitHub Repo Analysis**: Analisis struktur & code dari GitHub repo
- 🔐 **OAuth Login**: Google & GitHub
- 📧 **Email Verification**: SMTP-based verification
- 👤 **User Management**: Profile, avatar upload, password change
- 🛡️ **Admin Dashboard**: User management, usage stats
- 💬 **Chat History**: Persistent conversations dengan search

## 🛠️ Tech Stack

**Frontend:**
- React 18 + Vite
- Lucide React (icons)
- React Markdown + Syntax Highlighting
- CSS custom properties

**Backend:**
- Node.js + Express
- Prisma ORM (PostgreSQL)
- JWT authentication
- Multer (file upload)
- Tesseract.js (OCR)
- Mammoth (DOCX parser)
- pdf-parse

## 🚀 Setup

### Prerequisites

- Node.js 18+
- PostgreSQL 16
- X5Lab API key (https://x5lab.ai)

### 1. Clone repo

```bash
git clone https://github.com/NDORRRRR/urbanmotion-chatbot.git
cd urbanmotion-chatbot
