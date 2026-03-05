# LawrenceBlankenship.com — Portfolio

Live Site: https://lawrenceblankenship.com

## Purpose
This repository contains the source code for my personal developer portfolio website.  
It highlights my background, technical skills, and software projects.

## Tech Stack
- HTML5
- CSS3
- JavaScript
- Git
- GitHub
- GitHub Pages (hosting)

## Architecture Overview

Repository structure:

TreyBlankenship.github.io
│
├── index.html
├── README.md
├── CNAME
└── assets
    ├── css
    └── js

index.html contains the main portfolio sections:
About, Skills, and Projects.

assets contains styling and supporting files.

The CNAME file configures the custom domain.

## Deployment

This site is deployed using GitHub Pages.

Deployment flow:

Local Development  
→ Feature Branch  
→ Pull Request  
→ Merge to main  
→ GitHub Pages Auto Deploy

Production URL:

https://lawrenceblankenship.com

## Local Development

Clone the repository:

git clone https://github.com/TreyBlankenship/TreyBlankenship.github.io.git

Then open index.html in your browser.

## Workflow Rules

No direct pushes to main.

Required workflow:

Feature Branch  
→ Commit  
→ Push  
→ Pull Request  
→ Merge

Example:

git checkout -b feature/example  
git commit -m "example change"  
git push origin feature/example

## License

MIT License