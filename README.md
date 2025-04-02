# Social Media App (aka. Social Sphere)

A modern social media platform built with React, TypeScript, and Appwrite backend.

🌐 **Live Demo (deployed on Vercel)**: [social-media-app-pi-gold.vercel.app](https://social-media-app-pi-gold.vercel.app)

## 🚀 Features

- **Authentication System**

  - Sign up and sign in functionality
  - Protected routes
  - User profile management

- **Social Features**
  - Create, edit, and delete posts
  - Explore feed
  - Save posts
  - User profiles
  - Follow/unfollow users

## 🛠️ Tech Stack

- **Frontend Framework**: React 18 with TypeScript
- **Styling**: Tailwind CSS
- **Backend**: Appwrite
- **State Management**: React Query
- **Form Handling**: React Hook Form with Zod validation
- **UI Components**: Radix UI and shadcn
- **Routing**: React Router v6
- **Build Tool**: Vite

## 📁 Project Structure

```
src/
├── _auth/           # Authentication related components
├── _root/           # Main application pages
├── components/      # Reusable UI components
├── context/         # React context providers
├── constants/       # Application constants
├── hooks/          # Custom React hooks
├── lib/            # Utility functions and configurations
└── types/          # TypeScript type definitions
```

## 🔒 Authentication

The application uses Appwrite for authentication, providing:

- Email/password authentication
- Protected routes
- Session management
- User profile management

## 🎨 UI/UX

- Modern and responsive design
- Toast notifications
- Loading states
- Form validation
- File upload support
- Infinite scrolling
