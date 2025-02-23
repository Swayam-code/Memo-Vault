# Memo-Vault

A comprehensive memory preservation platform that combines a modern digital time capsule with AI-powered sentiment analysis capabilities. This repository contains two main components:

## 🌟 Components

### 1. Project-MemoVault (Digital Time Capsule)
A modern digital time capsule platform for preserving and sharing memories, built with Next.js and enhanced with AI capabilities.

#### Key Features
- **Digital Memory Preservation**
  - Create and store digital "capsules" containing text, images, and memories
  - Lock capsules until a specified future date
  - Support for personal and communal memory preservation

- **Smart Organization**
  - AI-powered sentiment analysis for emotional context
  - Automatic categorization and tagging of memories
  - Timeline view for chronological memory exploration

- **Modern UI/UX**
  - Responsive design with smooth animations
  - Intuitive navigation
  - Real-time updates
  - Frosted glass design elements

#### Tech Stack
- Next.js 13 (App Router)
- TypeScript
- Tailwind CSS
- MongoDB Atlas
- Supabase Storage
- AWS S3

### 2. ML-MemoVault (Sentiment Analysis API)
A Flask-based REST API that provides sentiment analysis capabilities for the time capsule platform.

#### Key Features
- Real-time sentiment analysis
- Cross-Origin Resource Sharing (CORS) enabled
- Easy-to-use REST API interface

#### Tech Stack
- Python
- Flask
- Transformers (Hugging Face)
- PyTorch

## 🚀 Getting Started

### Prerequisites
- Node.js 18.0 or later
- Python 3.8 or later
- MongoDB Atlas account
- Supabase account
- npm or yarn package manager
- pip (Python package manager)

### Installation

1. Clone the repository with submodules:
```bash
git clone https://github.com/Swayam-code/Memo-Vault.git
cd Memo-Vault
git submodule init
git submodule update
```

2. Set up Project-MemoVault:
```bash
cd Project-MemoVault
npm install
# Set up environment variables as specified in the Project-MemoVault README
npm run dev
```

3. Set up ML-MemoVault:
```bash
cd ../ML-MemoVault
pip install -r requirements.txt
python app.py
```

## 📡 API Endpoints

### Project-MemoVault Frontend
- `/api/capsules` - Manage time capsules
- `/api/users` - User management
- `/api/auth` - Authentication

### ML-MemoVault Sentiment Analysis
- `GET /` - Health check endpoint
- `POST /sentiment` - Sentiment analysis endpoint
  ```json
  {
    "text": "Your text for sentiment analysis"
  }
  ```

## 🔗 Repository Links
- Main Repository: [Memo-Vault](https://github.com/Swayam-code/Memo-Vault)
- Frontend & Core: [Project-MemoVault](https://github.com/Swayam-code/Project-MemoVault)
- Sentiment Analysis API: [ML-MemoVault](https://github.com/Swayam-code/ML-Memovault)

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request to either of the submodules or the main repository.

## 📄 License
This project and its submodules are licensed under the MIT License - see the respective LICENSE files for details.
