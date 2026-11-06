# Personal Site

Source for **[abdelhamidwho.github.io/Abdelhamid-Portfolio](https://abdelhamidwho.github.io/Abdelhamid-Portfolio/)** — my portfolio, work history and writing index.

## What's here

A static multi-page site. No build step, no framework, no dependencies to install.

| Page | Purpose |
|---|---|
| `index.html` | Landing page — intro, selected projects, latest writing |
| `about.html` | Background, work history, education |
| `projects.html` | Full project list |
| `blog.html` | Posts, pulled live from Hashnode |
| `gear.html` | Tools and hardware I work with |
| `chemist-app.html`, `asset-audit.html`, `package-app.html`, `dua-app.html`, `graduation-project.html` | Individual case studies |
| `swipe-action.html`, `net-watcher.html`, `flutter-color-picker.html` | Open-source library pages |

## Stack

Plain HTML, CSS and vanilla JavaScript. [AOS](https://michalsnik.github.io/aos/) for scroll animations, Google Fonts for type, and the Hashnode public API for the blog feed — fetched at runtime, so posts stay current without a redeploy.

## Running locally

Open `index.html` directly, or serve the folder so the blog fetch works against a real origin:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deployment

GitHub Pages, deployed from `main` by `.github/workflows/static.yml`. Pushing to `main` publishes.

## Credits

Built on the [Miller](https://templatesjungle.com/downloads/miller/) template by [TemplatesJungle](https://templatesjungle.com/), used under its free licence — `readme.txt` holds the original licence text, and the footer attribution link is required by it and deliberately kept. All content, copy and case studies are my own.
