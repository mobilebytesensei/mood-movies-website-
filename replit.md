# Mood Movies Landing Page

## Overview
A premium, cinematic landing page for "Mood Movies" - an AI-powered movie recommendation app that matches films to users' emotional states. The design follows Apple-meets-Netflix-meets-Letterboxd aesthetics with a dark navy theme and soft, premium color accents.

## Project Type
Static HTML/CSS/JavaScript website (no backend, no build process)

## Tech Stack
- **Frontend**: Pure HTML5, CSS3 (custom premium design), Vanilla JavaScript
- **Design System**: Custom CSS with CSS variables for premium color palette
- **Fonts**: Inter (Google Fonts)

## Design System

### Color Palette
- **Navy Dark**: #0a0e1a (primary background)
- **Navy**: #0f1629 (section backgrounds)
- **Lavender**: #a78bfa (primary accent)
- **Teal**: #5eead4 (feature accent)
- **Pink**: #f9a8d4 (mood accent)
- **Orange**: #fdba74 (step accent)
- **Purple**: #c4b5fd (secondary accent)

### Design Principles
- Premium, muted colors (no neon, no oversaturation)
- Cinematic gradients and subtle glows
- Film-grain texture effects
- Soft ambient lighting effects
- Apple-like minimal hero, more cinematic inner sections

## Project Structure
```
.
├── index.html          # Main landing page
├── server.py           # Python HTTP server for development
├── css/
│   ├── premium.css     # Premium cinematic styles (primary)
│   ├── style.css       # Legacy Tailwind styles (unused)
│   └── ...            # Other CSS dependencies
├── js/                 # JavaScript files
├── images/             # Image assets
└── fonts/              # Web fonts
```

## Sections
1. **Hero** - Clean, minimal, Apple-like with dark navy gradient
2. **How It Works** - 4 steps with entertainment-inspired accent colors
3. **Features** - Gradient cards with glowing icons
4. **Explore by Mood** - Color-coded mood grid (12 moods)
5. **Testimonials** - Cinematic background with user stories
6. **Footer** - Minimal with soft gradient border

## Running the Project
```bash
python server.py
```
Server runs on port 5000 with cache-busting headers.

## Deployment
Configured for static deployment on Replit (public_dir: .)

## Recent Changes
- **Dec 6, 2024**: Complete premium redesign
  - New cinematic CSS with premium color palette
  - Redesigned all sections with Apple/Netflix/Letterboxd aesthetics
  - Added gradient cards and glowing icons to Features section
  - Color-coded mood exploration grid
  - Testimonials with bokeh-style background effects
  - Classic minimal footer with gradient border

## User Preferences
- Premium, sophisticated design aesthetic
- No neon or oversaturated colors
- Cinematic but classy visual effects
- Mobile-responsive design
