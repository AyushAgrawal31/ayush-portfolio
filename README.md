# Ayush Agrawal: Portfolio

Personal portfolio of Ayush Agrawal, software engineer and data engineer. It covers automation, AI tooling and Microsoft Fabric data pipelines.

**Live site:** _add your link here after deploying_

## What is on the site

- **Hero:** name, roles, photo, call to action, proof strip
- **About:** short bio and profile summary
- **Work:** four projects with a clickable project list. Each has key numbers, a pipeline diagram, what was built and the stack
  - AI-driven UI automation pipeline (Playwright, TypeScript, Codex CLI)
  - Swagger-driven API automation framework (Python, pytest, Allure)
  - Website analytics ETL (Microsoft Fabric, PySpark, Power BI)
  - Supply chain monitoring pipeline (Microsoft Fabric, PySpark, Power BI)
- **Experience:** IALTruist LLC and Techment Technology internships, with metrics
- **Skills:** grouped by area
- **Credentials:** DP-600, B.Tech, awards
- **Freelance:** services and process
- **Contact:** message composer that opens a ready email draft, plus LinkedIn and GitHub links
- **Resume:** download buttons for software engineering and data engineering versions

## Design

- Scrolling story layout with large condensed headings
- 60-30-10 colour system: background, supporting surfaces, cyan accent
- Light and dark themes, with a toggle in the top bar
- Animated data-network background, custom cursor and subtle sound effects
- Sound starts after the first click, tap or key press, because browsers block earlier audio
- Respects the reduced-motion setting
- Works on phone, tablet and desktop

## Tech

Plain HTML, CSS and JavaScript in a single file. No framework and no build step.

- Fonts: Archivo, Hanken Grotesk and IBM Plex Mono from Google Fonts
- Background and cursor effects: Canvas API
- Sound effects: Web Audio API

## Files

```
index.html                      the whole site
ayush.jpg                       profile photo
resume-software-engineer.pdf    resume, software engineering
resume-data-engineer.pdf        resume, data engineering
README.md                       this file
```

## Run locally

Open `index.html` in a browser. Or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy

Any static host works.

- **Netlify Drop:** drag the folder onto app.netlify.com/drop
- **Vercel:** import the repo, framework preset "Other", deploy
- **GitHub Pages:** Settings, Pages, deploy from branch `main`, root folder

## Edit your content

- Text: edit the HTML sections in `index.html` (`about`, `work`, `experience`, `skills`, `freelance`, `contact`)
- Colours: change the tokens in the `:root` blocks at the top of the `<style>` tag
- Photo: replace `ayush.jpg` with a new image of the same name
- Resumes: replace the two PDF files, keeping the file names

## Contact

- Email: ayushagrawal9630@gmail.com
- LinkedIn: https://www.linkedin.com/in/ayush-agrawal315
- GitHub: https://github.com/AyushAgrawal31
