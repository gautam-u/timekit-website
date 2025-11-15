# TimeKit Website

Official marketing website for TimeKit - Professional Time Tracking for Freelancers.

## Overview

This is a Jekyll-based static website hosted on GitHub Pages. It provides information about TimeKit, pricing, features, privacy policy, and terms of service.

## Structure

```
TimekitWebsite/
├── _layouts/
│   └── default.html          # Main layout template
├── assets/
│   ├── screenshots/          # App screenshots
│   └── app-icon.png          # App icon
├── index.md                  # Homepage
├── privacy-policy.md         # Privacy Policy page
├── terms.md                  # Terms of Service page
├── support.md                # Support page
├── _config.yml               # Jekyll configuration
└── README.md                 # This file
```

## Features

- Responsive design
- Professional layout
- Privacy Policy & Terms of Service
- Support page with FAQ
- App Store download links
- Feature showcase

## Local Development

### Prerequisites
- Ruby 2.7 or higher
- Jekyll 4.0 or higher

### Setup

1. Install dependencies:
```bash
gem install bundler jekyll
bundle install
```

2. Run local server:
```bash
bundle exec jekyll serve
```

3. Visit `http://localhost:4000/timekit-website/`

## Deployment

This website is automatically deployed to GitHub Pages when changes are pushed to the main branch.

**Live URL**: https://gautam-u.github.io/timekit-website/

## Content Updates

### Privacy Policy
Edit `privacy-policy.md` to update privacy policy content.

### Terms of Service
Edit `terms.md` to update terms of service content.

### Homepage
Edit `index.md` to update homepage content and features.

### App Store Link
Update `appstore_link` in `_config.yml` when app is published.

## Legal Requirements

✅ Privacy Policy (GDPR, CCPA compliant)
✅ Terms of Service
✅ Support page with contact information
✅ Restore Purchases link in app

## Contact

For website issues or suggestions, contact:
- Email: support@timekitapp.com
- GitHub: @gautam-u

---

**TimeKit** - Track time. Build your kit.
