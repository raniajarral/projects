# Ontario Window Cleaners - Mockup Landing Page

This is a simple **mockup landing page** designed for a professional window cleaning brand based in Ontario. Built with React, TypeScript, and Tailwind CSS, the page showcases modern design, performance optimization, and responsive UI practices. It is not connected to any backend or live client data—built purely for demonstration and prototyping purposes.

## 🔗 Live Site

[https://onterioclean.netlify.app/](https://onterioclean.netlify.app/)

---

## Features

- **Mobile-First, Responsive Design** — Built with adaptability in mind for seamless viewing across all devices.
- **Modern Visual Identity** — Clean layout, soft shadows, elegant spacing, and high-contrast CTA buttons.
- **Component-Based Architecture** — Scalable and reusable sections developed using modular React components.
- **Interactive UX** — Mobile menu transitions, testimonial carousel, and hover interactions.
- **High Performance** — Vite-powered build system with lazy loading and optimized asset handling.
- **Accessible & SEO-Friendly** — Semantic HTML, ARIA-conscious design, and optimized metadata.

---

## Tech Stack

- **Frontend Framework**: React (18+)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Library**: Shadcn/ui
- **Icons**: Lucide React
- **Bundler**: Vite

---

## Project Structure

```bash
ontario_clean/
├── src/
│   ├── components/                  # Contains all reusable and page-specific React components
│   │   ├── ui/                      # Smaller UI elements like buttons, cards, badges, etc.
│   │   ├── Header.tsx              # Navigation bar with logo and links
│   │   ├── HeroSection.tsx         # Eye-catching intro with CTA; first section users see
│   │   ├── AboutSection.tsx        # Brief overview of the company, vision, and values
│   │   ├── ServicesSection.tsx     # Placeholder for services (can be extended or removed)
│   │   ├── TestimonialsSection.tsx # Client feedback section with quotes and ratings
│   │   ├── ContactSection.tsx      # Contact form and company contact details
│   │   └── Footer.tsx              # Footer with links, legal info, and possibly social icons
│   ├── assets/                     # Static assets such as images, icons, and logos
│   ├── lib/                        # Utility functions, helpers, or service integrations
│   ├── App.tsx                     # Main component that wraps and routes all sections
│   └── main.tsx                    # Entry point that mounts React app to the DOM
├── public/                         # Static files served as-is (like favicon, meta files)
├── index.html                      # HTML template injected by Vite during build
├── package.json                    # Project metadata, scripts, and dependency list
├── tailwind.config.js             # TailwindCSS customization and theme settings
├── tsconfig.json                  # TypeScript compiler settings
└── vite.config.ts                 # Vite build configuration
```


---

## 📦 Component Overview

### 1. `Header`
- A fixed top navigation bar featuring logo, quick links to each section, and a CTA button.
- Includes a mobile hamburger menu for smaller screens with slide-in behavior.

### 2. `HeroSection`
- A strong first impression with a bold heading, tagline, and CTA.
- Contains trust-building elements like “15+ Years of Experience” and “500+ Clients Served”.

### 3. `AboutSection`
- Communicates the professionalism and brand values of the company.
- Includes concise descriptions of the company’s experience, commitment, and service quality.

### 4. `ServicesSection`
- Icon-based cards that showcase key services: Residential, Commercial, High-Rise, Pressure Washing, etc.
- Designed as a responsive grid with hover and focus interactions for user engagement.

### 5. `TestimonialsSection`
- Displays real-user quotes in a clean testimonial format.
- Responsive layout with adaptive grid and swipe-enabled carousel for mobile devices.

### 6. `ContactSection`
- Highlights direct contact details like phone and email.
- Includes a "Request a Quote" form with properly labeled inputs and UX-focused layout.

### 7. `Footer`
- Contains brand logo, navigation links, business contact info, and legal disclaimers.
- Structured for both accessibility and crawlability.
  
---

## 📌 Notes

- This is a **mockup/demo site only**—not a production deployment or live business website.
- It was built as part of a portfolio project to demonstrate UI/UX skills, component-based development, and mobile optimization.

---

**GitHub**: [@raniajarral](https://github.com/raniajarral)  
**Email**: rania.jarral@connectprax.com
