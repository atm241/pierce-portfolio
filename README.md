# Pierce Gruidl — Portfolio

A personal developer portfolio built with React and Vite, featuring 3D graphics,
animated sections, and a contact form. It includes an About section, an
interactive 3D hero scene, a tech stack showcase, a work-experience timeline,
project highlights, and an email contact form.

## Tech Stack

- **React 18** + **Vite** — UI and build tooling
- **Tailwind CSS** — styling
- **Three.js** via **@react-three/fiber** and **@react-three/drei** — 3D scenes
- **Framer Motion** — animations
- **react-vertical-timeline-component** — work-experience timeline
- **EmailJS** (`@emailjs/browser`) — contact form delivery
- **react-router-dom** — routing

## Getting Started

```bash
# Install dependencies
npm install

# Start the dev server (http://localhost:5173)
npm run dev

# Create a production build
npm run build

# Preview the production build locally
npm run preview
```

## Contact Form Setup

The contact form uses [EmailJS](https://www.emailjs.com/). To enable it, supply
your own EmailJS service ID, template ID, and public key in
`src/components/Contact.jsx`.

## Project Structure

```
src/
├── assets/        # Images, logos, and company/tech icons
├── components/    # Section components (Hero, About, Experience, Works, Contact, ...)
│   └── canvas/    # Three.js scenes (Computers, Earth, Stars, Ball)
├── constants/     # Site content (experiences, projects, technologies, ...)
├── hoc/           # Section wrapper higher-order component
├── utils/         # Animation helpers
├── styles.js      # Shared style tokens
└── App.jsx        # App entry / layout
```

## License

Personal project. Company logos and trademarks referenced in the experience
section belong to their respective owners.
