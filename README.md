# 🤖 AI Resume Analyzer

> **Resumind** - Smart feedback for your dream job

An intelligent resume analysis platform that provides ATS (Applicant Tracking System) scoring and detailed feedback to help you optimize your resume for job applications.

![AI Resume Analyzer](https://img.shields.io/badge/React-19.1.0-blue?style=flat-square&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.8.3-blue?style=flat-square&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.1.4-38B2AC?style=flat-square&logo=tailwind-css)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

## ✨ Features

- **🎯 ATS Optimization**: Get detailed ATS compatibility scores and recommendations
- **📊 Comprehensive Analysis**: Receive feedback on content, structure, tone, and skills
- **📱 Modern UI**: Beautiful, responsive interface built with React and Tailwind CSS
- **🔒 Secure Authentication**: Built-in authentication system for user privacy
- **📈 Progress Tracking**: Track your resume submissions and improvement over time
- **🤖 AI-Powered Insights**: Advanced AI analysis using Claude 4 for accurate feedback
- **📄 Multi-Format Support**: Upload PDF resumes with automatic conversion
- **💾 Persistent Storage**: Save and manage your resume analyses securely

## 🚀 Quick Start

### Prerequisites

- Node.js 20+ 
- npm or yarn
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/darvinpatel/ai-resume-analyzer.git
   cd resume-analyzer
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   # Edit .env with your configuration
   ```

4. **Start development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:3000`

## 🛠️ Tech Stack

### Frontend
- **React 19** - Modern React with latest features
- **TypeScript** - Type-safe development
- **React Router** - Client-side routing
- **Tailwind CSS** - Utility-first CSS framework
- **Zustand** - Lightweight state management
- **React Dropzone** - File upload handling

### Backend & Services
- **Puter Cloud** - File storage and AI services
- **Claude 4 AI** - Advanced resume analysis
- **PDF.js** - PDF processing and conversion

### Development Tools
- **Vite** - Fast build tool and dev server
- **Docker** - Containerization support
- **ESLint & Prettier** - Code quality and formatting

## 📖 Usage

### 1. Authentication
- Sign up or log in to access the platform
- Your data is securely stored and private

### 2. Upload Resume
- Navigate to the upload page
- Enter company name, job title, and job description
- Upload your PDF resume
- Click "Save & Analyze Resume"

### 3. Review Analysis
- View comprehensive feedback including:
  - Overall ATS score
  - Content quality assessment
  - Structure and formatting tips
  - Skills alignment analysis
  - Tone and style recommendations

### 4. Track Progress
- Monitor your resume submissions
- Compare different versions
- Track improvement over time

## 🏗️ Project Structure

```
ai-resume-analyzer/
├── app/
│   ├── components/          # Reusable UI components
│   ├── routes/             # Page components and routing
│   ├── lib/                # Utility functions and services
│   ├── constants/          # Application constants
│   └── types/              # TypeScript type definitions
├── public/                 # Static assets
├── Dockerfile              # Docker configuration
├── package.json            # Dependencies and scripts
└── README.md              # Project documentation
```

## 🐳 Docker Deployment

### Build and Run with Docker

```bash
# Build the Docker image
docker build -t ai-resume-analyzer .

# Run the container
docker run -p 3000:3000 ai-resume-analyzer
```

### Docker Compose (Optional)

```yaml
version: '3.8'
services:
  ai-resume-analyzer:
    build: .
    ports:
      - "3000:3000"
    environment:
      - NODE_ENV=production
```

## 🔧 Configuration

### Environment Variables

Create a `.env` file in the root directory:

```env
# Puter Cloud Configuration
PUTER_APP_ID=your_puter_app_id
PUTER_APP_SECRET=your_puter_app_secret

# Application Settings
NODE_ENV=development
PORT=3000
```

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Development Guidelines

- Follow TypeScript best practices
- Use meaningful commit messages
- Add tests for new features
- Update documentation as needed
- Follow the existing code style

## 🐛 Troubleshooting

### Common Issues

**Build Errors**
```bash
# Clear node_modules and reinstall
rm -rf node_modules package-lock.json
npm install
```

**Port Already in Use**
```bash
# Kill process on port 3000
lsof -ti:3000 | xargs kill -9
```

**Docker Issues**
```bash
# Rebuild without cache
docker build --no-cache -t ai-resume-analyzer .
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Puter Cloud** for providing file storage and AI services
- **Claude 4** for advanced AI analysis capabilities
- **React Router** team for the excellent routing solution
- **Tailwind CSS** for the beautiful utility-first CSS framework

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/darvinpatel/resume-analyzer/issues)
- **Email**: contact@darvinpatel.com

## 🔗 Links

- **Live Demo**: [https://resume-analyzer.darvinpatel.com/](https://resume-analyzer.darvinpatel.com/)

---

<div align="center">
  <p>Made with ❤️ by <a href="https://github.com/darvinpatel">Darvin Patel</a></p>
  <p>If this project helps you, please give it a ⭐️</p>
</div>
