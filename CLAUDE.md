# hbanalyst

## What this is
A professional site for home building industry analysis and insights. HB = Home Building. The direction is still being defined — future sessions should brainstorm with B_Shappy about what this becomes (tools, data, reports, dashboards, etc.).

## Owner
B_Shappy (brschappert@gmail.com)

## Live site
https://hbanalyst.com

## Hosting
- GitHub repo: https://github.com/brschappert/hbanalyst
- Hosted on Vercel — auto-deploys on every push to main
- DNS managed via Namecheap pointing to Vercel

## Stack
- Plain HTML/CSS for now (no framework)
- Output directory: /public
- No build step required

## Structure
```
public/
  index.html    # main landing page
  computer.png  # placeholder hero image
```

## Style / tone
- Light background (#f8f7f4), navy (#1a1a2e), blue accent (#2e6da4)
- Serif font (Georgia) for headings, sans-serif for body
- Professional, data-driven, industry-focused
- Audience: home building professionals, analysts, executives

## Vision (TBD — brainstorm in future sessions)
- Industry data tools?
- Market analysis dashboards?
- Reports or newsletters?
- AI-powered analysis for home builders?

## Deploy workflow
```bash
# make changes
git add .
git commit -m "describe what changed"
git push
# Vercel auto-deploys in ~30 seconds
```
