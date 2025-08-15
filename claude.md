# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website project for Danfe Hotel & Restaurant, a 20-bed establishment located in Chame, Manang, on the Annapurna trekking route in Nepal. The website consists of 2-3 static pages showcasing hotel services, amenities, and contact information.

## Development Commands

Since this is a static HTML/CSS/JS website, development is straightforward:

- **Local development**: Open HTML files directly in browser or use a local server:
  - `python -m http.server 8000` (Python 3)
  - `python -m SimpleHTTPServer 8000` (Python 2)
  - Use VS Code Live Server extension
- **Validation**: Use W3C validators for HTML/CSS validation
- **Deployment**: Ready for static hosting (GitHub Pages, Netlify, Vercel)

## Architecture & Structure

### Planned Site Structure
- **3 main pages**: Home/Services, About, Contact
- **Static assets**: HTML, CSS, JavaScript (optional), images
- **Responsive design**: Mobile-first approach
- **Navigation**: Consistent header/footer across all pages

### Key Requirements
- **Hotel name**: Danfe Hotel & Restaurant
- **Location**: Chame, Manang, Annapurna trekking route
- **Services**: Breakfast, lunch, dinner included
- **Amenities**: Hot shower, fireplace, WiFi
- **Target**: Professional, attractive, simple design for trekkers

### Content Guidelines
- Highlight the hotel's location advantage on the Annapurna circuit
- Emphasize services important to trekkers (hot meals, hot shower, WiFi)
- Use placeholder images initially, replace with actual hotel photos later
- Include contact form or contact details for bookings
- Optional: Map embed showing location in Chame

## Design Inspiration
Research similar small hotel/restaurant websites in Nepal or mountain destinations for design patterns and content organization suitable for trekking clientele.
