# Mashhood Ahmed – Portfolio

A responsive, single-page personal portfolio for **Mashhood Ahmed**, an AI Engineer and Full-Stack Developer. It presents his background, skills, selected projects and contact details.

## Features

- Fixed, translucent navbar with smooth scrolling between sections
- Hero section with a shaped portrait frame and call-to-action
- About and Education sections
- Skills cards (AI engineering, agent workflows, full-stack) with tech badges and progress bars
- Project cards with hover effects and "ask about this project" email links
- Contact section with a message form, plus footer links (GitHub, email)
- Fully responsive down to mobile

## Tech Stack

- HTML5 and CSS3 (custom properties, gradients, grid/flexbox)
- [Bootstrap 5.3.8](https://getbootstrap.com/) via CDN
- No build step and no dependencies to install

## Project Structure

```
.
├── index.html     # The entire site (markup + styles)
├── profile.jpeg   # Portrait shown in the hero (add your own)
└── README.md
```

## Getting Started

1. Clone the repository.
2. Place a portrait image named `profile.jpeg` next to `index.html`.
3. Open `index.html` in a browser, or serve it locally:

   ```bash
   python3 -m http.server 8000
   ```

   Then visit <http://localhost:8000>.

## Customising

- Colours are defined as CSS variables at the top of the `<style>` block (`--navy`, `--aqua`, `--orange`, ...).
- Edit skill percentages via the `width` style on each `.progress-bar`.
- Project images are Unsplash URLs set in the `.project-one/two/three` classes.

## Known Limitations

- The contact form has no backend yet; wiring it to a service such as Formspree or EmailJS would make it functional.

## Contact

- Email: qsahb688@gmail.com
- GitHub: [Mashhood1488](https://github.com/Mashhood1488)
