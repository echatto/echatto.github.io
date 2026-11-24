# Erolflyn Jr. Chatto — Full-Stack Web Development & Engineering Portfolio

Responsive static portfolio for GitHub Pages. No backend, dependencies, paid hosting or build command required.

## Preview locally (Windows / VS Code)
Open the extracted folder in VS Code. Open `index.html` directly or run `python -m http.server 8000` in the VS Code terminal and visit http://localhost:8000. Ctrl+C stops the server.

## Publish using GitHub Pages
1. Create a public GitHub repository named `portfolio` (or `YOUR_USERNAME.github.io` for a root personal website).
2. Extract the ZIP and upload the contents of the `portfolio` folder to the repository root, preserving `assets/`. The root must contain `index.html`, `styles.css` and `script.js`.
3. Commit the files to the `main` branch. Include `.nojekyll` if possible.
4. Open repository **Settings → Pages → Build and deployment → Deploy from a branch**. Select **main** and **/ (root)**, then **Save**.
5. Once deployment completes, visit the URL shown in Settings → Pages, normally `https://YOUR_USERNAME.github.io/portfolio/`.

Alternatively, with Git installed and an empty remote repository created, run inside the extracted folder:

```powershell
git init
git add .
git commit -m "Publish engineering portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git push -u origin main
```

Then enable GitHub Pages as above. Official docs: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Customize
- `index.html`: content, projects, experience, contact links and SEO metadata. Duplicate a project article, assign `data-category` (web, automation, engineering or deployment), and update the displayed project counts.
- `styles.css`: responsive layout and theme variables.
- `script.js`: filtering, screenshot viewer, mobile menu, theme and email copying.
- `assets/`: workflow screenshots, redacted MSIM dashboard and Windows installer screenshot, favicon and public résumé. The phone number was removed from the PDF; email and LinkedIn remain.

## Public-release checklist
- Confirm all employment dates, titles and experience claims are current.
- Confirm you may publish the screenshots and enterprise project summaries. Inspect any future screenshots for customer information, API keys and private URLs.
- Check the public résumé and contact details. The PDF is publicly downloadable, not password protected.
- Screenshots are portfolio evidence, not downloadable n8n workflow source code. This site sends no SMS, creates no payment sessions, and holds no API credentials.
- No GitHub profile URL is assumed; add your actual URL when available.

## Featured projects and work showcases

1. MSIM V2 — Source Inspection Management (full-stack web application)
2. Enterprise Web Application Development (professional experience showcase)
3. Custom Client Websites & Web Solutions (freelance experience showcase)
4. Automated Monthly Billing & SMS Reminder System
5. Xendit — Automated Bulk Payment Link Generation & Recovery
6. Invoice Follow-up & Escalation Automation
7. Student Grading & Report Card Automation
8. Structural Steel CDM Data Feed
9. Windows Installer Development & Deployment

The homepage prioritizes full-stack web development and the project gallery has a dedicated Web development filter. The enterprise and freelance summaries describe work from the résumé; no invented client names, screenshots or live demo links are included.

The MSIM preview uses irreversible opaque redactions. The internal feature documentation and unredacted screenshot are not included. AI extraction is described as a roadmap item, not a verified deployed capability. Confirm permission to publish the enterprise screenshot and summary even after redaction.

The installer preview permanently redacts local asset paths. No setup executable, application files, student records, or credentials are included. Confirm permission to publish the enterprise installer preview and branding.
