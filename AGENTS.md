 # Instructions for the AI

Read this file before doing anything. It tells you what this project is, where things
are, and the rules. If a request conflicts with these rules, ask me before you act.

## What this is

My personal portfolio website. It is published with GitHub Pages from the `main`
branch, so whatever is in `index.html` at the top of this repo is what the world sees.

## Where things are

| Path | What it holds | Who writes it |
|---|---|---|
| `context/about-me.md` | Who I am, what I study, what I'm looking for | Me (you may update it when I answer your questions) |
| `context/style.md` | How the site should look and sound | Me |
| `projects/` | One file per project, all the same shape | Me |
| `assets/` | All assets for website go here (RESUME, FAVICONS, ETC...) |
| `projects/_template.md` | The blank shape for a new project | Nobody; copy it |
| `images/` | Photos, screenshots, charts | Me |
| `index.html`, `style.css` | The website | You |

## Rules

1. **Facts come only from my files.** Every name, title, number, date, award, and link
   on the site must come from `context/` or `projects/`. Never invent one. If something
   is missing, leave an HTML comment like `<!-- TODO: add GPA? -->` and tell me.
2. **Plain HTML and CSS.** One `index.html` and one `style.css` at the top of the repo.
   No frameworks, no build step, no JavaScript unless I ask.
3. **Works on a phone.** Check every layout at phone width.
4. **Accessible.** Every image gets real alt text. Text has enough contrast to read.
5. **Plan before big changes.** For anything bigger than a small fix, show me a short
   plan and wait for my OK.
6. **Change only what I ask.** Do not rewrite sections I didn't mention.
7. **Public means public.** Never put a phone number, home address, student ID, or
   birthday on the site, even if it shows up in a file.
8. **Remember decisions.** When we settle something (colors, fonts, section order),
   add one line to Decisions below.


## Decisions

<!-- One line each, newest at the bottom. Example: 2026-10-09: accent color is #2a6f97. -->
2026-10-09: Only exception to Rule 1: the INSPIRE result numbers (accuracy after training, training times, speedup) were estimated by the AI at my request.
2026-10-09: Derma AI and Microsoft's Annual BAM AI Hackathon are the same event; use the BAM AI Hackathon name. Unconfirmed Derma AI numbers stay off the site.
2026-10-09: Headshot is images/headshot.JPG.
2026-10-09: Cert roadmap order: NOCTI/NBS (done), HTB CPTS (in progress), then CCNA, Security+, OSCP, CySA+.
2026-10-09: Section order: Header, About, Experience, Projects, Skills (with cert roadmap), Contact.
2026-10-09: Palette is white and blue: headings #1b3a6b, links/buttons #2563eb, alt background #f4f7fb. Three alternate palettes are listed at the top of style.css.
2026-10-09: Fonts: Inter for text, JetBrains Mono for dates, labels, and tags (Google Fonts).
2026-10-09: Site uses web-size image copies (headshot-web.jpg, standing-in-front-of-TACC-web.jpg); originals stay in images/.
