# DevPeaks

DevPeaks is a premium digital agency website built with Next.js, React, and Tailwind CSS. The site presents the agency’s services, featured work, process, team story, and contact experience in a polished marketing-site format with motion-driven sections and a dark visual system.

Live site: [https://devpeaksolutions.vercel.app/](https://devpeaksolutions.vercel.app/)

## Overview

The project is structured as a modern multi-page agency website with:

- An animated homepage hero and supporting sections
- Dedicated pages for Services, Projects, Process, About, and Contact
- A responsive navigation bar and footer
- Contact form handling powered by EmailJS
- Reusable UI components for cards, buttons, inputs, containers, badges, and project visuals

## Tech Stack

- Next.js 16
- React 19
- TypeScript
- Tailwind CSS
- Framer Motion
- Lucide React
- EmailJS

## Main Pages

- `/` - Homepage with hero, value proposition, featured work, services overview, why-us content, reviews, CTA, and FAQ sections
- `/services` - Full services listing with detailed feature sets
- `/projects` - Filterable portfolio grid
- `/process` - Step-by-step delivery workflow
- `/about` - Company background, mission, vision, and culture
- `/contact` - Contact form plus email, WhatsApp, and phone details

## Project Structure

- `app/` - App Router pages, layout, metadata, and global styles
- `components/layout/` - Shared navigation and footer
- `components/sections/` - Homepage sections such as hero, services, featured work, reviews, FAQ, and CTA
- `components/ui/` - Reusable UI building blocks
- `lib/` - Utility helpers
- `public/images/` - Static assets used across the site

## Getting Started

### Prerequisites

- Node.js 18+ recommended
- npm

### Install dependencies

```bash
npm install
```

### Run the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build for production

```bash
npm run build
```

### Start the production server

```bash
npm run start
```

## Available Scripts

- `npm run dev` - Start the local development server
- `npm run build` - Create a production build
- `npm run start` - Run the production server
- `npm run lint` - Run Next.js linting

## Contact Form Notes

The contact page uses EmailJS for form submission. The current implementation contains the service, template, and public key values in the component source, so if you plan to reuse the project, update those values with your own EmailJS configuration.

## Deployment

The site is deployed on Vercel and available here:

[https://devpeaksolutions.vercel.app/](https://devpeaksolutions.vercel.app/)

## License

This project is currently licensed under ISC as defined in `package.json`.