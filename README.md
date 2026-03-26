Purushotham Portfolio Website

A Neo-Brutalist personal portfolio website built using HTML, CSS, and JavaScript.

This project focuses on creative UI design, experimental layouts, and interactive elements without using frameworks or build tools. Everything is written using pure front-end technologies to keep the project lightweight and fast.

This portfolio represents my personal playground for experimenting with web design, animations, and interactive UI ideas.

Live Website: (Add your website link here)

About the Design

This website follows the Neo-Brutalist design style, a bold and expressive UI trend inspired by brutalist architecture.

Instead of polished and minimal interfaces, neo-brutalism focuses on:

Strong visible borders
High-contrast color palettes
Flat offset shadows
Exposed layout structures
Creative imperfections

The goal is to create a bold, creative, and visually striking interface.

Design System
Color Palette

The project uses CSS variables for easy color management.

Color	Variable	Usage
Yellow	--yellow	Primary accent
Cyan	--cyan	Code and highlight elements
Pink	--pink	Secondary accents
Green	--green	Success and highlight states
Black	--border	Borders and text
Typography

Fonts used in the portfolio:

Space Grotesk – Headings and body text
Space Mono – Code blocks and terminal elements
Caveat – Handwritten notes and highlights

These fonts help create a modern yet creative visual style.

UI Features
Paper Tear Section Divider

Sections are separated using torn paper SVG dividers that animate during scrolling.

Book Flip Timeline

The journey section includes a book-style flip animation that reveals the timeline.

Scroll Highlight Animation

Highlighted text appears as if a marker pen is drawing across the text while scrolling.

Interactive Map

A Leaflet.js interactive map shows different locations connected to the timeline.

Matrix Typing Effect

The hero section greeting uses a scramble typing animation before revealing the final text.

Decorative Falling Icons

Icons around the hero image fall with gravity animation when the page scroll begins.

Terminal Mode

The website also includes an interactive terminal-style resume page.

Open:

/terminal.html

Features include:

Command-based navigation
Multiple color themes
Terminal split panels
Command history support
Built-in Snake game

Example command:

help
Project Structure
.
├── index.html
├── styles.css
├── terminal.html
├── script.js
├── favicon.svg
├── images/
│   ├── avatar
│   ├── icons
│   └── assets
├── CNAME
├── robots.txt
├── sitemap.xml
└── README.md
Technologies Used
HTML
CSS
JavaScript
Leaflet.js
p5.js
Font Awesome
Google Fonts

No frameworks or build tools were used.
Everything is built using vanilla web technologies.

Run Locally

You can run this project using any static server.

Using Node
npx serve .
Using Python
python3 -m http.server 8000

Then open:

http://localhost:8000
Author

Purushotham

Frontend Developer | Web Designer | UI Experimenter

This portfolio showcases my web development skills, creative UI experiments, and interactive design ideas.

License

This project is created as a personal portfolio project.

You may view the source code for learning purposes, but please do not copy or redistribute without permission.
