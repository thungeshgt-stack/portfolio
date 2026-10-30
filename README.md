# portfolio
It's just a information of mine in the form of Web Page ....
# Thungesh GT — Portfolio

A multi-page personal portfolio built with plain HTML, CSS and JavaScript. No frameworks, no build step.

**Theme:** royal black, grey and white, with Cinzel headings and Inter body text.

## About

Third-year B.E. Computer Science and Engineering (AI & ML) student at Meenakshi College of Engineering, Chennai, seeking internship and part-time opportunities in software development, Python and web development.

## Pages

| Page | File | Content |
|------|------|---------|
| Home | `index.html` | Photo in a 3D tilt frame, name, quick links |
| About | `about.html` | Education and what I am looking for |
| Skills | `skills.html` | Python Programming, Vibecoding, HTML basics, supporting tools |
| Projects | `projects.html` | PharmaCore, Iron Forge Gym, this portfolio |
| Resume | `resume.html` | CV download |
| Contact | `contact.html` | Phone (tap to call), email, WhatsApp, Instagram, GitHub, LinkedIn |

## Features

- Page-wipe transition between pages
- Scroll-triggered reveal animations
- 3D tilt and light-follow effect on cards and the profile frame
- Letter-by-letter name animation
- Mobile-first layout on an 8px spacing grid
- Respects `prefers-reduced-motion`

## Project structure

```
site/
├── index.html
├── about.html
├── skills.html
├── projects.html
├── resume.html
├── contact.html
├── css/
│   └── style.css      # design tokens, layout, components
├── js/
│   └── main.js        # transitions, reveals, tilt, name animation
└── assets/
    ├── me.jpg         # profile photo
    └── Thungesh_CV.pdf
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to Netlify

1. Go to [app.netlify.com](https://app.netlify.com).
2. Drag the project folder into the deploy area, or connect this repository.
3. Leave the build command empty and set the publish directory to the project root.

## Contact

- Phone: +91 89250 86752
- Email: thungesh019@gmail.com
- GitHub: [thungeshgt-stack](https://github.com/thungeshgt-stack)
- LinkedIn: [in/thungesh](https://www.linkedin.com/in/thungesh)
- Instagram: [@thungesh_gt](https://www.instagram.com/thungesh_gt)
