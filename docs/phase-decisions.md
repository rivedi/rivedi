# jazdibar.com — Project Decisions

## Project Overview
Personal professional website for **Dr. Jazmín Díaz-Barrios, PhD** — the user's mother.
Live URL: https://jazdibar.com  
GitHub repo: https://github.com/rivedi/rivedi (GitHub Pages, `main` branch)  
Domain: jazdibar.com (registered on Namecheap, CNAME points to GitHub Pages)  
Local mirror: C:\Users\quida\Documents\Projects\jazdibar.com  
GitHub account: `rivedi` (separate from user's main `ponquecitos` account)

## Tech Stack
- **Static HTML/CSS** — hand-written in Notepad, no build tools or frameworks
- **Single stylesheet:** `/assets/css/style.css`
- **Hosted:** GitHub Pages (free tier)
- **Analytics:** Google Analytics 4 (tag: G-1RVFSHX2TQ)
- **Booking:** TidyCal (tidycal.com/example/discovery — placeholder URLs, may need updating)
- **SEO:** Schema.org JSON-LD structured data, hreflang, sitemap.xml + sitemap.xsl, robots.txt, BingSiteAuth.xml

## Site Structure
```
/                    → EN homepage (index.html)
/about/              → EN about & CV page
/privacy.html        → Privacy policy (EN)
/terms.html          → Terms of service (EN)
/es/                 → ES homepage
/es/about/           → ES about & CV
/es/privacy.html     → Privacy policy (ES)
/es/terms.html       → Terms of service (ES)
/assets/css/style.css
/assets/*.png|ico    → Favicons + web manifest
/assets/*.pdf        → CV downloads (EN + ES)
/assets/jazmin-portrait.jpg
```

## Subject / Content
Dr. Díaz-Barrios is a Venezuelan-origin academic and consultant:
- **Roles:** Senior Management Consultant (BCTP, USA), Professor/Researcher (Universidad del Zulia), Doctoral Advisory Professor (Global Humanistic University, Curacao)
- **Credentials:** Post-Doctorate (UNEFA), PhD in Management Sciences (URBE), MS in Finance + Specialist in Business Economics (UCAB), BS in Administrative Sciences (UNIMET)
- **Research:** 70+ scientific publications, h-index 12, i10-index 17
- **Languages:** Spanish, English, French, Italian
- **Academic profiles:** LinkedIn, Google Scholar, ResearchGate, ORCID, AD Scientific Index, Web of Science, Academia.edu, SSRN
- **Latest book:** *Controlando financieramente mi emprendimiento* (Amazon, 2024, Spanish only)
- **Contact:** jazdibar@gmail.com

## Design System
- **Primary color:** `#0056b3` (deep professional blue)
- **Accent:** `#f0ad4e` (gold/yellow)
- **Dark:** `#1a1a1a` (text)
- **Light:** `#f4f4f4` (background)
- **Hero bg:** `#0a2540` (deep navy)
- **Font:** System sans-serif stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto…)
- **Max content width:** 900px

## Blog
- External Blogspot: http://presupuesto-jazdibar.blogspot.com/
- Linked from nav as "Blog ↗" (opens in new tab)

## Tracking
Tracked in the Roadmap dashboard under the **Websites** tab (`tools-roadmaps` project).
- Registry: `C:\Users\quida\Documents\Projects\tools-roadmaps\registry.yml` → `websites` → `jazdibar.com`
- Note: jazdibar.com is a website project, not a tool — it does not belong in the tools `projects` list.

## Pending / Roadmap Items
- [ ] **Blogspot custom theme** — style the Blogspot blog to visually match jazdibar.com
- [ ] **Blog redirect** — redirect or route `/blog/` subdirectory to the Blogspot (or migrate posts)
- [ ] **TidyCal URLs** — current booking links use placeholder `tidycal.com/example/...`; need real URLs
- [ ] **Mobile nav** — no hamburger menu; nav wraps on mobile (functional but rough)

## Hub Note — 2026-08-02
*Decision recorded in tools-roadmaps project hub.*

Un-gitignored docs/phase-decisions.md so it syncs across machines; pushed using the rivedi account's token after a plain git push hit the wrong cached credential. Also fixed the hub registry's dir field, which pointed at a nonexistent jazdibar.com folder; the real checkout is named rivedi.
