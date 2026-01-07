# 📸 Khaled Mo Photography Portfolio

<div align="center">

![Khaled Mo Photography Portfolio](https://khaledmo.com/ogpreview.png)

**Professional Photography Portfolio | Modern Next.js 15 Application**

[![Next.js](https://img.shields.io/badge/Next.js-15.4.10-black?logo=next.js)](https://nextjs.org)
[![React](https://img.shields.io/badge/React-19.0.1-61DAFB?logo=react)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8.3-3178C6?logo=typescript)](https://www.typescriptlang.org)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4.17-38BDF8?logo=tailwind-css)](https://tailwindcss.com)
[![Framer Motion](https://img.shields.io/badge/Framer_Motion-Latest-FF6B6B?logo=framer)](https://www.framer.com/motion)
[![GSAP](https://img.shields.io/badge/GSAP-3.13.0-00D084?logo=greensock)](https://gsap.com)
[![Vercel](https://img.shields.io/badge/Deployed_on-Vercel-black?logo=vercel)](https://vercel.com)


[ Live ](https://khaledmo.com) | [📱 Mobile Optimized](https://khaledmo.com) | [🔍 SEO Optimized](https://khaledmo.com)

</div>

---

##  Project Overview

**Khaled Mo Photography Portfolio** is a cutting-edge, professional photography portfolio website built with Next.js 15 and React 19. It showcases the work of Khaled Mo, a professional photographer specializing in personal branding, commercial photography, and event coverage in Egypt and the Middle East.

### Key Highlights

- **Modern Architecture**: Built with Next.js 15 App Router and React 19
- **Performance First**: Optimized for Core Web Vitals and SEO
- **Interactive Experience**: Advanced animations with Framer Motion and GSAP
- **Professional Design**: Clean, modern interface with attention to detail
- **Mobile Optimized**: Fully responsive design for all devices
- **SEO Excellence**: Comprehensive SEO optimization with structured data

### Professional Background

**Khaled Mo** is a professional photographer with:
- **25+ Years Experience** in professional photography
- **2000+ Talents Trained** in photography techniques
- **500+ Projects Delivered** successfully
- **100+ Brand Partners** worldwide
- **Founder of Tawseeq** - platform integrating photography with marketing

---

##  Features

###  Core Features

- **Dynamic Photo Collections**: Automatically loads and displays photos from organized collections
- **Interactive Gallery**: Masonry layout with smooth transitions and hover effects
- **Advanced Animations**: Powered by Framer Motion and GSAP for smooth interactions
- **Sound Effects**: Professional camera shutter sounds for enhanced UX
- **Custom Cursor**: Interactive target cursor for desktop users
- **Image Trail**: Dynamic image trail following mouse movement
- **Smooth Scrolling**: Enhanced navigation experience with scroll animations

###  Photography Showcase

- **16 Professional Collections**: Comprehensive portfolio showcasing diverse work
- **Featured Projects**: Highlighted collections for maximum impact
- **Tag-based Filtering**: Easy navigation through different photography categories
- **High-Quality Images**: Cloudinary-hosted images for optimal performance
- **Metadata Display**: Professional camera settings and technical details
- **Lightbox Gallery**: Full-screen viewing experience

###  Visual Experience

- **Intro Animation**: Professional loading sequence with brand reveal
- **Parallax Effects**: Depth and movement throughout the site
- **Gradient Overlays**: Sophisticated color treatments
- **Typography**: Custom font loading with Old London display font
- **Dark Theme**: Professional dark interface optimized for photography
- **Visual Hierarchy**: Clear content organization and flow

###  User Experience

- **Mobile-First Design**: Optimized for all screen sizes
- **Touch Interactions**: Gesture-friendly mobile interface
- **Fast Loading**: Optimized images and code splitting
- **Accessibility**: WCAG compliant with keyboard navigation
- **Progressive Enhancement**: Works without JavaScript
- **Offline Support**: Service worker implementation

---

##  Technology Stack

###  Frontend Framework

- **Next.js 15.4.10**: Latest Next.js with App Router and React Server Components
- **React 19.0.1**: Latest React with concurrent features and improved performance
- **TypeScript 5.8.3**: Full type safety and enhanced developer experience

###  Styling & Animation

- **Tailwind CSS 3.4.17**: Utility-first CSS framework with custom design system
- **Framer Motion (Latest)**: Production-ready motion library for React
- **GSAP 3.13.0**: Professional-grade animation library
- **CSS Custom Properties**: Dynamic theming and responsive design
- **Tailwind Animate**: Extended animation utilities

###  Image & Media

- **Next/Image**: Optimized image loading with WebP/AVIF support
- **React Photo Album**: Masonry layout for gallery display
- **Cloudinary**: Professional image hosting and optimization
- **Custom Image Trail**: Dynamic mouse-following image effects

###  Development Tools

- **ESLint**: Code quality and consistency
- **PostCSS**: CSS processing and optimization
- **Autoprefixer**: Cross-browser compatibility
- **Bundle Analyzer**: Performance monitoring and optimization

###  Analytics & SEO

- **Google Analytics 4**: Advanced user behavior tracking
- **Google Tag Manager**: Flexible tag management
- **Structured Data**: JSON-LD schema markup
- **Dynamic Sitemap**: Auto-generated XML sitemap
- **Meta Tags**: Comprehensive social media optimization

---

##  Project Structure

```
khaledmo-photography-portfolio/
├── 📁 app/                          # Next.js App Router
│   ├── 📁 about/                    # About page
│   │   ├── about-client.tsx         # Client-side about component
│   │   └── page.tsx                 # About page server component
│   ├── 📁 api/                      # API routes
│   │   └── 📁 og-image/             # Dynamic OG image generation
│   ├── 📁 collections/              # Dynamic collection routes
│   │   └── 📁 [slug]/               # Individual collection pages
│   ├── 📁 showcases/                # Portfolio showcase
│   │   ├── loading.tsx              # Loading UI
│   │   ├── page.tsx                 # Showcases page
│   │   └── showcases-client.tsx     # Client-side showcase component
│   ├── error.tsx                    # Error boundary
│   ├── globals.css                  # Global styles and CSS variables
│   ├── layout.tsx                   # Root layout with providers
│   ├── loading.tsx                  # Global loading UI
│   ├── manifest.ts                  # PWA manifest generation
│   ├── page.tsx                     # Home page
│   ├── robots.ts                    # Dynamic robots.txt
│   └── sitemap.ts                   # Dynamic sitemap generation
├── 📁 components/                   # Reusable UI components
│   ├── 📁 ui/                       # Base UI components
│   │   ├── button.tsx               # Button component with variants
│   │   ├── image-trail.tsx          # Mouse-following image trail
│   │   └── target-cursor.tsx        # Custom cursor component
│   ├── animated-button.tsx          # Animated button with effects
│   ├── back-to-top.tsx              # Smooth scroll to top
│   ├── collection-grid.tsx          # Portfolio grid layout
│   ├── dynamic-og-image.tsx         # Dynamic Open Graph images
│   ├── featured-collections.tsx     # Featured work showcase
│   ├── filter-tabs.tsx              # Category filtering
│   ├── footer.tsx                   # Site footer
│   ├── global-image-trail.tsx       # Global image trail effect
│   ├── google-analytics.tsx         # GA4 integration
│   ├── google-tag-manager.tsx       # GTM integration
│   ├── header.tsx                   # Navigation header
│   ├── hero-gallery-scroll.tsx      # Hero gallery with scroll effects
│   ├── hero-section.tsx             # Main hero section
│   ├── hero-slider.tsx              # Hero image slider
│   ├── intro-animation.tsx          # Loading animation
│   ├── intro-wrapper.tsx            # Animation wrapper
│   ├── loading.tsx                  # Loading components
│   ├── logo.tsx                     # Brand logo component
│   ├── photo-gallery.tsx            # Gallery display
│   ├── safari-theme-color.tsx       # Safari theme color
│   ├── services-section.tsx         # Services showcase
│   ├── sound-effects.tsx            # Audio feedback
│   ├── structured-data.tsx          # SEO structured data
│   ├── tag-list.tsx                 # Tag display and filtering
│   ├── trusted-clients.tsx          # Client testimonials
│   └── useDisableRightClick.ts      # Image protection hook
├── 📁 lib/                          # Utility libraries
│   ├── actions.ts                   # Server actions
│   ├── collections.ts               # Portfolio data management
│   ├── types.ts                     # TypeScript type definitions
│   └── utils.ts                     # Utility functions
├── 📁 public/                       # Static assets
│   ├── 📁 fonts/                    # Custom fonts
│   ├── 📁 Imagetrail/               # Image trail assets
│   ├── 📁 intro/                    # Intro animation assets
│   ├── 📁 trusted/                  # Client logos
│   ├── about.jpg                    # About page image
│   ├── favicon1.ico                 # Site favicon
│   ├── hero.jpg                     # Hero background
│   ├── Logo.png                     # Brand logo
│   └── ogpreview.png                # Social media preview
├── 📁 scripts/                      # Build scripts
│   └── validate-images.ts           # Image validation
├── .env.local                       # Environment variables
├── .gitignore                       # Git ignore rules
├── .vercelignore                    # Vercel ignore rules
├── components.json                  # Component configuration
├── deploy.sh                        # Deployment script
├── next.config.mjs                  # Next.js configuration
├── package.json                     # Dependencies and scripts
├── postcss.config.mjs               # PostCSS configuration
├── tailwind.config.ts               # Tailwind CSS configuration
├── tsconfig.json                    # TypeScript configuration
└── vercel.json                      # Vercel deployment config
```

---

##  Performance & SEO

###  Core Web Vitals Optimization

- **LCP (Largest Contentful Paint)**: < 2.5s with optimized images
- **FID (First Input Delay)**: < 100ms with code splitting
- **CLS (Cumulative Layout Shift)**: < 0.1 with proper image dimensions
- **TTFB (Time to First Byte)**: Optimized with Vercel Edge Network

###  SEO Excellence

- **Comprehensive Meta Tags**: Title, description, keywords in Arabic and English
- **Open Graph Optimization**: Rich social media previews
- **Twitter Cards**: Optimized Twitter sharing
- **Structured Data**: JSON-LD schema for photographers
- **Dynamic Sitemap**: Auto-generated XML sitemap
- **Robots.txt**: Search engine crawling optimization
- **Canonical URLs**: Duplicate content prevention
- **Hreflang Tags**: Multi-language SEO support

###  Performance Features

- **Image Optimization**: WebP/AVIF formats with lazy loading
- **Code Splitting**: Route-based and component-based splitting
- **Bundle Optimization**: Tree shaking and minification
- **Caching Strategy**: Aggressive caching for static assets
- **CDN Delivery**: Global content delivery via Vercel
- **Compression**: Gzip/Brotli compression enabled

###  Security Headers

- **Content Security Policy**: XSS protection
- **X-Frame-Options**: Clickjacking prevention
- **X-Content-Type-Options**: MIME type sniffing protection
- **Referrer Policy**: Privacy protection
- **Permissions Policy**: Feature access control

---

##  Design System

###  Color Palette

- **Background**: Pure black (#000000) for professional photography display
- **Foreground**: White (#FFFFFF) for maximum contrast
- **Muted**: Gray variations for secondary content
- **Accent**: Subtle gradients for interactive elements

###  Typography

- **Display Font**: Old London (custom loaded) for brand identity
- **Body Font**: Inter (Google Fonts) for readability
- **Font Weights**: 400, 500, 600, 700 for hierarchy
- **Font Loading**: Optimized with next/font for performance

###  Animation System

- **Duration**: 300ms (fast), 600ms (medium), 1000ms (slow)
- **Easing**: Custom cubic-bezier curves for natural motion
- **Stagger**: Progressive animation reveals
- **Scroll Triggers**: GSAP ScrollTrigger for scroll-based animations
- **Parallax**: Subtle depth effects throughout

###  Responsive Breakpoints

- **Mobile**: < 640px (sm)
- **Tablet**: 640px - 1024px (md/lg)
- **Desktop**: > 1024px (xl)
- **Large**: > 1280px (2xl)

---

##  Responsive Design

###  Mobile-First Approach

- **Touch-Friendly**: Large tap targets and gesture support
- **Performance**: Optimized for mobile networks
- **Navigation**: Collapsible menu with smooth animations
- **Images**: Responsive images with appropriate sizes
- **Typography**: Scalable text for all screen sizes

###  Device Optimization

- **iPhone/Android**: Native-like experience with PWA features
- **Tablet**: Optimized layout for medium screens
- **Desktop**: Full-featured experience with advanced interactions
- **Large Screens**: Expanded layouts for professional displays

---

##  Analytics & Tracking

###  Google Analytics 4

- **Page Views**: Track all page visits
- **User Engagement**: Monitor user behavior
- **Conversion Tracking**: Track contact form submissions
- **Custom Events**: Photography-specific events
- **E-commerce**: Track service inquiries

###  Google Tag Manager

- **Flexible Tagging**: Easy tag management
- **Event Tracking**: Custom event implementation
- **Conversion Tracking**: Goal completion monitoring
- **A/B Testing**: Ready for testing implementation

###  Performance Monitoring

- **Core Web Vitals**: Real user monitoring
- **Error Tracking**: JavaScript error monitoring
- **Performance Metrics**: Load time and interaction tracking
- **User Experience**: Comprehensive UX analytics

---

##  Security Features

###  Content Protection

- **Right-Click Disable**: Image protection for portfolio
- **Copy Protection**: Prevent unauthorized copying
- **Watermarking**: Professional image watermarks
- **HTTPS Only**: Secure connection enforcement

###  Data Security

- **Environment Variables**: Secure configuration management
- **API Security**: Protected API endpoints
- **Input Validation**: Form input sanitization
- **CSRF Protection**: Cross-site request forgery prevention

###  Access Control

- **Rate Limiting**: Prevent abuse and spam
- **Bot Protection**: Automated traffic filtering
- **Geographic Restrictions**: Optional geo-blocking
- **User Agent Filtering**: Suspicious traffic detection

---

##  License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

##  Contact & Support

###  Professional Contact

- **Website**: [khaledmo.com](https://khaledmo.com)
- **Email**: info@khaledmo.com
- **Phone**: +201002769277
- **WhatsApp**: [+201002769277](https://wa.me/201002769277)

###  Social Media

- **Instagram**: [@khaledmo_photo](https://www.instagram.com/khaledmo_photo)
- **Facebook**: [khaledmo.photography](https://www.facebook.com/khaledmo.photography)
- **LinkedIn**: [khaledmo](https://www.linkedin.com/in/khaledmo)

---

##  Achievements & Recognition

- **25+ Years Experience** in professional photography
- **2000+ Talents Trained** in photography techniques
- **500+ Projects Delivered** successfully
- **100+ Brand Partners** worldwide
- **Founder of Tawseeq** - platform integrating photography with marketing
- **International Recognition** for photography excellence
- **Award-Winning Portfolio** across multiple categories

---

<div align="center">

###  Built with passion for photography and powered by cutting-edge technology

**Khaled Mo Photography Portfolio** - *Transforming Visions into Timeless Art*



</div>
