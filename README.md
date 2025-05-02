# 🌴 The Wild Oasis - Guest Portal

## 🔍 Project Overview

Wild Oasis Booking is a modern, user-friendly hotel booking platform built with Next.js that allows guests to discover, explore, and book stays at the Wild Oasis Hotel. This guest-facing application seamlessly integrates with the hotel's management system to provide real-time availability and booking capabilities.

## 🛠 Technical Stack

### Core Technologies

- **Framework**: Next.js 14 with App Router
- **Styling**: TailwindCSS
- **State Management**: Context API for UI state
- **Backend**: NextAuth for authentication and Supabase for data storage

## ✨ Key Features

### 🏨 Hotel & Cabin Discovery

- Detailed cabin listings with photos, pricing, and availability
- Real-time capacity-based filtering
- Interactive booking calendar

### 📅 Booking Management

- Streamlined reservation process
- Booking status tracking
- Modification and cancellation capabilities
- View past and upcoming reservations

### 👤 User System

- Secure authentication required for bookings
- Profile management for faster check-in
- Booking history access
- Personal information updates

## 🏗 Architecture & Code Organization

### Project Structure

```bash
src/
├── .next/                  # Next.js build output
├── app/                    # App Router pages and layouts
│   ├── _components/       # Shared components
│   ├── _lib/             # Utility functions
│   ├── _styles/          # Global styles
│   ├── about/            # About page
│   ├── account/          # User account pages
│   ├── api/              # API routes
│   │   ├── auth/        # Authentication endpoints
│   │   └── cabins/      # Cabin-related endpoints
│   ├── cabins/          # Cabin pages
│   ├── login/           # Authentication pages
│   ├── fonts/           # Custom font files
│   ├── ...      
```

### Key Design Patterns

- **App Router Structure**: Utilizing Next.js 14 file-based routing
- **Route Handlers**: API endpoints for booking operations
- **Middleware**: Authentication and route protection
- **Error Handling**: Centralized error boundaries
- **Loading States**: Optimized loading experience

## 🚀 Performance Optimizations

- Server-side rendering for improved SEO
- Image optimization with Next.js Image component
- Route prefetching for faster navigation
- Incremental Static Regeneration for cabin data
- Optimistic updates for booking actions
