# Anu.dev — Meftahul Jannati Anonna's Portfolio

Personal portfolio site for Meftahul Jannati Anonna — CSE undergrad at IUT, AI Automation Engineer, and research collaborator. Built with React + Vite.

**Live:** https://meftahul-anu13.github.io/Anu.dev/

## Sections

About · Experience · Research (publications & ongoing work) · Projects · Skills · Achievements · Education · Contact

## Tech Stack

- React 19 + Vite, plain CSS (no UI framework)
- [Web3Forms](https://web3forms.com/) for the contact form and CV/CGPA unlock flows
- QuickEmailVerification (via CORS proxy) with AbstractAPI as fallback, for email validation

## Getting Started

```bash
npm install
npm run dev     # local dev server
npm run build   # production build to dist/
```

## Environment Variables

Create a `.env` file with:

```
VITE_WEB3FORMS_ACCESS_KEY=
VITE_QUICKEMAILVERIFICATION_API_KEY=
VITE_ABSTRACT_EMAIL_API_KEY=
```

## Deployment

Auto-deploys to GitHub Pages via GitHub Actions (`.github/workflows/deploy.yml`) on every push to `main`.
