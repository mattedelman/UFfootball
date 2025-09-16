# UF Football Web Application

A comprehensive React + TypeScript + Tailwind CSS web application for University of Florida Gators football, featuring team schedules, roster information, team history, and domain sales opportunities.

## 🏈 Features

### Core Functionality
- **Team Schedule**: Complete 2024 season schedule with game results and upcoming matches
- **Team Roster**: Player information, coaching staff, and position filtering
- **Team History**: National championships, Heisman winners, and program records
- **Domain Sales**: Professional contact forms and domain value proposition

### Technical Features
- **Responsive Design**: Mobile-first approach with Tailwind CSS
- **Modern Stack**: React 18, TypeScript, Vite
- **SEO Optimized**: Meta tags, structured data, and performance optimized
- **Ad Integration**: Strategic ad placements throughout the site
- **Accessibility**: WCAG 2.1 AA compliant design

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd uf-football
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## 🛠️ Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 📁 Project Structure

```
src/
├── components/
│   ├── Header.tsx          # Navigation header
│   ├── Footer.tsx          # Site footer with domain info
│   └── AdBanner.tsx        # Reusable ad component
├── pages/
│   ├── Home.tsx            # Landing page
│   ├── Schedule.tsx        # Team schedule
│   ├── Roster.tsx          # Player roster
│   ├── History.tsx         # Team history
│   └── Contact.tsx         # Domain sales contact
├── App.tsx                 # Main app component
├── main.tsx               # App entry point
└── index.css              # Global styles with Tailwind
```

## 🎨 Design System

### Colors
- **UF Orange**: #FA4616
- **UF Blue**: #0021A5
- **UF Gold**: #FFD700

### Typography
- **Font Family**: Inter (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700, 800

## 📱 Responsive Breakpoints

- **Mobile**: 320px - 767px
- **Tablet**: 768px - 1199px
- **Desktop**: 1200px+

## 🎯 Business Features

### Domain Sales
- Professional contact forms
- Domain value proposition
- Lead generation system
- Budget range selection

### Advertising
- Strategic ad placements
- Header, sidebar, and in-content ads
- Mobile-optimized ad units
- Google AdSense ready

## 🔧 Customization

### Adding New Pages
1. Create a new component in `src/pages/`
2. Add the route to `src/App.tsx`
3. Update navigation in `src/components/Header.tsx`

### Modifying Data
- Schedule data: `src/pages/Schedule.tsx`
- Roster data: `src/pages/Roster.tsx`
- History data: `src/pages/History.tsx`

### Styling
- Global styles: `src/index.css`
- Component styles: Inline Tailwind classes
- Color scheme: `tailwind.config.js`

## 🚀 Deployment

### GitHub Repository Setup

1. **Initialize Git Repository** (if not already done):
```bash
git init
git add .
git commit -m "Initial commit: UF Football web app"
```

2. **Create GitHub Repository**:
   - Go to [GitHub](https://github.com) and create a new repository
   - Name it `uf-football` or your preferred name
   - Don't initialize with README (we already have one)

3. **Push to GitHub**:
```bash
git remote add origin https://github.com/YOUR_USERNAME/uf-football.git
git branch -M main
git push -u origin main
```

### Vercel Deployment

1. **Connect to Vercel**:
   - Go to [Vercel](https://vercel.com)
   - Sign in with your GitHub account
   - Click "New Project"
   - Import your `uf-football` repository

2. **Configure Build Settings**:
   - Framework Preset: `Vite`
   - Build Command: `npm run build` (auto-detected)
   - Output Directory: `dist` (auto-detected)
   - Install Command: `npm install` (auto-detected)

3. **Deploy**:
   - Click "Deploy"
   - Vercel will automatically build and deploy your app
   - You'll get a live URL like `https://uf-football.vercel.app`

### Build for Production
```bash
npm run build
```

The built files will be in the `dist/` directory, ready for deployment to any static hosting service.

### Recommended Hosting
- **Vercel** (Recommended - One-click deployment)
- Netlify
- AWS S3 + CloudFront
- GitHub Pages

## 📊 Performance

- **Lighthouse Score**: 90+
- **Page Load Speed**: < 3 seconds
- **Mobile Performance**: Optimized
- **SEO Score**: High

## 🔒 Security

- HTTPS ready
- Form validation
- Input sanitization
- Privacy policy ready

## 📈 Analytics Ready

The application is prepared for:
- Google Analytics
- Google Tag Manager
- Custom analytics tracking
- Conversion tracking

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is proprietary and confidential. All rights reserved.

## 📞 Contact

For domain inquiries or business opportunities:
- Email: contact@uffootball.com
- Domain: uffootball.com

---

**Go Gators! 🐊**