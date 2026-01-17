# 💰 FinTrack AI

Web Site Link (Deployment) : https://next-fin-track-ai.vercel.app/

<img width="1916" height="913" alt="Screenshot 2026-01-17 023614" src="https://github.com/user-attachments/assets/5c9c8d00-8428-4ae7-b701-295cd3b97c6c" />

A modern, AI-powered expense tracking web application built with Next.js 15, featuring intelligent categorization, real-time analytics, and personalized financial insights.

## ✨ Features

### 🤖 AI-Powered Intelligence

- **Smart Categorization**: AI automatically suggests expense categories based on descriptions
- **Financial Insights**: Personalized recommendations and spending pattern analysis
- **Interactive AI Chat**: Get detailed explanations and advice for any insight

### 💼 Core Functionality

- **Expense Tracking**: Add, edit, and delete expenses with ease
- **Real-time Charts**: Beautiful visualizations using Chart.js
- **Statistics Dashboard**: Comprehensive spending analytics
- **Expense History**: Complete transaction history with search and filter

### 🎨 Modern UI/UX

- **Light & Dark Mode**: Seamless theme switching with smooth transitions
- **Fully Responsive**: Optimized for all screen sizes
- **Beautiful Animations**: Smooth interactions and hover effects
- **Gradient Designs**: Modern card layouts with backdrop blur effects

### 🔐 Authentication & Security

- **Multiple Login Options**: Google, GitHub, Facebook, or email/password
- **Secure Sessions**: Managed by Clerk authentication
- **User Profiles**: Personalized dashboards with user information

## 🛠️ Tech Stack

### Frontend

- **[Next.js 15](https://nextjs.org)** - React framework with App Router
- **[React 19](https://react.dev)** - Latest React with concurrent features
- **[TypeScript](https://typescriptlang.org)** - Type-safe development
- **[Tailwind CSS](https://tailwindcss.com)** - Utility-first CSS framework
- **[Chart.js](https://chartjs.org)** - Beautiful charts and visualizations

### Backend & Database

- **[Neon](https://get.neon.com/0pFcBSF)** - Serverless PostgreSQL database
- **[Prisma](https://prisma.io)** - Type-safe database ORM
- **Server Actions** - Direct server functions in Next.js

### AI & Authentication

- **[OpenRouter](https://openrouter.ai)** - Free AI API access without credit cards
- **[Clerk](https://go.clerk.com/WSe7K8F)** - Complete authentication solution
- **OpenAI Compatible API** - For intelligent expense categorization

### Deployment

- **[Vercel](https://vercel.com)** - Serverless deployment platform

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- npm, yarn, or pnpm

### Installation

1. **Clone the repository**

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory:

   ```env
   # Database
   DATABASE_URL="your-neon-database-url"

   # Clerk Authentication
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="your-clerk-publishable-key"
   CLERK_SECRET_KEY="your-clerk-secret-key"
   NEXT_PUBLIC_CLERK_SIGN_IN_URL="/sign-in"
   NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_REDIRECT_URL="/"
   NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_REDIRECT_URL="/"

   # OpenRouter AI
   OPENROUTER_API_KEY="your-openrouter-api-key"

   # App URL
   NEXT_PUBLIC_APP_URL="http://localhost:3000"
   ```

4. **Set up the database**

   ```bash
   npx prisma generate
   npx prisma db push
   ```

5. **Run the development server**

   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

6. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📊 Database Schema

The application uses a simple yet effective database schema:

- **User**: Stores user information from Clerk
- **Record**: Stores expense transactions with categories and amounts

## 🎯 Key Features Walkthrough

### 1. Smart Expense Adding

- Enter description, date, and amount
- Click the ✨ button for AI category suggestions
- Manual category selection from predefined options

### 2. AI Insights Dashboard

- Real-time spending pattern analysis
- Categorized insights: warnings, tips, success, info
- Interactive expandable AI explanations
- Confidence scores for each insight

### 3. Visual Analytics

- Interactive Chart.js charts
- Daily, weekly, and monthly views
- Color-coded spending categories
- Responsive design for all devices

### 4. Expense Management

- Complete transaction history
- Search and filter capabilities
- One-click expense deletion
- Real-time updates across all components

## 🌐 Deployment

### Deploy on Vercel (Recommended)

1. **Connect your GitHub repository to Vercel**
2. **Add environment variables in Vercel dashboard**
3. **Deploy automatically on every push to main branch**

## 📎 Useful Links

- **[Neon Database](https://get.neon.com/0pFcBSF)** - Serverless PostgreSQL
- **[Clerk Authentication](https://go.clerk.com/WSe7K8F)** - User management
- **[GitHub Repository](https://github.com/sahandghavidel/next-expense-tracker-ai)** - Source code
- **[Database Diagram](https://app.eraser.io/workspace/XhlJP6Rdmx6nrGR0SpKz?origin=share)** - Visual schema
- **[Next.js Documentation](https://nextjs.org)** - Framework docs
- **[Tailwind CSS](https://tailwindcss.com)** - Styling framework
- **[Vercel Platform](https://vercel.com)** - Deployment platform
