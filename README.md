# Arena Agent Dashboard

A modern React/TypeScript dashboard for managing arena agents. Built with Vite and deployed on Vercel.

## Features

- **Modern UI**: Beautiful, responsive design
- **Agent Management**: Configure and monitor agents
- **Usage Tracking**: Monitor agent usage and limits
- **Purchase Flow**: Integrated payment processing
- **Profile Management**: User profiles and settings

## Tech Stack

- **React** with TypeScript
- **Vite** for fast development
- **Supabase** for backend
- **Vercel** for deployment

## Quick Start

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build
```

## Project Structure

```
arena agent bot/
├── src/
│   ├── components/       # React components
│   │   ├── AdminPanel.tsx
│   │   ├── UsageCenter.tsx
│   │   ├── PurchaseFlow.tsx
│   │   ├── ProfileCenter.tsx
│   │   ├── PricingPlans.tsx
│   │   ├── PaymentProcessing.tsx
│   │   ├── DeviceConfiguration.tsx
│   │   ├── BrandIntro.tsx
│   │   ├── ApiKeySettings.tsx
│   │   ├── AccountPreferences.tsx
│   │   ├── AboutArena.tsx
│   │   └── WaitingArcade.tsx
│   ├── pages/            # Page components
│   ├── lib/              # Utilities
│   │   └── supabase.ts   # Supabase client
│   ├── *.css             # Stylesheets
│   ├── main.tsx          # Entry point
│   └── App.tsx           # Main app
├── package.json
├── vite.config.ts
├── tsconfig.json
└── vercel.json
```

## Environment Variables

Create a `.env` file:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## Deployment

This project is configured for Vercel deployment. Just push to your repository and Vercel will automatically deploy.

## License

MIT
