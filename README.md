# AAA Unity Game Developer Portfolio // Brine Sebastian Das

A premium, interactive, AAA-game-inspired portfolio website designed and developed for professional Unity Game Developer **Brine Sebastian Das**. 

The portal captures the visual aesthetic of elite studio web designs (Riot Games, Unreal Engine, Rockstar, CD Projekt Red) utilizing a glowing cyberpunk color palette, floating particle networks, glassmorphic HUD panel layers, custom shaders, and physics-driven particle matrices.

---

## 🕹️ Tech Stack
- **Framework**: React 18 & Vite
- **Language**: TypeScript
- **Styling**: Tailwind CSS & Vanilla CSS custom modules
- **3D Graphics & Shaders**: Three.js, React Three Fiber (R3F), Drei
- **Motion & Interaction**: Framer Motion & GSAP
- **Smooth Scroll**: Lenis Scroll Engine
- **Icons**: Lucide Icons
- **Effects**: Canvas Confetti (form completion feedback)

---

## 📂 Project Organization
```
c:\Users\ASUS\Downloads\Brine
├── public/                  # Core static assets
├── src/
│   ├── components/          # Interactive UI components
│   │   ├── Background3D.tsx # React Three Fiber 3D wave and stars canvas
│   │   ├── CustomCursor.tsx # Glowing trailing cursor component
│   │   └── LoadingScreen.tsx# Gaming-console style loader panel
│   ├── hooks/               # Custom lifecycle hooks
│   │   ├── useMousePosition.ts
│   │   └── useWindowSize.ts
│   ├── sections/            # Core page sections
│   │   ├── Hero.tsx         # Responsive headline & console widget CTAs
│   │   ├── About.tsx        # Milestone timeline & stats trackers
│   │   ├── TechStack.tsx    # Armament skill filter dashboard
│   │   ├── Projects.tsx     # Mission catalog & details overlays
│   │   ├── GameShowcase.tsx # Cinematic slider stat dashboards
│   │   ├── Experience.tsx   # Professional timelines and logs
│   │   ├── Testimonials.tsx # Studio reviews slider
│   │   ├── Contact.tsx      # Dispatch form, validations & confetti
│   │   └── Footer.tsx       # Copyright tags & scroll hooks
│   ├── styles/
│   │   └── index.css        # Cyber gridlines, scanlines & neon glows
│   ├── App.tsx              # Main system wire-up & Lenis initialization
│   ├── main.tsx             # DOM binder entry
│   └── vite-env.d.ts
├── package.json             # Engine script and version bindings
├── vite.config.ts           # Vite compile parameters (GitHub Pages compatible base)
├── tailwind.config.js       # Cyberpunk theme details
├── postcss.config.js        # Postprocessing CSS plugins
├── tsconfig.json            # Strict type settings
├── .eslintrc.cjs            # Linting constraints
└── .prettierrc              # Formatting configurations
```

---

## ⚡ Execution Guidelines

### 1. Install System Dependencies
Ensure you have Node.js and npm installed. Run inside the project directory:
```bash
npm install
```

### 2. Launch Local Dev Node
To start the hot-reloading development server on port 3000:
```bash
npm run dev
```

### 3. Compile Production Bundle
To compile and optimize assets into the static `dist/` directory for deployment:
```bash
npm run build
```

### 4. Local Build Preview
To preview the compiled static production build locally:
```bash
npm run preview
```

---

## 🚀 GitHub Pages Deployments
This repository is configured out-of-the-box to compile static files using relative paths (`base: './'`), meaning it can be built and pushed directly to any branch (e.g., `gh-pages` or `/docs`) and it will run immediately without asset linking issues.
