# Replit.md

## Overview

This is a static website for Dore Canine Services, a professional dog care business specializing in large breeds. The website is built as a single-page React application that showcases the business's services including dog walking, grooming, training, and pet sitting. The site emphasizes the owner's credentials (DBS-checked, canine first aid certified) and targets premium customers seeking professional pet care services.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: React with modern JavaScript (ES6+)
- **Build System**: Vite-based build process generating optimized production assets
- **Styling**: Tailwind CSS framework with custom Google Fonts integration (Playfair Display, Open Sans)
- **Bundle Structure**: Single-page application with code-splitting resulting in separate CSS and JS chunks
- **Responsive Design**: Mobile-first approach with viewport optimization

### Component Structure
- **Single Root Component**: All functionality contained within one React application mounted to `#root`
- **Static Content Focus**: Business information, services, credentials, and contact details
- **No State Management**: Simple presentational components without complex state logic

### Asset Management
- **Font Loading**: Preconnected Google Fonts with display optimization
- **Bundle Optimization**: Production build creates fingerprinted assets for cache busting
- **Static Assets**: Minified and optimized CSS/JS files served from `/assets/` directory

### SEO and Meta Optimization
- **Open Graph Integration**: Social media sharing optimization with proper metadata
- **Semantic HTML**: Proper document structure with meaningful meta descriptions
- **Local Business Focus**: UK-specific locale settings and business-oriented content

## External Dependencies

### Core Technologies
- **React**: Frontend framework for component-based UI
- **Vite**: Build tool and development server
- **Tailwind CSS**: Utility-first CSS framework

### Font Services
- **Google Fonts**: Typography via CDN (Playfair Display, Open Sans, additional font families)

### Development Tools
- **Replit Integration**: Development environment with live preview capabilities
- **Modern JavaScript**: ES6+ features with module bundling

### Hosting Considerations
- **Static Hosting Ready**: Can be deployed to GitHub Pages, Netlify, Vercel, or any static host
- **No Backend Dependencies**: Pure frontend application requiring no server-side processing
- **CDN Friendly**: Optimized asset structure for content delivery networks