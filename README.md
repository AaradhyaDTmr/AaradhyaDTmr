# aaradhyadtmr.github.io

Personal portfolio website for **Aaradhya Dev Tamrakar** — BEI IV/I student at Kathmandu Engineering College (KEC), Institute of Engineering (IOE), Tribhuvan University.

## About

This site showcases my work as an Electronics, Communication and Information Engineering student, IEEE KEC Vice Chair, Fuse AI Fellow (Fusemachines 2026), NSSR DataCamp Fellow (Cohort 2), and robotics enthusiast. It features a dark-themed, luxury editorial design with custom CSS animations and interactive elements.

## Features

- Responsive design optimised for all devices
- Custom cursor animation (pointer: fine only — keyboard/touch safe)
- Smooth scrolling navigation with active-section highlighting
- Light / dark theme toggle
- Back-to-top button (appears after scrolling 400 px)
- Profile photo with grayscale-to-colour hover effect (`loading="lazy"`)
- Proficiency dot scale (●●● / ●●○ / ●○○) replacing arbitrary skill bars
- Professional portfolio layout — projects, experience, skills, contact
- Contact form with EmailJS (primary + auto-reply) → Formspree (fallback) → mailto (last resort)
- Full ARIA landmark pass — `<main>`, `aria-labelledby` on all sections, `role="navigation"` on mobile drawer, `role="contentinfo"` on footer, skip link to `#main-content`, dynamic hamburger `aria-expanded`
- `prefers-reduced-motion` guard on all animations
- Google Analytics 4 (G-P38642CDGB) — pageview tracking, scroll depth, outbound clicks, CV download events, contact form conversion events
- Font render-blocking eliminated — `media=print` onload swap + `rel=preload`; `@font-face` `size-adjust` fallbacks to reduce FOUT/CLS

## Lighthouse Scores *(May 2026)*

| | Performance | Accessibility | Best Practices | SEO |
|---|---|---|---|---|
| **Desktop** | 98 | 100 | 100 | 100 |
| **Mobile** | 78 | 100 | 100 | 100 |

Mobile FCP 3.0 s / LCP 4.3 s on slow-4G simulation. EmailJS (65 KiB) is an irreducible third-party cost. HubSpot Website Grader: **90 / 100**.

## Technologies Used

- HTML5
- CSS3 (Custom properties, Flexbox, Grid)
- JavaScript (Vanilla) — DATA-driven architecture (content separated from render logic)
- Google Fonts — Cormorant Garamond · DM Mono · Instrument Sans
- EmailJS — contact form with auto-reply
- Formspree — contact form fallback
- Google Analytics 4 (GA4) — visitor tracking, CV download events, contact form events

## Profile Photo & CV

**Profile photo:** Add `photo.jpg` to the repo root (recommended: ~400×500 px minimum). The config already references `profilePhoto: "photo.jpg"` — just push the file.

**CV download:** Place `AARADHYA_DEV_TAMRAKAR_CV.pdf` in the repo root. The hero **Download CV** button is already linked — no code changes needed.

## Local Development

```bash
git clone https://github.com/AaradhyaDTmr/AaradhyaDTmr.github.io.git
cd AaradhyaDTmr.github.io
# Open index.html in your browser
```

## Deployment

Deployed automatically via GitHub Pages. Changes pushed to `main` go live at **[https://aaradhyadtmr.github.io](https://aaradhyadtmr.github.io)**.

## Contact

| Channel | Detail |
|---------|--------|
| Email | aaradhyadevtmr@gmail.com |
| LinkedIn | [aaradhya-dev-tamrakar](https://www.linkedin.com/in/aaradhya-dev-tamrakar) |
| GitHub | [AaradhyaDT](https://github.com/AaradhyaDT) |
| Instagram | [@aaradhya_dev_tamrakar](https://instagram.com/aaradhya_dev_tamrakar) |
| X / Twitter | [@AaradhyaDT](https://x.com/AaradhyaDT) |

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
