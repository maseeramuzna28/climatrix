# CLIMATRIX — Campus Climate Intelligence Prototype

An enhanced, responsive, static front-end prototype for the CLIMATRIX hackathon concept.

## Run locally
Open `index.html` in a browser, or run a local static server:

```bash
python -m http.server 5500
```
Then visit `http://localhost:5500`.

## Deploy
This is a static site and can be deployed directly to Vercel, Netlify, or GitHub Pages. No build command is required; set the output/root directory to the repository root.

# 🌱 CLIMATRIX

### The Closed-Loop Climate Copilot for Campuses

🚀 **Live Demo:** https://maseeramuzna28.github.io/climatrix/

💻 **GitHub Repository:** https://github.com/maseeramuzna28/climatrix

> Don't just count carbon. Prove your campus is cooler, greener and safer because of what you did.


## What is enhanced in this build
- Preserves the original six-module CLIMATRIX dashboard and navigation.
- Adds refined visual hierarchy, hover states, glow details, responsive polish and reduced-motion support.
- Adds a working demo risk-layer switcher and an interactive electricity-reduction what-if slider.
- Adds drag-and-drop bill selection and evidence-file selection (demo UI only).
- Updates the campus pulse date automatically.

## Previous v0.2 improvements
- Command-centre hero panel that explains the closed-loop climate workflow at a glance.
- Campus pulse resilience visual and high-priority insight strip.
- Clearer calls to action into the AI copilot and climate risk map.

## Demo interactions
- Sidebar navigation switches between six product areas.
- Carbon intelligence: upload any image/PDF to trigger a clearly labelled simulated bill extraction.
- AI copilot: ask the included sample prompts or enter a campus climate question for a scripted demo response.
- What you see: dashboard metrics, map overlays, emissions charts, evidence trails and student engagement cards.

## Important prototype limitations
All campus metrics, map layers, intervention outcomes, confidence levels and copilot responses are illustrative demo data. The upload interaction is a UI simulation; it does not perform OCR, calculate official emissions, call an LLM, query satellite imagery, or persist records. Production implementation needs verified emission-factor datasets, geospatial processing, authentication, database storage, evidence validation and real AI/RAG integrations.
