# CLAUDE.md - Project Context

## Project Overview
This is a **Next.js Platform Starter** built for deployment on Netlify, showcasing modern web development patterns and Netlify Core Primitives.

**Live Demo:** https://nextjs-platform-starter.netlify.app/

## Tech Stack
- **Framework:** Next.js 15.5.0 (App Router)
- **Styling:** Tailwind CSS 4.0.15 (using PostCSS plugin)
- **Runtime:** React 18.3.1
- **Deployment:** Netlify (requires Next Runtime v5)
- **Package Manager:** Both npm and pnpm supported (pnpm-lock.yaml present)

## Key Dependencies
- **@netlify/blobs** (8.2.0) - Blob storage functionality
- **blobshape** (1.0.0) - Blob shape generation
- **bright** (0.8.5) - Syntax highlighting
- **markdown-to-jsx** (7.4.5) - Markdown rendering
- **unique-names-generator** (4.7.1) - Name generation utility

## Project Structure
```
/
├── app/                    # Next.js App Router pages
│   ├── blobs/             # Blob storage demos
│   ├── classics/          # Classic examples
│   ├── edge/              # Edge function demos
│   ├── image-cdn/         # Image CDN examples
│   ├── quotes/            # API routes
│   ├── revalidation/      # Revalidation examples
│   └── layout.jsx         # Root layout
├── components/            # React components
│   ├── header.jsx         # Navigation header
│   ├── footer.jsx         # Site footer
│   ├── card.jsx           # UI cards
│   ├── alert.jsx          # Alert components
│   └── [other components]
├── styles/                # Global styles
├── public/                # Static assets
├── data/                  # Data files
└── netlify/               # Netlify configuration
```

## Current Customizations
- **Branding:** Changed from "Netlify" to "Warbux" 
- **Logo:** Uses custom Warbux logos (light/dark variants)
- **Modified files:**
  - `app/layout.jsx` - Title template and logo
  - `components/header.jsx` - Navigation and branding

## Development Commands
- **Local dev:** `netlify dev` (preferred) or `npm run dev`
- **Build:** `npm run build`
- **Lint:** `npm run lint`

## Configuration Files
- **next.config.js** - Basic Next.js config with React Strict Mode
- **postcss.config.js** - Tailwind CSS PostCSS plugin
- **netlify.toml** - Netlify deployment config
- **.eslintrc.json** - ESLint configuration
- **.prettierrc** - Code formatting rules

## Features Demonstrated
1. **Blob Storage** - File storage and management
2. **Edge Functions** - Geolocation-based content
3. **Image CDN** - Optimized image delivery
4. **Revalidation** - Cache invalidation patterns
5. **API Routes** - Server-side functionality

## Notes
- Uses Tailwind CSS 4.x (latest major version)
- Configured for Netlify deployment with Core Primitives
- Built with Next.js App Router (modern routing)
- Supports both light and dark Warbux branding assets