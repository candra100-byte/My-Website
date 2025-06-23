# SIMPONI - Sistem Pemantauan Imunisasi

## Overview

SIMPONI is an immunization monitoring system designed specifically for Central Lombok (Lombok Tengah) that integrates local wisdom to improve basic immunization coverage. The application features a modern web interface for tracking children's immunization schedules, managing SMS reminders, and incorporating traditional practices to encourage vaccination participation.

## System Architecture

### Frontend Architecture
- **Framework**: React 18 with TypeScript
- **UI Library**: Radix UI components with Tailwind CSS styling
- **State Management**: TanStack Query for server state management
- **Routing**: Wouter for lightweight client-side routing
- **Form Management**: React Hook Form with Zod validation
- **Build Tool**: Vite for fast development and optimized builds

### Backend Architecture
- **Runtime**: Node.js 20 with Express.js
- **Database**: PostgreSQL with Drizzle ORM
- **Authentication**: Passport.js with local strategy and session-based auth
- **Session Store**: PostgreSQL-backed sessions via connect-pg-simple
- **API Design**: RESTful API endpoints with consistent error handling

### Styling and Design System
- **CSS Framework**: Tailwind CSS with custom SIMPONI color palette
- **Components**: shadcn/ui component library (New York variant)
- **Theme**: Cultural-inspired design with local Lombok aesthetic elements
- **Responsive**: Mobile-first design approach

## Key Components

### Database Schema (PostgreSQL + Drizzle)
1. **Users Table**: System users (petugas/staff) with role-based access
2. **Children Table**: Child registration with demographics and contact info
3. **Immunizations Table**: Vaccination schedule tracking with status management
4. **SMS Logs Table**: Message delivery tracking and history
5. **Local Wisdom Table**: Cultural practices and traditional knowledge integration

### Authentication System
- Session-based authentication using Passport.js
- Encrypted password storage with scrypt hashing
- Role-based access control (petugas role)
- Protected routes with authentication middleware

### Core Features
1. **Dashboard**: Real-time statistics and overview of immunization progress
2. **Child Management**: Registration and profile management
3. **Immunization Tracking**: Schedule management with status updates
4. **SMS Gateway**: Automated reminders and notifications
5. **Local Wisdom Integration**: Cultural practices to encourage participation

## Data Flow

1. **User Authentication**: Login → Session creation → Route protection
2. **Child Registration**: Form submission → Validation → Database storage
3. **Immunization Scheduling**: Child selection → Vaccine scheduling → Status tracking
4. **SMS Notifications**: Automated triggers → Message queuing → Delivery tracking
5. **Real-time Updates**: Client queries → Server response → UI state updates

## External Dependencies

### Core Dependencies
- **@neondatabase/serverless**: PostgreSQL connection (Neon database)
- **drizzle-orm**: Type-safe database ORM
- **@tanstack/react-query**: Server state management
- **passport**: Authentication middleware
- **express-session**: Session management

### UI Dependencies
- **@radix-ui/***: Accessible UI primitives
- **tailwindcss**: Utility-first CSS framework
- **lucide-react**: Icon library
- **react-hook-form**: Form state management
- **zod**: Schema validation

### Development Dependencies
- **tsx**: TypeScript execution for development
- **esbuild**: Fast JavaScript bundler
- **vite**: Frontend build tool

## Deployment Strategy

### Development Environment
- **Runtime**: Node.js 20 with Replit hosting
- **Database**: PostgreSQL 16 (provisioned via environment)
- **Hot Reload**: Vite HMR for frontend, tsx for backend
- **Port**: Development server runs on port 5000

### Production Build
- **Frontend**: Vite build process generates optimized static assets
- **Backend**: ESBuild bundles server code for production
- **Static Assets**: Served from dist/public directory
- **Process**: Single Node.js process serving both API and static files

### Environment Configuration
- **Database**: Requires DATABASE_URL environment variable
- **Sessions**: Requires SESSION_SECRET for secure session management
- **Deployment**: Configured for Replit's autoscale deployment target

## Changelog
- June 23, 2025. Initial setup

## User Preferences

Preferred communication style: Simple, everyday language.