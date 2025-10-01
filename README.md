# 🎬 YouTube Downloader Premium

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Node](https://img.shields.io/badge/node-%3E%3D16.0.0-brightgreen.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)

A modern, premium YouTube downloader web application with an elegant glassmorphism UI. Download YouTube videos and audio in multiple formats and resolutions with a beautiful, responsive interface.

## ✨ Features

- 🎨 **Premium Glassmorphism UI** - Modern, elegant design with smooth animations
- 📱 **Fully Responsive** - Works perfectly on desktop, tablet, and mobile devices
- 🎥 **Multiple Video Quality Options** - Choose from 144p to 4K quality
- 🎵 **Audio-Only Downloads** - Extract audio in MP3 format
- ⚡ **Fast & Efficient** - Quick downloads with progress tracking
- 🔒 **Secure** - No data stored, privacy-focused
- 🌙 **Dark/Light Mode** - Comfortable viewing in any lighting
- ♿ **Accessible** - WCAG 2.1 compliant for all users
- 🔄 **Real-time Progress** - Live download progress indicators
- 📊 **Video Information** - Preview thumbnail, title, duration, and views

## 🚀 Quick Start

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Jayasakthi-07/youtube-downloader-premium.git
   cd youtube-downloader-premium
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000`

## 🎯 Usage

1. Paste a YouTube video URL into the input field
2. Click "Get Video Info" to fetch video details
3. Select your preferred format and quality
4. Click "Download" to start downloading
5. Your video will be saved to your downloads folder

## 🏗️ Project Structure

```
youtube-downloader-premium/
├── public/
│   ├── index.html
│   ├── favicon.ico
│   └── demo/
│       ├── demo1.png
│       ├── demo2.png
│       └── demo.gif
├── src/
│   ├── components/
│   │   ├── Header.js
│   │   ├── VideoInput.js
│   │   ├── VideoInfo.js
│   │   ├── DownloadOptions.js
│   │   └── Footer.js
│   ├── styles/
│   │   ├── App.css
│   │   ├── glassmorphism.css
│   │   └── animations.css
│   ├── utils/
│   │   ├── youtube-api.js
│   │   └── download-helper.js
│   ├── App.js
│   └── index.js
├── server/
│   ├── server.js
│   ├── routes/
│   │   └── download.js
│   └── utils/
│       └── ytdl-wrapper.js
├── package.json
├── README.md
├── LICENSE
└── .gitignore
```

## 🌐 Deployment

### Deploy to Vercel

1. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Deploy:
   ```bash
   vercel
   ```

3. Follow the prompts to complete deployment

### Deploy to Netlify

1. Build the project:
   ```bash
   npm run build
   ```

2. Deploy to Netlify:
   - Drag and drop the `build` folder to Netlify
   - Or use Netlify CLI:
     ```bash
     npm install -g netlify-cli
     netlify deploy --prod
     ```

### Deploy to Heroku

1. Create a Heroku app:
   ```bash
   heroku create your-app-name
   ```

2. Deploy:
   ```bash
   git push heroku main
   ```

### Deploy on VPS/Node.js Server

1. Install Node.js on your server
2. Clone the repository
3. Install dependencies: `npm install`
4. Set up environment variables
5. Run with PM2:
   ```bash
   npm install -g pm2
   pm2 start server/server.js --name "youtube-downloader"
   pm2 startup
   pm2 save
   ```

## 🔧 Configuration

Create a `.env` file in the root directory:

```env
PORT=3000
NODE_ENV=production
MAX_DOWNLOAD_SIZE=500MB
ALLOWED_ORIGINS=*
```

## 🎨 UI/UX Features

- **Glassmorphism Design** - Frosted glass effect with backdrop blur
- **Smooth Animations** - CSS transitions and keyframe animations
- **Gradient Backgrounds** - Dynamic, eye-catching gradients
- **Hover Effects** - Interactive element responses
- **Loading States** - Beautiful loading animations
- **Error Handling** - User-friendly error messages
- **Toast Notifications** - Non-intrusive feedback
- **Responsive Grid** - Adaptive layout for all screens

## 📸 Screenshots

### Desktop View
![Desktop View](public/demo/demo1.png)

### Mobile View
![Mobile View](public/demo/demo2.png)

### Download in Action
![Download Demo](public/demo/demo.gif)

## 🛠️ Technologies Used

### Frontend
- React.js
- CSS3 (Glassmorphism, Animations)
- Axios for API calls
- React Icons

### Backend
- Node.js
- Express.js
- ytdl-core (YouTube download library)
- cors
- helmet (Security)

## 📦 Dependencies

```json
{
  "dependencies": {
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "axios": "^1.4.0",
    "express": "^4.18.2",
    "ytdl-core": "^4.11.5",
    "cors": "^2.8.5",
    "helmet": "^7.0.0",
    "dotenv": "^16.0.3"
  }
}
```

## 🔐 Security Features

- CORS protection
- Helmet.js for security headers
- Input validation and sanitization
- Rate limiting
- No data storage (privacy-first)
- HTTPS enforcement in production

## ⚡ Performance Optimizations

- Code splitting
- Lazy loading
- Optimized images
- Minified assets
- Gzip compression
- CDN support
- Efficient caching

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/AmazingFeature`
3. Commit your changes: `git commit -m 'Add some AmazingFeature'`
4. Push to the branch: `git push origin feature/AmazingFeature`
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

This tool is for educational purposes only. Please respect YouTube's Terms of Service and copyright laws. Download videos only if you have permission or they are in the public domain.

## 🙏 Acknowledgments

- ytdl-core library for YouTube downloading functionality
- React community for excellent documentation
- All contributors who help improve this project

## 📞 Support

If you encounter any issues or have questions:

- Open an [Issue](https://github.com/Jayasakthi-07/youtube-downloader-premium/issues)
- Star ⭐ this repository if you find it helpful!

## 🔄 Changelog

### Version 1.0.0 (October 2025)
- Initial release
- Premium glassmorphism UI
- Multiple format support
- Responsive design
- Full functionality

---

**Made with ❤️ by Jayasakthi-07**

[🔝 Back to Top](#-youtube-downloader-premium)
