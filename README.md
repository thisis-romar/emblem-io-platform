# Emblem-NLP.iO Platform

Enterprise AI Orchestration & Multimedia Generation Platform

## Overview

Emblem.io is an enterprise platform that integrates ChatGPT, Claude, Midjourney, and 150+ production APIs through Microsoft's Model Context Protocol. The platform eliminates AI rework cycles and provides consistent, brand-aligned multimedia generation with measurable ROI.

## Project Structure

```
emblem-io-platform/
├── index.html                 # Main landing page (emblem.io platform overview)
├── assets/                    # Static assets (images, CSS, JS)
├── docs/                      # Documentation and guides
│   └── GMAIL-BACKGROUND-IMAGES-IMPLEMENTATION-GUIDE.md
├── email-templates/           # Email campaign templates
│   ├── emblem-io-email-campaign.html
│   ├── emblem-io-email-gmail-optimized.html
│   └── emblem-io-email-maximum-compatibility.html
└── README.md                  # This file
```

## Key Features

- **Enterprise AI Orchestration**: Production-ready MCP orchestration for multimedia generation at scale
- **Multi-Modal Integration**: ChatGPT, Claude, Midjourney, and 150+ APIs in unified workflow
- **Brand Consistency**: Eliminates AI lottery with consistent, brand-aligned output
- **Measurable ROI**: Analytics and tracking for AI-generated content performance
- **Gmail-Compatible Email Templates**: Fully tested email campaigns with working background images

## Email Templates

The `email-templates/` directory contains Gmail-compatible email templates:

- **emblem-io-email-maximum-compatibility.html**: Gmail-optimized version with working background images via Google Drive
- **emblem-io-email-gmail-optimized.html**: Table-based structure for maximum email client compatibility
- **emblem-io-email-campaign.html**: Standard campaign template

### Gmail Background Images Solution

We've solved the Gmail image blocking issue using:
- Google Drive hosting with `lh3.googleusercontent.com` URLs
- Table-based HTML structure instead of div-based
- VML fallback for Outlook compatibility
- Inline critical styles for maximum compatibility

See `docs/GMAIL-BACKGROUND-IMAGES-IMPLEMENTATION-GUIDE.md` for complete implementation details.

## Live Demo

Once deployed on GitHub Pages, the platform will be available at:
- Main site: `https://[username].github.io/emblem-io-platform/`
- Landing page: `https://[username].github.io/emblem-io-platform/index.html`

## Development

### Local Development
1. Clone the repository
2. Open `index.html` in a web browser
3. Edit files as needed

### Email Template Testing
1. Open email templates in web browser for preview
2. Copy HTML content for email composition
3. Test in Gmail composition for compatibility verification

## Documentation

- **Gmail Implementation Guide**: Complete guide for implementing Gmail-compatible background images
- **Email Template Guide**: Instructions for using and customizing email templates
- **Platform Overview**: Detailed information about emblem.io enterprise features

## Technical Specifications

- **Email Compatibility**: Gmail, Outlook, Apple Mail, Yahoo Mail
- **Image Hosting**: Google Drive with public sharing
- **Background Images**: 800x400px optimized for email delivery
- **Text Styling**: High contrast with text-shadow for readability
- **Cross-Client Support**: VML fallback for Outlook desktop

## Contact

For enterprise inquiries and platform access, contact emblem.io team.

---

*Last Updated: September 2025*
*Email Templates Tested: Gmail Web, Gmail Mobile, Outlook Desktop*