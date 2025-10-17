# ERP System — Phase 1 Wireframes

This repository contains static HTML wireframes for Phase 1. There is no JavaScript in the pages (per scope); basic inline CSS only.

## 🌐 Live Demo

**GitHub Pages:** [View Live Site](https://[username].github.io/ERP-Wireframes/)

The site is automatically deployed to GitHub Pages when changes are pushed to the main branch.

## Files

- `index.html` — Homepage (Login page) - Main entry point for GitHub Pages
- `login_wireframe.html` — Login page with Email, Password, Login, Forgot Password, Verify Email.
- `reset_password_wireframe.html` — Reset password page with email input and send button.
- `change_password_wireframe.html` — Change password page with new/confirm password fields.
- `account_locked_wireframe.html` — Account locked notification page with support contact.
- `dashboard_wireframe.html` — Dashboard skeleton with Header, Footer, and stackable panels.
- `admin_wireframe.html` — System Administration skeleton with Companies/Users tables and buttons.
- `mock/` (optional) — Minimal Node static server and example JSON fixtures.

## Preview

### Online (GitHub Pages)

- Visit the live site: [https://[username].github.io/ERP-Wireframes/](https://[username].github.io/ERP-Wireframes/)

### Local Development

- Option 1: Double-click any `.html` file to open in your browser.
- Option 2 (optional): Run a tiny static server for consistent asset serving:
  1. Install Node.js LTS if not present.
  2. In a terminal, run:
     ```bash
     node mock/server.js
     ```
  3. Open `http://localhost:3000/login_wireframe.html`.

## Deployment

This project is automatically deployed to GitHub Pages using GitHub Actions. The deployment workflow:

1. Triggers on push to `main` branch
2. Uses the official `actions/deploy-pages` action
3. Deploys all HTML files to GitHub Pages
4. Site is available at: `https://[username].github.io/ERP-Wireframes/`

### Manual Setup (if needed)

1. Go to repository Settings → Pages
2. Source: GitHub Actions
3. The site will be live at: `https://[username].github.io/ERP-Wireframes/`

## Notes

- No JavaScript is included in the HTML wireframes.
- Company field is omitted in Login for now; a commented placeholder is present for future multi-tenant.
- Target browsers: latest Chrome/Edge.
- Next step: Convert these wireframes to Angular standalone components and hook to mock APIs.
