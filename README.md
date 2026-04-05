# csce412-project4-site

Personal multi-page static website for CSCE 412 Project 4.

## Current Site Structure

- index.html
- about.html
- projects.html
- experience.html
- skills.html
- contact.html
- assets/css/styles.css
- assets/js/main.js
- assets/img/*
- docs/*

## Before Deployment

1. Add your resume PDF to:
   - assets/resume/Minh-Nguyen-Resume.pdf
2. Replace headshot placeholder with your real photo:
   - assets/img/headshot-placeholder.svg (or update image path in HTML)
3. Review and finalize copy in all pages.

## Local Preview

Open index.html directly in browser, or run a local server:

```bash
python3 -m http.server 8080
```

Then visit:

- <http://localhost:8080>

## Deployment and Deliverables

Use these docs:

- docs/project4-step-by-step-guide.md
- docs/project4-documentation-template.md

These documents cover:

- AWS S3 setup
- Route 53 and Namecheap DNS delegation
- ACM certificate issuance
- CloudFront HTTPS distribution
- Required documentation and demo checklist
