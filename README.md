# Global Residential — PPC Landing Pages

This repository hosts landing pages for PPC campaigns.

## How to add a new landing page

1. Create a new folder for your campaign (e.g., `cyprus-residency-summer/`)
2. Add your `index.html`, CSS files, images, and any other assets inside that folder
3. Push to the `main` branch
4. Your page will be live within ~30 seconds at: `https://ppc.global-residential.com/your-folder-name/`

## Folder structure

```
/
├── campaign-name/
│   ├── index.html
│   ├── styles.css
│   └── images/
│       └── hero.jpg
├── another-campaign/
│   ├── index.html
│   └── styles.css
└── README.md
```

## Important notes

- Each campaign should be in its own folder
- The main entry point for each campaign should be named `index.html`
- All asset paths (CSS, images, JS) should be **relative** (e.g., `./styles.css`, `./images/hero.jpg`)
- Changes go live automatically when pushed to the `main` branch
