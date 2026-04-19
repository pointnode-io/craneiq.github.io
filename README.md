# craneIQ Website

Official website for craneIQ — Overhead Crane Technology.

**Live site:** https://craneiq.co.uk  
**Product of:** Pointnode Ltd, West Midlands, UK  
**Contact:** joe@pointnode.io

---

## Products

Nine products, one intelligent platform. Each works alongside existing crane controls — no rip-and-replace, no proprietary lock-in.

| Product | Code | Description |
|---------|------|-------------|
| craneIQ Core | CIQ-COR | Hoist controller — DWP tracking, load spectrum, overload protection |
| craneIQ Automation | CIQ-AUT | Teach-and-replay crane automation, no code, commissions in a day |
| craneIQ Monitoring | CIQ-MON | Standalone condition monitoring — DWP, vibration, every lift logged |
| craneIQ Cloud | CIQ-CLD | Live crane data anywhere — alerts, remote diagnostics, multi-site |
| craneIQ Vision | CIQ-VIS | Camera on crane, passive target on hook — stops snags and side pull |
| craneIQ Antisway | CIQ-ASW | Reduces load swing using existing VFDs only — no sensors or encoders |
| craneIQ Zoning | CIQ-ZON | Software-defined no-fly zones — multi-crane collision prevention |
| craneIQ LoadTrack | CIQ-LTK | Weighs and logs every lift — wireless displays, process cycle logging |
| craneIQ Guard | CIQ-GRD | Pre-use inspection enforcement — crane locked until every check passes |

---

## File Structure

```
index.html                    Main website (homepage)
404.html                      Custom error page
craneiq-overview.html         Product overview brochure (print to PDF)
brand-guidelines.html         Brand guidelines (internal — not linked from nav)
brand-guidelines.md           Brand guidelines source
README.md                     This file

assets/
  logos/                      SVG logo files (11 variants)
  illustrations/              Product illustration SVGs

datasheets/
  craneiq-core.html
  craneiq-automation.html
  craneiq-monitoring.html
  craneiq-cloud.html
  craneiq-vision.html
  craneiq-antisway.html
  craneiq-zoning.html
  craneiq-loadtrack.html
  craneiq-guard.html
```

---

## Homepage Sections

1. **Hero** — wordmark, tagline, hero stats, animated pendulum graphic
2. **Products** — nine-card grid, each links to a dedicated datasheet
3. **How It Works** — signal path diagram: Pendant → craneIQ Platform → Existing Controller → Motors & VFDs
4. **Why craneIQ** — six cards covering key differentiators
5. **Who It's For** — Plant Manager / Engineering Manager / Crane Partner
6. **Industries** — six industry sectors
7. **Compatibility** — open architecture, protocols (Hardwired I/O first, then fieldbus)
8. **Contact** — Formspree form (ID: xeevjlgd), sends to joe@pointnode.io

---

## Tech

Static HTML/CSS/JS. No frameworks, no dependencies, no build step.  
Hosted on GitHub Pages with custom domain craneiq.co.uk.  
Contact form via [Formspree](https://formspree.io) — form ID `xeevjlgd`.

---

## Brand

- **Primary font:** Open Sans 300/400/600
- **Mono font:** Share Tech Mono
- **Brand teal:** `#008B9A`
- **Radar green:** `#4ccc80`
- **Theme:** Light — white `#ffffff` / light grey `#f4f5f7`

Full brand guidelines at `craneiq.co.uk/brand-guidelines.html`  
(not indexed — share URL directly)

---

## Notes

- The How It Works diagram labels the craneIQ node as **Platform** — not Core. Core is one product within the platform.
- Cloud is not a node in the signal path diagram — it sits within the platform.
- Protocol order is always: Hardwired I/O first, then Modbus TCP, Profinet, EtherNet/IP.
- DWP always described as "counts down from 100% based on actual usage".
- "Galvanizing" with z throughout.
- No competitor names mentioned anywhere.
