# Site Plan - bosmith.tech

## Overview

A professional personal website for Brandon "Bo" Smith, Principal AI and Automation Architect at IBM. The site is a static frontend-only site designed to be hosted on GitHub Pages.

## Design Direction

- Business professional, modern, and edgy
- Dark theme with blue/purple accent gradient
- Responsive design with mobile hamburger menu
- Clean typography using Inter font family
- Scroll-based animations via Intersection Observer

## Technology Stack

- HTML5 (semantic markup)
- CSS3 (custom properties, grid, flexbox, animations)
- Vanilla JavaScript (no frameworks)
- Google Fonts (Inter)
- No backend, no build tools -- static files only

## Site Sections

1. **Navigation** - Fixed top navbar with logo (bo_headshot.jpeg) and section links
2. **Hero** - Full-viewport intro with headshot, name, title, tagline, and CTAs
3. **About** - Summary paragraph derived from LinkedIn profile
4. **Experience** - Timeline of all career roles with dates and descriptions
5. **Skills** - Grid of core technical competencies plus certifications
6. **Education** - Degree and program listings
7. **Contact** - Email, LinkedIn, and GitHub links
8. **Footer** - Copyright

## Content Source

All biographical content (experience, skills, education, certifications, summary) is sourced from Profile.pdf, which is an export of the LinkedIn profile. This is the single source of truth for factual content.

## File Structure

```
bosmith.tech/
  index.html          -- Single-page site
  bo_headshot.jpeg     -- Headshot used as favicon and logo
  Profile.pdf          -- LinkedIn profile export (content source)
  AGENTS.md            -- Agent instructions
  CLAUDE.md            -- References AGENTS.md
  css/
    style.css          -- All styles
  js/
    main.js            -- Navigation toggle, scroll effects, animations
  docs/
    PLAN.md            -- This file
```

## Hosting

GitHub Pages from the repository root. No custom build step required.
