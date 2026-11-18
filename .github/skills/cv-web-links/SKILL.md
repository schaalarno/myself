---
name: cv-web-links
description: 'Use when editing CV contact or reference links, contact data in index.html, or generating the CV PDF. Keep all required contact details in the PDF and web links in the designated sections.'
---

# CV Web Links

Use this workflow when editing CV contact or reference details, external links, or PDF output.

1. Keep external website links in the public CV only in the Contact block (`.contact-list`) or References block (`#reference .reference-contact`). Preserve internal navigation and asset links.
2. Read [`contact-details.local.html`](./contact-details.local.html) before generating the PDF. Include every listed applicant and reference detail in the matching PDF section, preserving visible text and the `mailto:` or `tel:` targets.
3. Keep private email, phone, postal address, and permit details out of the committed `index.html`. Add them only to the local print source, then remove any temporary private markup from `index.html` after exporting.
4. This checklist contains personal information and is intentionally ignored by Git. Never stage or force-add it, and do not copy it into committed documentation.
5. Keep Contact and References links visible in print. Generate `CV.pdf` locally with Edge print-to-PDF, verify the applicant and reference details in the resulting PDF, and keep the PDF ignored by Git.
