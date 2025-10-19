# Portfolio - Karina Vitória

## Overview
This is a personal portfolio website for Karina Vitória, a Front-End Developer. The site showcases her projects, skills, and professional information in Portuguese (Brazilian).

## Project Structure
- **index.html** - Main portfolio page with introduction, projects section, and contact information
- **currículo.html** - Resume/CV page with detailed professional and educational information
- **_css/** - Stylesheets directory
  - style.css - Main styling for the portfolio
  - currículo.css - Styling for the resume page
- **_javascript/** - JavaScript files directory
  - function.js - Portfolio functionality (placeholder for future features)
- **_imagens/** - Images and assets directory
  - Favicon/ - Website icons
  - logotipo/ - Logo images
  - perfil/ - Profile photos
  - redes-sociais/ - Social media icons
- **server.js** - Express server to serve the static website
- **package.json** - Node.js dependencies and scripts

## Recent Changes
- **2025-10-19**: Initial Replit setup
  - Created Express server configuration for static file serving
  - Fixed JavaScript syntax errors in function.js
  - Configured workflow to run on port 5000
  - Set up deployment configuration for autoscale
  - Added cache control headers to prevent browser caching issues

## Technology Stack
- HTML5
- CSS3
- JavaScript (basic)
- Bootstrap 5 (via CDN)
- Express.js (for serving static files)
- Node.js

## Development
The site runs on an Express server that serves static files and binds to `0.0.0.0:5000` for Replit compatibility.

### Running Locally
```bash
npm start
```

The server includes cache-control headers to ensure changes are immediately visible during development.

## Deployment
The project is configured for Replit's autoscale deployment, which is suitable for this static portfolio website.
