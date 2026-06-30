# My Portfolio Website – Requirements (NextJS + Prisma + ExpressJS)

A modern, full-stack portfolio website built with Next.js 15, featuring a personal blog, project showcase, and admin dashboard for content management.

🌐 **Live Demo**: [https://assignment-07-gamma.vercel.app](https://assignment-07-gamma.vercel.app)

## 📋 Project Overview

This is a comprehensive portfolio website that serves as both a personal showcase and a content management system. It features a clean, responsive design with dark/light theme support, allowing visitors to explore projects, read blog posts, and learn about the developer's skills and experience.

## ✨ Project Features

### 🎨 Frontend Features
- **Responsive Design** - Optimized for all device sizes
- **Dark/Light Theme** - Toggle between themes with system preference detection
- **Interactive Hero Section** - Typewriter effect and animated elements
- **Project Showcase** - Detailed project cards with live demos and source code links
- **Blog System** - Read and browse blog posts with filtering capabilities
- **About Section** - Personal information, skills, and experience
- **Loading States** - Skeleton screens for better UX

### 🔐 Admin Dashboard
- **Authentication System** - Secure login for content management
- **Blog Management** - Create, edit, delete, and publish blog posts
- **Project Management** - Add, update, and manage portfolio projects
- **Dashboard Analytics** - Overview of blogs, projects, and activity
- **Profile Management** - Update personal information and skills
- **Image Upload** - Cloudinary integration for media management

### 🚀 Performance Features
- **Server-Side Rendering** - Fast initial page loads
- **Static Generation** - Optimized build performance
- **Image Optimization** - Next.js Image component with Cloudinary
- **Turbopack** - Fast development and build times

## 🛠️ Technology Stack

### Frontend
- **Next.js 15** - React framework with App Router
- **React 19** - Latest React features
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first CSS framework
- **DaisyUI** - Tailwind CSS components

### UI Components & Libraries
- **Radix UI** - Headless UI components
- **Lucide React** - Modern icon library
- **React Icons** - Popular icon sets
- **React Hook Form** - Form handling and validation
- **React Hot Toast** - Toast notifications
- **SweetAlert2** - Beautiful alerts and modals

### Additional Features
- **next-themes** - Theme switching functionality
- **Cloudinary** - Image upload and optimization
- **React DatePicker** - Date selection component
- **Typewriter Effect** - Animated text effects
- **timeago.js** - Relative time formatting

### Development Tools
- **ESLint** - Code linting
- **PostCSS** - CSS processing
- **Turbopack** - Fast bundler for development

## 🚀 Setup Instructions

### Prerequisites
- Node.js 18+
- npm, yarn, pnpm, or bun

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd assignment-07
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Environment Setup**
   Create a `.env.local` file in the root directory:
   ```env
   NEXT_PUBLIC_API_URL=your_api_url
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   ```

4. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

### Build for Production

```bash
npm run build
npm start
```

## 📁 Project Structure

```
src/
├── app/                    # Next.js App Router
│   ├── (public)/          # Public pages (home, about, blog, projects)
│   ├── (dashboard)/       # Protected dashboard pages
│   ├── login/             # Authentication page
│   └── layout.tsx         # Root layout
├── components/            # React components
│   ├── models/           # Feature-specific components
│   ├── shared/           # Reusable components
│   └── ui/               # Base UI components
├── types/                # TypeScript type definitions
├── actions/              # Server actions and utilities
├── lib/                  # Configuration and utilities
└── helpers/              # Helper functions
```

## 🌟 Key Pages

- **Home** (`/`) - Hero section, about preview, featured projects, and latest blogs
- **About** (`/about`) - Detailed personal information, skills, and experience
- **Projects** (`/projects`) - Complete project showcase with filtering
- **Blog** (`/blog`) - Blog posts with search and category filtering
- **Dashboard** (`/dashboard`) - Admin panel for content management
- **Login** (`/login`) - Authentication page

## 📝 Additional Notes

### Deployment
- **Vercel Deployment** - Optimized for Vercel platform
- **Environment Variables** - Secure configuration management
- **Static Assets** - Optimized image and asset delivery

### Performance Optimizations
- Image optimization with Next.js Image component
- Code splitting and lazy loading
- Server-side rendering for better SEO
- Efficient bundle size with tree shaking

---

**Built with ❤️ using Next.js 15 and modern web technologies**

                             **Built By Hamim ❤️**


