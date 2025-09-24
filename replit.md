# V380 Pro 操作指南手機版

## Overview

This is a mobile-first instructional application designed to guide Chinese-speaking users through the step-by-step process of operating V380 Pro surveillance cameras. The application provides a structured walkthrough for WiFi setup, real-time viewing, recording playback, and date/time selection. It follows a tutorial-style approach with clear visual progress indicators, sequential step cards, and mobile-optimized navigation controls.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **React + TypeScript**: Modern React application with TypeScript for type safety
- **Vite**: Build tool and development server for fast development experience
- **Wouter**: Lightweight client-side routing library for navigation
- **shadcn/ui + Radix UI**: Comprehensive component library built on Radix primitives
- **Tailwind CSS**: Utility-first CSS framework with custom design system
- **TanStack Query**: Data fetching and state management library

### Design System
- **Mobile-First Approach**: Designed specifically for mobile devices with touch-friendly interfaces
- **Chinese Typography**: Uses 'Noto Sans TC' for optimized Traditional Chinese text rendering
- **Color Palette**: Professional blue primary (#220 85% 45%) with semantic color tokens
- **Component Structure**: Modular components including StepCard, ProgressIndicator, NavigationControls, and WarningAlert
- **Layout System**: Consistent spacing using Tailwind primitives (2, 4, 6, 8, 12, 16)

### Backend Architecture
- **Express.js**: Node.js web framework for API endpoints
- **TypeScript**: Full-stack TypeScript implementation
- **Modular Route System**: Organized route handlers with middleware support
- **Development Tools**: Hot module replacement with Vite integration

### Data Layer
- **Drizzle ORM**: Type-safe database interactions
- **PostgreSQL**: Primary database (via Neon serverless)
- **Schema Management**: Centralized schema definitions in shared directory
- **Connection Pooling**: Configured for serverless environments

### Component Architecture
- **Atomic Design**: Components organized from basic UI elements to complex page layouts
- **Prop-based Configuration**: Flexible components with comprehensive prop interfaces
- **Event Handling**: Structured callback system for user interactions
- **State Management**: Local component state with React hooks

### Application Structure
- **Step-based Navigation**: 8-step process for camera operation
- **Progress Tracking**: Visual indicators for completion status
- **Responsive Design**: Optimized for mobile screens with touch targets
- **Accessibility**: ARIA labels and semantic HTML structure

## External Dependencies

### UI Component Libraries
- **@radix-ui/**: Complete set of accessible UI primitives (accordion, alert-dialog, avatar, checkbox, etc.)
- **shadcn/ui**: Pre-built components following design system conventions
- **lucide-react**: Icon library for consistent iconography
- **class-variance-authority**: Utility for managing component variants
- **tailwind-merge & clsx**: CSS class manipulation utilities

### Development Tools
- **@replit/vite-plugin-runtime-error-modal**: Development error overlay
- **@replit/vite-plugin-cartographer**: Development navigation tools
- **drizzle-kit**: Database schema management and migrations
- **tsx**: TypeScript execution for development

### Database & ORM
- **@neondatabase/serverless**: Serverless PostgreSQL driver
- **drizzle-orm**: Type-safe SQL query builder
- **drizzle-zod**: Schema validation integration
- **connect-pg-simple**: PostgreSQL session store

### State Management & Data Fetching
- **@tanstack/react-query**: Server state management and caching
- **@hookform/resolvers**: Form validation resolvers
- **zod**: Runtime type validation

### Styling & Animation
- **tailwindcss**: Core CSS framework
- **autoprefixer**: CSS vendor prefixing
- **embla-carousel-react**: Carousel component functionality
- **date-fns**: Date manipulation utilities

### Fonts & Typography
- **Google Fonts**: Noto Sans TC for Traditional Chinese text optimization
- **Open Sans**: Secondary font for Latin characters