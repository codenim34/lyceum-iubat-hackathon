# IUBAT Hackathon Project

A modern web application built with Next.js, featuring authentication and a comprehensive learning platform.

## Features

- **Authentication**: Secure user authentication powered by Clerk
- **Modern UI**: Built with Tailwind CSS and various UI components
- **Interactive Learning**: Roadmaps and quest-based learning system
- **Dashboard**: User-specific dashboard for tracking progress
- **Admin Panel**: Administrative controls and management
- **API Integration**: RESTful API endpoints for data management

## Project Structure

```
├── app/
│   ├── admin/         # Admin panel components
│   ├── api/          # API routes
│   ├── components/   # Reusable UI components
│   ├── dashboard/    # User dashboard
│   ├── learn/        # Learning platform
│   ├── quests/       # Quest system
│   ├── roadmaps/     # Learning roadmaps
│   └── layout.jsx    # Root layout component
├── lib/             # Utility functions and actions
├── public/          # Static assets
└── components/      # Shared components
```

## Tech Stack

- **Framework**: Next.js 14
- **Authentication**: Clerk
- **Styling**: Tailwind CSS
- **UI Components**: 
  - Radix UI
  - Chakra UI
  - Framer Motion
- **Database**: MongoDB with Mongoose
- **Code Editor**: Monaco Editor
- **Markdown**: React Markdown with GFM
- **Analytics**: Vercel Analytics & Speed Insights

## Getting Started

1. **Clone the repository**
```bash
git clone [repository-url]
```

2. **Install dependencies**
```bash
npm install
```

3. **Set up environment variables**
Create a `.env.local` file with necessary credentials:
- Clerk authentication keys
- MongoDB connection string
- Other API keys

4. **Run the development server**
```bash
npm run dev
```

5. **Build for production**
```bash
npm run build
```

## Environment Variables

Required environment variables:
- `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY`
- `CLERK_SECRET_KEY`
- `MONGODB_URI`
- Other service-specific keys

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run lint` - Run ESLint

## License

This project is licensed under the MIT License.
