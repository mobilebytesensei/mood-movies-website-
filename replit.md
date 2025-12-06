# Mood Movies Landing Page

## Overview
A responsive landing page for "Mood Movies" - an AI-powered movie recommendation app that matches films to users' emotional states. The page showcases the app's features, how it works, and user testimonials.

## Project Type
Static HTML/CSS/JavaScript website (no backend, no build process)

## Tech Stack
- **Frontend**: Pure HTML5, CSS3 (Tailwind CSS), JavaScript
- **Libraries**: 
  - Tailwind CSS (utility-first CSS framework)
  - Swiper.js (for testimonial carousel)
  - Jarallax (for parallax effects)
  - Lucide Icons (icon library)
  - Gumshoe (smooth scroll navigation)
  - Preline UI (UI components)

## Project Structure
```
.
├── index.html          # Main landing page
├── css/                # Stylesheets
│   ├── style.css       # Main styles
│   ├── icons.min.css   # Icon styles
│   ├── jarallax.min.css
│   └── swiper-bundle.min.css
├── js/                 # JavaScript files
│   ├── app.js          # Main application logic
│   ├── lucide.min.js   # Icons
│   ├── jarallax.min.js # Parallax effects
│   ├── swiper-bundle.min.js # Carousel
│   ├── swiper.js
│   ├── gumshoe.polyfills.min.js # Smooth scroll
│   └── preline.js      # UI components
├── images/             # Image assets
└── fonts/              # Web fonts
```

## Running the Project
The site is served using a Python HTTP server on port 5000:
```bash
python server.py
```

The server includes cache-busting headers to ensure changes are visible immediately.

## Deployment
Configured for static deployment on Replit. The site is production-ready as-is.

## Features Showcased
- Mood-based movie recommendations
- AI-powered matching engine
- Surprise Me mode
- Mood tracking
- Personalized watch lists
- Multiple mood categories (Happy, Sad, Lonely, Inspired, Heartbroken, etc.)

## Recent Changes
- **Dec 6, 2024**: Initial project import and Replit environment setup
  - Created Python server for static file serving
  - Configured workflow for port 5000
  - Set up deployment configuration
  - Added .gitignore for Python environment
