# busolaogundimu.github.io

Personal research website — built with Jekyll, hosted on GitHub Pages.

## Local development

```bash
gem install bundler
bundle install
bundle exec jekyll serve
# → http://localhost:4000
```

## Deploying

Push to `main`. GitHub Actions builds and deploys automatically.

To enable GitHub Pages:
1. Go to your repo → Settings → Pages
2. Source: **GitHub Actions**
3. Save — next push will trigger a deploy

## Things to update before going live

- [ ] `_config.yml` — add your email
- [ ] `index.html` — update Substack and Medium links with real URLs
- [ ] `index.html` — update LinkedIn URL
- [ ] `index.html` — update email in contact section
- [ ] Writing cards — replace placeholder titles and descriptions with real posts
- [ ] Research items — add paper links when available

## Structure

```
busola-site/
├── _config.yml          # Site settings
├── _layouts/
│   └── default.html     # Base HTML template
├── assets/
│   └── css/main.css     # All styles
├── index.html           # Homepage (all sections)
└── .github/workflows/
    └── deploy.yml       # Auto-deploy on push
```
