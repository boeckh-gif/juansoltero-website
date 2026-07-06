# Project: Personal Website — juansoltero.com

**Status:** Active — live on the internet  
**Location:** `/Users/jlboeckh/MD/projects/website/`  
**Live URL:** https://juansoltero.com  
**Local preview:** http://localhost:3001  
**GitHub:** https://github.com/boeckh-gif/juansoltero-website  
**Hosting:** Railway (auto-deploys on git push)  
**Domain registrar:** Cloudflare  

## What It Is
Personal AI-optimized profile site for Juan Leopoldo Boeckh Soltero. Built in Node.js + Express. Single HTML file with embedded CSS and JS. Bilingual EN/ES toggle.

## How to Run Locally
```bash
cd /Users/jlboeckh/MD/projects/website
npm install   # first time only
node server.js
```

## How to Deploy Changes
```bash
cd /Users/jlboeckh/MD/projects/website
git add .
git commit -m "Description of change"
git push
```
Railway redeploys automatically. Live in ~1 minute.

## Sections
- Hero — photo, headline, locations
- Story — personal background, lineage, roots
- Services — The Hand (PM), The Hammer (AI), The Nail (emergency services + real estate)
- Who I Serve — restoration, plumbing/HVAC, real estate, US-Mexico cross-border
- Roots — Sierra de Quila, Arriero de Quila
- Contact — form saves to data/contacts.json
- Footer — LinkedIn, Ask AI about me (Claude, ChatGPT, Perplexity, Gemini)

## To Do
- Replace headshot with updated professional photo
- Add clean barrel photo (Arriero de Quila) to Roots section
- Add Solara Consulting service page when ready
- Connect custom email when domain email is set up
