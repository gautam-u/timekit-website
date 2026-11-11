# Workbill Website

Marketing site content for Workbill.

## Overview

This repository contains Jekyll-based marketing content for Workbill, including the homepage copy, support page, privacy policy, and terms of service.

The actual root domain used for universal links and App Store event links is published from the separate `gautam-u.github.io` repository under `/workbill/`.

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

This repository can still build as a project site, but the production Workbill website and universal-link pages now live at:

**Live URL**: https://gautam-u.github.io/workbill/

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
- Feedback: the App Store review page (there is no support mailbox)
- GitHub: @gautam-u

---

**Workbill** - Track time. Send invoices. Get paid.
