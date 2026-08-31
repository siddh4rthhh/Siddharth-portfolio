# Siddharth Singh — Portfolio 

A responsive personal portfolio website built with **pure HTML & CSS** (no frameworks, no JavaScript) as part of the Web Development — Task 1 assignment.


---

##  Overview

The site is designed around a "developer console" theme — dark navy background, gold accent, monospace labels styled like code comments, and a hero section built to look like a terminal. Motion is done entirely in CSS: a typing-cursor effect in the hero, staggered fade-ins, animated skill bars, and hover/scroll interactions.

##  Sections

- **Home** — intro, role, and a terminal-style animated snippet
- **About Me** — bio, quick facts
- **Skills** — categorized skills with animated progress bars
- **Projects** — project cards with tags and links
- **Education** — a vertical timeline of schooling/coursework
- **Contact** — email and social links styled as terminal commands

##  Project structure


portfolio/
├── index.html      
├── style.css        
├── assets/         
└── README.md

##  Customize it

Before submitting, replace the placeholder content with your own:

| What to change | Where |
|---|---|
| Name, role, bio | `index.html` — Hero & About sections |
| Profile photo | Add an image to `assets/`, then swap the `.about-photo` placeholder for an `<img>` tag |
| Skills & percentages | `index.html` — Skills section (`width: XX%` on each `.skill-fill`) |
| Projects, links, screenshots | `index.html` — Projects section |
| School/college name | `index.html` — Education timeline |
| Email, GitHub, LinkedIn | `index.html` — Contact section |
| Colors/fonts | `style.css` — `:root` variables at the top of the file |

##  Responsive

Tested breakpoints at 1024px (tablet) and 720px (mobile), with a CSS-only hamburger menu (via a hidden checkbox — no JavaScript needed) for small screens.

##  Built with

- HTML5 (semantic markup)
- CSS3 (Grid, Flexbox, custom properties, keyframe animations)
- Google Fonts: Fraunces, Inter, JetBrains Mono

##  License

Personal project — feel free to fork and adapt for your own portfolio.

##  Deployed via Netlify:

https://flourishing-melomakarona-a12d61.netlify.app/ 

---

**Author:** Siddharth Singh, Web Development
