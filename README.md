# ANTIGRAVITY

A NASA.gov–inspired single-page web prototype titled **Antigravity**. Built with pure HTML5 and CSS3, the design captures a clean, cinematic aerospace aesthetic using the official NASA color palette, bold typography, and subtle UI overlays.

---

## 🔧 Features

- **Visual Identity:** Deep black background, charcoal accents, NASA red highlights, and wide uppercase typography.
- **Navigation:** Sticky header with logo, centered links, search icon, and pulsing `LIVE` button.
- **Hero Section:** Full-viewport background image with gradient overlay, animated scan line, and call-to-action.
- **Telemetry HUD:** Corner displays mimicking flight data, complete with flicker animation.
- **Scanner Effect:** A subtle red scanning line traverses the hero image continually.
- **Authentication System:** Role-based login with secure dashboards for different personnel types.
- **Interactive Dashboards:** Real-time telemetry, command execution, and role-specific interfaces.
- **Responsive Layout:** Fluid grid designs collapse gracefully on tablet and mobile screens.
- **Content Sections:** Mission updates grid, featured two-column presentation, and footer with multi-column links.
- **Favicon Suite:** Custom icons (SVG) with manifest for PWA support.

## 🧩 Technologies

- HTML5
- CSS3 (Flexbox & Grid, animations, custom properties)
- JavaScript (ES6+ for interactive features)
- No frameworks or backend required

## 🔐 Authentication

The application includes a role-based authentication system with the following demo credentials:

### Default Login Credentials

| Role | Username | Password | Dashboard Access |
|------|----------|----------|------------------|
| **Commander** | `commander` | `antigravity2026` | Mission Control & Strategic Oversight |
| **Captain** | `captain` | `missioncontrol` | Navigation & Crew Management |
| **Engineer** | `engineer` | `propulsion` | Systems & Maintenance |
| **Scientist** | `scientist` | `research` | Research & Data Analysis |

> **Note:** These are demo credentials for testing purposes. In production, implement secure authentication.

## 🧭 Navigation

Use hash links within the page for smooth scrolling:
- `#missions` – Latest updates
- `#galaxies`, `#technology`, `#about` – Placeholder sections

## 🏁 Getting Started

1. Clone or download the repository.
2. Open `index.html` in any modern browser to view the landing page.
3. Click "Login" to access the authentication system.
4. Use the demo credentials above to access role-specific dashboards.
5. Explore different command interfaces and interactive features.

> All resources are local or pulled from public domain/Unsplash for placeholders.

## 📂 File Structure

```
/
├─ index.html                    # Main landing page
├─ login.html                    # Authentication page
├─ signup.html                   # User registration page
├─ commander-dashboard.html      # Commander role dashboard
├─ captain-dashboard.html        # Captain role dashboard
├─ engineer-dashboard.html       # Engineer role dashboard
├─ scientist-dashboard.html      # Scientist role dashboard
├─ styles.css                    # Main stylesheet
├─ javascript.js                 # Main page interactions
├─ login.js                      # Login page functionality
├─ signup.js                     # Signup page functionality
├─ dashboard.js                  # Dashboard common functionality
├─ favicon.svg                   # Favicon
├─ apple-touch-icon.svg          # Apple touch icon
├─ manifest.json                 # PWA manifest
├─ assets/                       # Image assets
└─ README.md                     # This file
```

## 🛠️ Customization

- Replace placeholder images with real NASA assets or project visuals.
- Adjust telemetry values, scan timing, or color variables as needed.
- Add additional sections or nav links for extended content.

## 🚀 Notes

This project has evolved from a static design prototype to a fully interactive mission control simulation. It includes client-side authentication, role-based dashboards, and real-time telemetry simulation. The application can be deployed to any static host or run locally. All authentication is simulated for demonstration purposes.

---

© 2026 ANTIGRAVITY Design Initiative