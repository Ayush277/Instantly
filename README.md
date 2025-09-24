# Instantly - AI Content Creation Platform

Transform your content creation instantly with our suite of premium AI tools. Write articles, generate images, and enhance your workflow with the power of artificial intelligence.

## 🚀 Features

- **AI Article Writer** - Generate high-quality, engaging articles on any topic
- **AI Image Generator** - Create stunning images from text descriptions
- **Background Remover** - Remove backgrounds from images instantly
- **Object Remover** - Remove unwanted objects from images
- **Blog Title Generator** - Create compelling blog titles
- **Resume Reviewer** - AI-powered resume analysis and feedback

## 🛠️ Tech Stack

**Frontend (Client)**
- React 19 + Vite
- Tailwind CSS
- Clerk Authentication
- Lucide React Icons
- React Router DOM

**Backend (Server)**
- Node.js + Express
- Clerk Authentication
- Cloudinary (Image Storage)
- Neon Database
- OpenAI/Gemini API Integration

## 📁 Project Structure

```
instantly/
├── client/          # React frontend application
├── server/          # Express.js backend API
├── package.json     # Root package configuration
└── README.md        # This file
```

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- pnpm (recommended) or npm

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/instantly.git
   cd instantly
   ```

2. **Install dependencies for both client and server**
   ```bash
   # Install server dependencies
   cd server && pnpm install
   
   # Install client dependencies
   cd ../client && pnpm install
   ```

3. **Set up environment variables**
   ```bash
   # Copy and configure server environment variables
   cd ../server
   cp .env.example .env
   # Edit .env with your actual API keys and database URL
   ```

4. **Start the development servers**
   
   **Terminal 1 - Start the backend server:**
   ```bash
   cd server
   pnpm run server
   ```
   
   **Terminal 2 - Start the frontend client:**
   ```bash
   cd client  
   pnpm dev
   ```

5. **Open your browser**
   - Frontend: [http://localhost:5173](http://localhost:5173)
   - Backend API: [http://localhost:3000](http://localhost:3000)

## 🔧 Environment Variables

You'll need to set up the following environment variables in `server/.env`:

```env
# Database
DATABASE_URL=your_neon_database_url

# Authentication  
CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

# AI Services
GEMINI_API_KEY=your_gemini_api_key
OPENAI_API_KEY=your_openai_api_key

# Image Processing
CLIPDROP_API_KEY=your_clipdrop_api_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

# Server Configuration
PORT=3000
```

## 📚 API Documentation

The backend provides RESTful API endpoints for:
- `/api/ai/*` - AI content generation endpoints
- `/api/user/*` - User management endpoints

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the ISC License.

## 🆘 Support

If you encounter any issues or have questions, please [open an issue](https://github.com/Ayush277/Instantly/issues) on GitHub.

---

**Instantly** - Create amazing content instantly with AI 🚀
