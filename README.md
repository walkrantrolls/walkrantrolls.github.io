# Portfolio

A clean, minimal one-page portfolio built with plain HTML, CSS, and JavaScript — no build step, ready for GitHub Pages.

Experience, skills, and education are pulled from your LinkedIn profile (Vischari Solutions, Mastek, Inscripts, Global Eagle, and earlier roles).

## Before you publish

1. **Add your résumé.** Drop a PDF at `assets/resume.pdf` (the "Résumé" button and "Download résumé" button both link there).
2. **Add your GitHub link.** In `index.html`, find the `<!-- CONTACT -->` section and replace `github.com/your-username` with your real GitHub profile URL (email and LinkedIn are already filled in).
3. **Add bullet points to any Experience role** you'd like more detail on — copy the `<ul class="timeline-points">` block from the Mastek or Inscripts entry into any other `<div class="timeline-item">`.

## Publish it on GitHub Pages

### Option A — user/organization site (`your-username.github.io`)
1. Create a new GitHub repo named exactly `your-username.github.io`.
2. Push this folder's contents to the `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/your-username/your-username.github.io.git
   git push -u origin main
   ```
3. Your site will be live at `https://your-username.github.io` within a minute or two — no extra configuration needed.

### Option B — project site (any repo name)
1. Push this folder to any repo, e.g. `portfolio`.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to "Deploy from a branch," pick `main` and `/ (root)`, then save.
4. Your site will be live at `https://your-username.github.io/portfolio/`.

## Local preview

Just open `index.html` in a browser, or serve it locally:
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.

## Structure

```
index.html
assets/
  css/style.css
  js/script.js
  resume.pdf   ← add this yourself
```
