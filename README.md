# 🚀 Tier-Based Event Showcase

A Next.js application that displays events based on user membership tiers using Clerk.dev for authentication and Supabase for data storage.

## 🛠️ Tech Stack

- **Frontend**: Next.js 14 (App Router)
- **Authentication**: Clerk.dev
- **Database**: Supabase (PostgreSQL)
- **Styling**: Tailwind CSS

## 🏃‍♂️ Quick Start

1. Clone the repository
2. Install dependencies: `npm install`
3. Copy `.env.example` to `.env.local` and add your keys
4. Run development server: `npm run dev`
5. Open [http://localhost:3000](http://localhost:3000)

## 🔑 Environment Variables

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
