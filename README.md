# QualiTrack – Pharmaceutical Quality Management Platform

## Project Overview

**QualiTrack** is a SaaS platform developed by **ClosedSource** to **digitize and automate pharmaceutical manufacturing quality control**.

Our solution integrates **IoT telemetry** from industrial equipment (autoclaves, pH meters, pressure sensors) with an automated **BPM compliance engine**, generating **immutable audit trails** and **PDF reports** ready for DIGEMID regulatory inspections — all in real time.

QualiTrack targets two key segments of the pharmaceutical quality ecosystem in Latin America:
- **QA Managers and Directors** at private pharmaceutical laboratories.
- **Public Health Directors** at institutions such as the INS (Instituto Nacional de Salud).

---

## Key Features

- **Real-Time IoT Monitoring:** Automated capture of temperature, pressure, and pH from industrial equipment — no manual entry, no transcription errors.
- **Automated BPM Compliance Engine:** Evaluates every sensor reading against configured GMP parameters. Blocks non-conforming batches instantly.
- **Immutable Audit Trails:** Every action is timestamped and tamper-proof. Batch traceability PDF reports generated in seconds — not days.
- **Digital Batch Management:** Full lifecycle management of production batches with digital signatures for lot release.
- **Instant Deviation Alerts:** Push notifications, email, or SMS when a critical variable goes out of range. Reaction time under 5 seconds.
- **KPI Analytics Dashboard:** Conformance rates, deviation trends, and release times — with actionable insights.
- **Internationalization (i18n):** Full support for **English (EN)** and **Spanish (ES)** via `data-i18n` attributes and a floating language switcher.

---

## Subscription Plans

| Plan | Price | Best For |
|---|---|---|
| **Standard Lab** | $199/month | Private laboratories of medium size |
| **Enterprise** | $599/month | Large institutions and public health entities (INS) |

Both plans include a **15% discount** with annual billing.

---

## Technologies Used

This Landing Page was built with standard web technologies, prioritizing performance, accessibility, and internationalization:

- **HTML5 & CSS3** — Page structure and styling with CSS custom properties for consistent branding.
- **Vanilla JavaScript** — Interactivity: language switching, accordion, plan billing toggle, scroll-reveal animations, and sticky header.
- **Font Awesome 5** — Iconography.
- **Google Fonts** — Typography (`Rubik`).
- **Flexbox / CSS Grid** — Responsive and modular layout.

---

## Project Structure

```
ClosedSource-LandingPage/
├── index.html                         # Main landing page
├── README.md
└── public/
    ├── assets/
    │   ├── styles/
    │   │   └── style.css              # Global stylesheet + branding variables
    │   ├── scripts/
    │   │   ├── main.js                # i18n engine, accordion, plans toggle, animations
    │   │   └── translations/
    │   │       ├── en.js              # English translations (translationsEN)
    │   │       └── es.js              # Spanish translations (translationsES)
    │   └── images/                    # Team photos, logo, hero image
    └── sections/
        ├── tos.html                   # Terms of Service
        └── policies.html             # Privacy Policy (Ley N° 29733)
```

---

## Team — ClosedSource

| Name | Code | Role |
|---|---|---|
| Billy Jake Ruiz Madrid | U202116401 | Software Engineer |
| Renato Guillermo Calvo Yalan | U202217053 | Software Engineer |
| Adrian Quiroz Cáceres | U202214864 | Software Engineer |
| Dyron Huapaya Galindo | U202322855 | Software Engineer |
| Felix Orlando Becerra Ttito | U20211b387 | Software Engineer |

> Software Engineering students at **Universidad Peruana de Ciencias Aplicadas (UPC)**.

---

## Copyright

Copyright © 2026 IoTech. All rights reserved.