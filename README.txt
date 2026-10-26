========================================================================
EGALA NAIDU - PERSONAL PORTFOLIO WEBSITE
Semantic HTML5 & Pure CSS3 (Zero JavaScript / Zero External Assets)
========================================================================

PROJECT OVERVIEW
----------------
This is the personal portfolio website for Egala Naidu, Computer Science and 
Engineering student and aspiring Software Developer / AI-ML Engineer.
The project is built entirely with semantic HTML5 and clean CSS3, incorporating 
CSS 3D perspective effects, layered transformations, accessible interactions, 
and responsive layouts without any JavaScript, external libraries, or CDN assets.


HOW TO OPEN THE PORTFOLIO
-------------------------
1. Direct Browser Opening (No server needed):
   - Locate "index.html" in the project directory.
   - Double-click "index.html" to open it in your default web browser (Chrome, 
     Edge, Firefox, Safari, etc.).
   - Alternatively, right-click "index.html", select "Open with", and choose 
     your browser of choice.

2. Using a Local Static Server (Optional):
   - Open PowerShell or Terminal in the portfolio folder.
   - Run Python's built-in HTTP server:
       python -m http.server 8000
   - Open your browser and navigate to:
       http://localhost:8000


HOW TO EDIT AND CUSTOMIZE CONTENT
---------------------------------
All content and styles are separated cleanly into two core files:

1. Editing Content ("index.html"):
   - Open "index.html" in VS Code, Notepad, or any code editor.
   - Header & Navigation:
     Modify navigation links in the <header> <nav> section.
   - Hero Section (<section id="home">):
     Edit the greeting, name, headline, short intro, or call-to-action buttons.
   - About & Education (<section id="about">):
     Update the bio text or degree details (institution, expected year, CGPA).
   - Skills (<section id="skills">):
     Add, modify, or reorder technical skills inside the <li class="skill-chip"> 
     elements.
   - Projects (<section id="projects">):
     Update project descriptions, tech stack pills, or benchmark metrics in 
     the project cards.
   - Certifications (<section id="certifications">):
     Add or edit certification titles, issuing organizations, dates, and descriptions.
   - Contact (<section id="contact">):
     Update your email address or LinkedIn URL in the respective <a> cards.
   - Footer:
     Update the copyright year or footer metadata.

2. Customizing Styling and Visuals ("style.css"):
   - Open "style.css".
   - Theme Colors & Accents:
     Modify the CSS variables at the top of the file under ":root":
       --bg-deep: Primary background color
       --accent: Electric cyan accent (#00f0ff)
       --accent-secondary: Indigo accent (#6366f1)
       --text-primary: High-contrast text color (#f8fafc)
   - 3D Transforms & Perspective:
     Adjust perspective depth (--container-max, perspective, translateZ values)
     or tweak animation durations in the @keyframes section.
   - Responsive Adjustments:
     Review media queries at the bottom of "style.css" for tablet (1024px), 
     mobile (768px), and small mobile (480px) breakpoints.


ACCESSIBILITY & MOTION FEATURES
-------------------------------
- Full keyboard navigation: Press Tab / Shift+Tab to navigate through links and 
  interactive cards; press Enter to activate.
- Skip link: An accessible skip link is positioned at the top of the page for 
  instant jumping to main content.
- Reduced motion: Users with system setting "prefers-reduced-motion: reduce" 
  will automatically see static 3D layouts without rotation animations.
