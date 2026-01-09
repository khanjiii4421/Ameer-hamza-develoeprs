# 🏗️ 3D Construction Website

A **fully immersive, enterprise-level 3D construction website** featuring glassmorphism UI, cinematic animations, and a complete admin panel for content management.

![Next.js](https://img.shields.io/badge/Next.js-16.1.1-black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)
![Three.js](https://img.shields.io/badge/Three.js-Latest-green)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-cyan)

---

## ✨ Features

### 🎨 Design
- **Dark Glassmorphism Theme** - Frosted glass UI with backdrop blur effects
- **3D Animations** - Fully interactive Three.js scenes
- **Cinematic Transitions** - GSAP & Framer Motion animations
- **Responsive Design** - Optimized for desktop, tablet, and mobile
- **Premium Aesthetics** - Vibrant gradients and micro-interactions

### 🏠 Pages
- **Home** - 3D hero with animated construction site, crane, and building
- **About** - Interactive timeline, core values, and team section
- **Services** - 4 main services with detailed subpages
- **Contact** - Glassmorphism form with validation

### 🛠️ Services
1. **Grey Structure** - Foundation and structural framework
2. **Architecture** - Innovative architectural design
3. **Interior Design** - Beautiful, functional spaces
4. **Construction & Development** - End-to-end project management

---

## 🚀 Tech Stack

### Frontend
- **Framework**: Next.js 16 (App Router)
- **Language**: TypeScript
- **3D Graphics**: Three.js + React Three Fiber
- **3D Helpers**: @react-three/drei, @react-three/postprocessing
- **Animations**: GSAP, Framer Motion
- **Styling**: Tailwind CSS (custom glassmorphism theme)
- **Icons**: React Icons

### Backend (Planned)
- **Runtime**: Node.js
- **API**: Next.js API Routes
- **Database**: MongoDB with Mongoose
- **Authentication**: JWT + bcrypt

---

## 📦 Installation

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Setup

1. **Clone the repository**
```bash
git clone <repository-url>
cd construction-3d-website
```

2. **Install dependencies**
```bash
npm install
```

3. **Run development server**
```bash
npm run dev
```

4. **Open in browser**
```
http://localhost:3000
```

---

## 📁 Project Structure

```
construction-website/
├── app/
│   ├── layout.tsx              # Root layout
│   ├── page.tsx                # Home page
│   ├── about/page.tsx          # About page
│   ├── services/
│   │   ├── page.tsx            # Services overview
│   │   └── [slug]/page.tsx     # Dynamic service pages
│   ├── contact/page.tsx        # Contact page
│   └── globals.css             # Global styles
│
├── components/
│   ├── 3d/
│   │   └── Hero3D.tsx          # 3D hero scene
│   ├── ui/
│   │   ├── GlassCard.tsx       # Glassmorphism card
│   │   ├── GlassButton.tsx     # Glass button
│   │   └── LoadingScreen.tsx   # Loading animation
│   ├── layout/
│   │   ├── Header.tsx          # Navigation header
│   │   └── Footer.tsx          # Footer
│   └── sections/
│       ├── CompanyIntro.tsx
│       ├── FeaturedProjects.tsx
│       ├── ServicesPreview.tsx
│       ├── TrustIndicators.tsx
│       ├── AboutHero.tsx
│       ├── CompanyTimeline.tsx
│       ├── CoreValues.tsx
│       └── TeamSection.tsx
│
├── lib/
│   └── utils.ts                # Utility functions
│
├── public/
│   └── assets/
│       └── images/             # Image assets
│
├── tailwind.config.ts          # Tailwind configuration
├── next.config.ts              # Next.js configuration
└── package.json                # Dependencies
```

---

## 🎨 Design System

### Colors
```css
Primary:    #0ea5e9 (Sky Blue)
Secondary:  #8b5cf6 (Violet)
Accent:     #f59e0b (Amber)
Background: #0a0a0a (Dark)
Glass:      rgba(255, 255, 255, 0.05)
```

### Glassmorphism Classes
- `.glass` - Base glass effect
- `.glass-card` - Glass card with hover effect
- `.glass-button` - Animated glass button
- `.glass-input` - Glass input field
- `.gradient-text` - Gradient text effect

### Animations
- `animate-float` - Floating animation
- `animate-glow` - Glow effect
- `animate-slide-up` - Slide up animation
- `animate-fade-in` - Fade in animation

---

## 🎯 Key Components

### Hero3D
Fully immersive 3D scene featuring:
- Animated 3D building with glowing windows
- Construction crane with rotation
- Floating particles
- Auto-rotating camera
- Cinematic lighting (ambient + directional + point lights)

### GlassCard
Reusable glassmorphism card component with:
- Backdrop blur effect
- Hover animations
- Customizable variants

### GlassButton
Animated button component with:
- 3 variants (primary, secondary, accent)
- 3 sizes (sm, md, lg)
- Hover effects and transitions

---

## 📱 Responsive Breakpoints

```css
Mobile:  < 768px   (Simplified 3D)
Tablet:  768-1024px (Medium 3D)
Desktop: > 1024px   (Full 3D experience)
```

---

## 🔧 Configuration

### Tailwind Config
Custom theme with glassmorphism utilities, animations, and color palette.

### Next.js Config
- Turbopack enabled for faster builds
- Three.js transpilation
- Image optimization

---

## 🚧 Roadmap

### Phase 1: Core Pages ✅
- [x] Home page with 3D hero
- [x] About page with timeline
- [x] Services page
- [x] Service detail pages
- [x] Contact page

### Phase 2: Backend (In Progress)
- [ ] MongoDB setup
- [ ] API routes
- [ ] Content schemas
- [ ] Authentication

### Phase 3: Admin Panel
- [ ] Admin login
- [ ] Content management
- [ ] Service management
- [ ] Media uploader
- [ ] SEO controls

### Phase 4: Enhancements
- [ ] More 3D models
- [ ] GSAP scroll animations
- [ ] Page transitions
- [ ] Performance optimization
- [ ] Google Maps integration

---

## 📊 Performance

### Optimizations
- Code splitting
- Dynamic imports
- Image optimization (Next.js Image)
- Lazy loading for 3D assets
- Level of Detail (LOD) for models
- Frustum culling

---

## 🎬 Scripts

```bash
npm run dev      # Start development server
npm run build    # Build for production
npm run start    # Start production server
npm run lint     # Run ESLint
```

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Construction Company**
- Website: www.ameerhamzadevelopers.com
- Email: info.ameerhamzadevelopers@gmail.com
- Phone: +923219300005

---

## 🙏 Acknowledgments

- **Next.js** - React framework
- **Three.js** - 3D graphics library
- **Tailwind CSS** - Utility-first CSS framework
- **Framer Motion** - Animation library
- **GSAP** - Professional-grade animation

---

## 📸 Screenshots

### Home Page
![Home Page](./screenshots/home.png)

### About Page
![About Page](./screenshots/about.png)

### Services Page
![Services Page](./screenshots/services.png)

### Contact Page
![Contact Page](./screenshots/contact.png)

---

## 🔗 Links

- [Documentation](./IMPLEMENTATION_PLAN.md)
- [Progress Report](./PROGRESS.md)
- [Live Demo](#) (Coming Soon)

---

**Built with ❤️ Khandev hub **


