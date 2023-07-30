## Steps

<ol>
<li> Start the template with

`npm create vite@latest ./ -- --template react` </li>
<li> Install dependencies:</li>
<ul>
<li>TailwindCSS config:

`npm install -D tailwindcss`
`npx tailwindcss init`
</li>
<li>
Install three fiber (create 3D JS code), drei, maath (calculation), tilt (cool animation), vertical timeline component (experience), framer motion, and react router dom (for routing)

`npm install --legacy-peer-deps @react-three/fiber @react-three/drei maath react-tilt react-vertical-timeline-component @emailjs/browser framer-motion react-router-dom`
</li>
</ul>
</br>
<li> File structure: </li>
<ul>
<li>Public file is inclusive of a 3D desktop pc, a 3d texture and a logo</li>
<li> Src file is inclusive of </li>
<ul>
<li>Assets: project's images. There will be a index.js file that export the image variables for easier reference when needed.
</li>
<li>Components: 1 canvas folder component for drawing, About + Contact for contact info., Experience + Feedbacks + Tech + Works for the job experience, Hero + Loader + Navbar for the landing page</li>
<li>The important components that run the app, including App.css, App.jsx, index.css, main.jsx </li>
</ul>
</ul>
</ol>

## Notes

- If Tailwind CSS style doesn't work with your Vite, you should add
`npm install --legacy-peer-deps -D tailwindcss postcss autoprefixer`
Then `npx tailwindcss init -p`
You can read more about TailwindCSS config for Vite [here](https://tailwindcss.com/docs/guides/vite)
</br>

- About React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.
Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Credit:
This project wouldn't be done without the help of JS Mastery.