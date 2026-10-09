[![pages-build-deployment](https://github.com/aberner/devsecops-awareness-talks/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/aberner/devsecops-awareness-talks/actions/workflows/pages/pages-build-deployment)
[![Dependabot Updates](https://github.com/aberner/devsecops-awareness-talks/actions/workflows/dependabot/dependabot-updates/badge.svg)](https://github.com/aberner/devsecops-awareness-talks/actions/workflows/dependabot/dependabot-updates)

# devsecops-awareness-talks
DevSecOps Awareness Talks is a collection of presentations designed to raise awareness about security in modern software development and delivery processes.

## 🎯 About

This repository contains a simple reveal.js presentation about DevSecOps principles and practices.

## 🚀 Getting Started

### View the Presentation

Simply open `index.html` in your web browser to view the presentation.

**Option 1: Local File**
```bash
# Open directly in your browser
open index.html  # macOS
xdg-open index.html  # Linux
start index.html  # Windows
```

**Option 2: Local Web Server**
```bash
# Using Python 3
python3 -m http.server 8000

# Then open http://localhost:8000 in your browser
```

**Option 3: Using Node.js**
```bash
# Install http-server globally (one time)
npm install -g http-server

# Run server
http-server -p 8000

# Then open http://localhost:8000 in your browser
```

## 📖 Navigation

- **Next Slide**: Arrow keys (→ or ↓), Space bar
- **Previous Slide**: Arrow keys (← or ↑)
- **Overview Mode**: Press `ESC` or `O`
- **Speaker Notes**: Press `S`
- **Fullscreen**: Press `F`

## Working with GitHub in Visual Studio Code

Open `github-vscode.html` directly or select **Working with GitHub in Visual Studio Code** on the landing page. The 12-slide beginner presentation covers Git/GitHub concepts, everyday VS Code use, company practices, Azure delivery, and one complete practical example.

The one-hour session reserves **20 minutes for the introduction, 30 minutes for a live demo, and 10 minutes for recap and questions**. Each slide includes timed speaker notes and the demo slide includes a walkthrough. Press `S` for presenter view; use a local web server and allow the speaker-view popup.

### Presenter preparation

- Replace the bracketed prompts on the company and Azure slides with confirmed internal details: organization and access contact, approved sign-in, branch rules, reviewers, required checks, merge permissions, release approvals, support owner, and demo resources. These prompts are not assertions about company policy.
- Confirm the Azure directory/tenant, subscription, resource group, app service/resource type, test URL, pipeline, trigger, and deployment environment. The deck describes a generic delivery path; adapt it to your actual GitHub Actions, Azure DevOps, or other approved pipeline.
- Prepare Git and VS Code, company-approved authentication, repository access, and access to the non-production Azure resources. A GitHub Pull Requests extension is optional; the browser works for PRs.
- Rehearse a welcome-heading change in an **existing approved demo app** with working checks and deployment. This presentation repository's GitHub Pages hosting is not the Azure demo app.
- Have an authorized reviewer and any release approver available. Do not bypass protections or deploy to production for the demonstration.
- Prepare a completed demo PR/run and sanitized screenshots as a clearly labeled fallback. Hide credentials and customer data, and ensure no secrets appear in code, logs, or the portal views you share.
- Share the internal onboarding guide, practice repo, rules, and help contact at the end. Internet access is needed for the CDN-hosted reveal.js assets and online demonstration.

## 🎨 Features

- Clean, responsive design
- Code syntax highlighting
- Smooth slide transitions
- Speaker notes support
- Touch/swipe navigation on mobile devices

## 📝 License

See LICENSE file for details.
