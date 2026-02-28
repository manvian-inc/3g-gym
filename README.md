# 3G Gym - Fitness Website sample

A modern, responsive fitness/gym website built with Next.js 16, TypeScript, and Tailwind CSS.

## Features

- 🏋️ **Hero Section** - Eye-catching landing section with call-to-action
- 📖 **About Section** - Showcase gym philosophy and offerings
- 💪 **Programs Section** - Display various fitness programs
- 📊 **Results Section** - Before/after transformation showcases
- 💬 **Testimonials** - Customer success stories
- 💰 **Pricing Plans** - Multiple pricing tiers (Monthly, Personal Training, Diet Plans)
- 🎯 **Call-to-Action** - Final conversion section
- 📱 **Responsive Design** - Mobile-first, works on all devices
- 🎨 **Modern UI** - Dark theme with vibrant red/maroon accents

## Getting Started

### Prerequisites

- Node.js 18+ installed
- npm or yarn package manager

### Installation

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

## Project Structure

```
3g_gym/
├── app/
│   ├── globals.css          # Global styles and Tailwind config
│   ├── layout.tsx           # Root layout
│   └── page.tsx             # Main page (homepage)
├── components/
│   ├── header/              # Navigation header
│   ├── hero/                # Hero section
│   ├── about/               # About section
│   ├── programs/            # Programs showcase
│   ├── results/             # Before/after results
│   ├── testimonials/        # Customer testimonials
│   ├── pricing/             # Pricing plans
│   ├── cta/                 # Call-to-action section
│   └── footer/              # Footer with links
└── public/                  # Static assets (images, etc.)
```

## Customization

### Adding Images

Replace the placeholder image divs in components with actual images:

1. Add your images to the `public/` directory
2. Import and use Next.js `Image` component:
```tsx
import Image from 'next/image';

<Image
  src="/your-image.jpg"
  alt="Description"
  width={800}
  height={600}
  className="rounded-lg"
/>
```

### Color Scheme

The design uses:
- **Primary Red**: `#8B0000` (deep red/maroon)
- **Accent Purple**: `#A020F0` (for gradients)
- **Dark Background**: `#000000` and `#1a1a1a`
- **White**: `#FFFFFF` for text and backgrounds

### Updating Content

Each component is self-contained. Edit the component files in `components/` to update:
- Text content
- Pricing information
- Program details
- Links and navigation

## Build for Production

```bash
npm run build
npm start
```

## Technologies Used

- **Next.js 16** - React framework
- **TypeScript** - Type safety
- **Tailwind CSS 4** - Utility-first CSS
- **React 19** - UI library

## Notes

- All image placeholders should be replaced with actual fitness/gym photos
- Update contact information in the Footer component
- Customize pricing plans according to your needs
- Add your actual social media links in the Footer

## License

This project is created for 3G Gym.
