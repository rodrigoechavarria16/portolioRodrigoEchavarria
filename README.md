# 🤖 Rodrigo Echavarría Moreno — Portfolio

**Mechatronics Engineer · Tec de Monterrey**
**Live site:** `https://ItsRodri6666.github.io/portolioRodrigoEchavarria`

---

## 👤 About me

I am a Mechatronics Engineer graduated from Tecnológico de Monterrey (CCM campus), specializing in the design and implementation of intelligent systems at the intersection of hardware, software, automation, and cybersecurity. Currently working as a **Cybersecurity Advocate at Honeywell HTCS**, where I ensure Secure Software Development Lifecycle (SSDLC) compliance across product releases.

My background spans digital twin development, robotics, industrial automation, and cloud platforms — with academic projects delivered in collaboration with **Siemens Digital Industries Software** and **Ford Motor Company**.

---

## 🗂️ Repository structure

```
portolioRodrigoEchavarria/
│
├── GitHubPortfolio.html        ← Main portfolio (single-file, self-contained)
├── README.md                   ← This file
│
└── MediaFiles/                 ← All images and videos used in the portfolio
    ├── Honeywell.jpg           → Experience: Honeywell HTCS
    ├── DashboardDigitaltwin.png → Experience & Projects: Siemens Digital Twin
    ├── HMI_Digitaltwin.png     → Experience & Projects: Ford / Siemens HMI
    ├── Object_detection.png    → Project: Pick-and-Place Robot
    ├── AGV.jpg                 → Project: AGV Unloading Station (photo)
    ├── AGV_Demo.mp4            → Project: AGV Unloading Station (demo video)
    ├── RowingMachine.jpg       → Project: Air Rowing Machine (photo)
    ├── RowM_Demo.mp4           → Project: Air Rowing Machine (demo video)
    └── SAIA.jpg                → Project: Electratón CCM & SAIA
```

---

## 🚀 Features

| Feature | Description |
|---|---|
| **Multi-brand design** | Visual language combining Apple (clean, airy), Google Material (colorful chips), Microsoft Fluent (structured cards, pivot tabs), and Siemens (teal accents, engineering grid) |
| **Dark / Light mode** | Toggle button (☽/☀) in the nav bar. Preference saved in `localStorage`. Respects OS setting on first visit |
| **3D skill sphere** | Interactive Three.js globe — drag, scroll to zoom, hover to inspect, click to filter by category |
| **Experience pivot tabs** | Microsoft-style tab strip: filter between All · Industry · Academic |
| **Scroll reveal animations** | Sections animate in as you scroll using `IntersectionObserver` — no library required |
| **Lightbox** | Click any project image to open full-screen. Press `Esc` or click outside to close |
| **Embedded media** | Local images and MP4 videos served directly from `MediaFiles/` |
| **Responsive** | Mobile-friendly layout, nav collapses on small screens |

---

## 💼 Experience

### Honeywell HTCS — Cybersecurity Advocate *(June 2025 – Present)*
Responsible for ensuring Secure Software Development Lifecycle (SSDLC) activities comply with Honeywell and SBG policies, standards, processes, and procedures within product releases.

### Siemens Digital Industries Software — Digital Twin Integration Engineer *(Academic)*
Designed and developed a Cyber-Physical Warehouse System with a synchronized Digital Twin for real-time monitoring, simulation, and process optimization.

### Ford Motor Company — Digital Twin Developer *(Academic)*
Designed and implemented a Digital Twin for an Autonomous Integrated Manufacturing System, enabling predictive insights and remote process visibility on the production floor.

---

## 🛠️ Projects

| Project | Category | Media files used |
|---|---|---|
| Pick-and-Place Robot with Vision AI | Robotics · ML | `Object_detection.png` |
| Cyber-Physical Warehouse + Digital Twin | Siemens · Digital Twin | `DashboardDigitaltwin.png`, `HMI_Digitaltwin.png` |
| Autonomous Manufacturing Digital Twin | Ford · Manufacturing | `DashboardDigitaltwin.png` |
| Automated Material Unloading Station | Automation · AGV | `AGV.jpg`, `AGV_Demo.mp4` |
| Functional Air Rowing Machine | Mechanical Design | `RowingMachine.jpg`, `RowM_Demo.mp4` |
| Electratón CCM & SAIA | Team · SAIA & Electratón CCM | `SAIA.jpg` |

---

## 🔧 Skills

### Programming
`Python` · `C++` · `MATLAB` · `GitHub` · `GitHub Actions` · `Jenkins`

### Low-code · Platforms
`Mendix` · `Canva`

### CAD & Design
`SolidWorks` · `AutoCAD` · `Fusion 360` · `PTC Creo`

### Automation & Control
`TIA Portal (Siemens)` · `Studio 5000 (Rockwell)` · `Digital Twin` · `AGV Systems`

### Cloud & DevOps
`AWS` · `Azure`

### Methodologies
`Design Thinking` · `Agile · Scrum` · `Lean Six Sigma` · `DFx / QFD` · `JTBD / SMART`

### Cybersecurity
`SSDLC` · `Jira (PSJira)` · `SD Elements` · `Black Duck` · `Threat Modeling`

---

## 📜 Certifications

| Year | Certification |
|---|---|
| 2026 | FIFA World Cup 2026 Mexico City - Volunteer Program |
| 2026 | Microsoft Certified: Security, Compliance, and Identity Fundamentals |
| 2025 | Software Security Practitioner — Architect |
| 2025 | Lean Six Sigma White Belt |
| 2025 | Mendix Rapid Developer Certification |
| 2024–25 | Formula 1 Mexican Grand Prix — Volunteer Program |
| 2024 | PTC Creo Workshop — Provided by Generac |
| 2023 | SolidWorks Certification |
| 2022 | Microsoft Office Specialist Certification |

---

## 🌐 Languages

| Language | Level |
|---|---|
| Español | Native · C2 |
| English | Advanced · C1 |
| Français | Basic · A1 |

---

## ➕ Adding media to a project card

1. Upload your file to `MediaFiles/` on GitHub (**Add file → Upload files**)
2. Commit with a descriptive message, e.g. `"Add AGV project photo"`
3. Open `GitHubPortfolio.html`, find the card, replace the placeholder:

```html
<!-- Single image (clickable, opens lightbox) -->
<img class="media-img"
     src="MediaFiles/your-image.jpg"
     alt="Short description"
     onclick="openLightbox(this.src)"/>

<!-- Two-photo side-by-side grid -->
<div class="media-grid">
  <img src="MediaFiles/photo-1.jpg" alt="..." onclick="openLightbox(this.src)"/>
  <img src="MediaFiles/photo-2.jpg" alt="..." onclick="openLightbox(this.src)"/>
</div>

<!-- Video player -->
<video class="media-video"
       src="MediaFiles/demo.mp4"
       controls muted playsinline>
</video>
```

## 🌓 Dark / Light mode

The **☽ / ☀ toggle** is in the top-right corner of the nav bar.

- **First visit** — automatically matches your OS preference (`prefers-color-scheme: dark/light`)
- **After toggling** — choice is saved in `localStorage` and persists across reloads and browser sessions
- **To reset to OS default** — open DevTools → Application → Local Storage → delete the `theme` key

---

## 📬 Contact

| Channel | Details |
|---|---|
| Phone | +52 55 2094 4665 |
| School email | a01658350@tec.mx |
| Personal email | rodrigoechavarria16@gmail.com |
| LinkedIn | [linkedin.com/in/rodrigo-echavarría](https://www.linkedin.com/in/rodrigo-echavarr%C3%ADa-70758130b/) |

---

*Rodrigo Echavarría Moreno · Mechatronics Engineer · Tec de Monterrey · 2026*
