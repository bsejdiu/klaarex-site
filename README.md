# klaarex.com

Website of Klaarex – deutschsprachiger Kundenservice aus Prishtina. One static page, no build step.

- `index.html` – the whole site. Names, phone numbers, links and the contact-form endpoint live in the `CONFIG` block at the bottom of the file.
- `404.html` – not-found page
- `vercel.json` / `netlify.toml` – security headers and redirects (picked up automatically by the host)
- `robots.txt`, `sitemap.xml` – search engines

## Deploy

Connected to Vercel: every push to `main` goes live on https://klaarex.com.

## Before launch

1. Fill the `CONFIG` block (founders, phones, Calendly, LinkedIn, ARBK number) and the Impressum/Datenschutz placeholders.
2. Create a form at formspree.io and paste its URL into `CONFIG.formEndpoint`.
3. Add `og.png` (1200×630) to the repo root for link previews.
4. Create the mailboxes kontakt@klaarex.com and jobs@klaarex.com.
