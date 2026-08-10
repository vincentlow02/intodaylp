# Intoday Landing Page

Intoday is a calm, editorial landing page for a research workspace built around long-term thinking. The page introduces how researchers can collect materials, organize context, and preserve connections between ideas over time.

**Deployment target:** [intoday.cc](https://www.intoday.cc/)

## Features

- Responsive desktop, tablet, and mobile layouts
- English, Simplified Chinese, Japanese, Thai, and Malay language options
- Language preference saved locally in the browser
- Product sections for Collect, Organize, and Connect
- Subtle scroll-entry motion with reduced-motion support
- Screenshot lightbox and expandable FAQ items
- Dedicated Privacy Policy and Terms of Service pages
- Minimal editorial design with locally stored product assets

## Project structure

```text
.
├── index.html          # Landing page
├── privacy.html        # Interim Privacy Policy
├── terms.html          # Interim Terms of Service
└── assets/
    ├── collect.png
    ├── connect.png
    ├── hero-workspace.png
    ├── language.svg
    ├── organize.png
    └── plus.svg
```

## Local preview

No build step or package installation is required. Serve the repository with any static HTTP server:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

Opening `index.html` directly also works, although a local server more closely matches production behavior.

## Deployment

The project is a static site and can be deployed directly with Vercel:

1. Import this GitHub repository into Vercel.
2. Select **Other** as the framework preset.
3. Leave the build command empty.
4. Use the repository root (`.`) as the output directory.
5. Connect the `intoday.cc` domain to the Vercel project.

## Legal pages

The included Privacy Policy and Terms of Service are interim pages based on the current landing-page behavior. They should be reviewed against the released product, actual data practices, and applicable launch jurisdictions before production use.

## Contact

- Email: [contact.intoday@gmail.com](mailto:contact.intoday@gmail.com)
- X: [@vdhhhl](https://x.com/vdhhhl?s=21)

## Copyright

© 2026 Intoday. All rights reserved.
