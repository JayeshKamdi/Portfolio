# Jayesh Kamdi - Portfolio

A personal portfolio website built with **HTML and advanced CSS**, featuring interactive 3D elements and a bento-grid "About Me" section. It introduces who I am, what I'm learning, and the work I do in web development and video editing.

## Overview

I'm a first-year Computer Science Engineering student at Ramdeobaba University (RBU). I have been editing YouTube videos and montages for over three years, and I'm now building my web development skills. This portfolio is a showcase of both sides: clean front-end work and a visual, color-focused design sense.

## Features

- **Hero section** with a bold "WEB DEVELOPER" title, a short bio, and an interactive 3D scene
- **Header links** to Contact (email), GitHub, LinkedIn, and a Google Drive folder of my video edits
- **Bento-grid About section** with four cards:
  > **Intro**: About Me, with an embedded 3D model
  > **Tech Stack**: HTML, CSS, learning C, and DaVinci Resolve
  > **Experience**: YouTube editing, SIH hackathon, technical club interview
  > **Passion**: gaming and vibe coding
- **Gradient backgrounds** on each card for a consistent visual style

## Tech Stack

1. Markup - HTML 5
2. Styling - CSS 3
3. 3D Models - Spline (https://spline.design/) via the "<spline-viewer>" web component 
4. Video editing - DaVinci Resolve 


## Project Structure

Portfolio/
1. .github/workflows/                              # GitHub workflow configuration.
2. index.html                                      # Main page markup.
3. style.css                                       # Styles.
4.  gradient.png                                   # Intro Card background image.
5.  gradient 2.png                                 # Tech Stack card background image.
6.  gradient3&4.png                                # Experience and Passion card background image. 
7.  skills group.png                               # Skills illustration (Tech Stack card).
8.  Smart-Casual 3D Man with Glasses.png           # 3D Model in Intro card.


## Getting Started

No build step or dependencies are required.

1. Clone the repository:
   bash
   git clone https://github.com/JayeshKamdi/Portfolio.git
   cd Portfolio
   
2. Open index.html in your browser, or serve it locally:
   bash
   # Python 3
   python -m http.server 8000
   
   Then visit http://localhost:8000.

> An internet connection is needed for the 3D scenes, which load from Spline's CDN.

## Customization

- **Text and links**: edit the content and the header "<a>" links in "index.html".
- **Look and feel**: adjust colors, layout, and card styles in style.css.
- **3D scenes**: replace the "url" attribute on the "<spline-viewer>" elements with your own Spline scene.
- **Card backgrounds**: swap the gradient images for your own, keeping the same file names or updating the src paths.



## Contact

- **GitHub:** (@JayeshKamdi)(https://github.com/JayeshKamdi)
- **LinkedIn:** (jayeshkamdi)(https://www.linkedin.com/in/jayeshkamdi/)
- **Email:** 2153.jayesh@gmail.com
- **Website:** https://jayeshkamdi.github.io/Portfolio/

---

Designed and built by Jayesh Kamdi.
