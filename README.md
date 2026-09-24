# Jack Stromgren

Built site for Jack Stromgren, DDS (restorative and implant dentist, Willow Glen, San Jose).

Deployment target: https://jackstromgren.netlify.app

All placeholders are populated. Flat .html files, deploy the contents of
this folder to the web root.

## Structure

```
├── index.html
├── about.html
├── contact.html
├── privacy.html
├── dental-anxiety-clinical-issue.html
├── oral-appliance-therapy-sleep-apnea.html
├── executive-protection-dental-plan-pillars.html
├── sitemap.xml
├── robots.txt
├── assets/
│   └── style.css
└── images/
```

All pages are flat .html files at the root. Internal links use relative
paths like `about.html` and `dental-anxiety-clinical-issue.html`.

## Why .html in URLs

This template uses .html-suffixed URLs because they work on every static
host with zero configuration: Netlify, Vercel, Cloudflare Pages, GitHub
Pages, Bunny CDN, AWS S3, Apache, nginx. No edge rules, rewrite rules,
or .htaccess needed.

## Placeholder reference

(See comments in the HTML files. The master prompt also documents every
placeholder.)
