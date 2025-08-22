# Central Automations Website - Vercel Deployment

This directory contains a frontend-only version of the Central Automations website, ready for deployment on Vercel.

## Features

- **Modern React Application** - Built with Vite, TypeScript, and Tailwind CSS
- **Responsive Design** - Mobile-first approach with desktop optimization
- **Calendly Integration** - Embedded scheduling for discovery calls
- **Clean UI Components** - Using Shadcn/ui and Radix UI primitives
- **Professional Landing Page** - Optimized for B2B lead generation

## Quick Deployment to Vercel

### Option 1: Vercel CLI (Recommended)
1. Install Vercel CLI: `npm i -g vercel`
2. From this directory, run: `vercel`
3. Follow the prompts to deploy

### Option 2: Vercel Dashboard
1. Push this directory to a Git repository
2. Connect your repository to Vercel
3. Vercel will automatically detect it as a Vite project

## Local Development

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start development server:
   ```bash
   npm run dev
   ```

3. Build for production:
   ```bash
   npm run build
   ```

## Project Structure

```
vercel-deploy/
├── src/
│   ├── components/     # React components
│   ├── pages/         # Page components
│   ├── hooks/         # Custom React hooks
│   └── lib/           # Utility functions
├── attached_assets/   # Static assets
├── index.html         # Main HTML file
├── package.json       # Dependencies and scripts
├── vite.config.ts     # Vite configuration
└── tailwind.config.ts # Tailwind CSS configuration
```

## Environment Variables

No environment variables are required for this frontend-only deployment.

## Domain Configuration

After deployment, you can configure a custom domain in your Vercel dashboard.

## Support

For any issues with the deployment, refer to the [Vercel documentation](https://vercel.com/docs).