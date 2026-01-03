# Adrian Portfolio Template

## Overview
A personal portfolio website template built with HTML, CSS, and JavaScript. Features include animated particles background, smooth scrolling, portfolio gallery with filtering, and responsive design.

## Project Structure
```
/
├── index.html          # Main portfolio page
├── blog.html           # Blog listing page
├── single-blog.html    # Individual blog post page
├── server.py           # Python HTTP server for development
├── mail.php            # Contact form handler (PHP)
├── css/                # Stylesheets
│   ├── style.css       # Main styles
│   ├── bootstrap.css   # Bootstrap framework
│   ├── animate.css     # Animation library
│   └── ...
├── js/                 # JavaScript files
│   ├── main.js         # Main site functionality
│   ├── particles.min.js # Particles background effect
│   ├── jquery.min.js   # jQuery library
│   └── ...
├── images/             # Image assets
│   ├── logo/           # Logo images
│   ├── portfolio/      # Portfolio items
│   ├── blog/           # Blog images
│   └── background/     # Background images
└── fonts/              # Font files (Font Awesome)
```

## Running the Project
The site is served using a Python HTTP server on port 5000:
```
python server.py
```

## Deployment
This is a static site that can be deployed as static files. The `index.html` serves as the entry point.

## Recent Changes
- 2026-01-03: Initial setup for Replit environment
  - Added Python HTTP server with cache control headers
  - Renamed index-particles.html to index.html
  - Created .gitignore for Python
