# Staff Portal — Guernsey Yacht Club

A single static page (`index.html`) listing every event booking page and
admin tool the club has live, with a short description of what each one
does and links to the staff-only sub-pages inside it (booking form,
admin/manage page, kitchen sheet, etc.).

No build step, no backend — it's just a directory page. To add a new
event site once it's live, add a card to the relevant section in
`index.html` following the existing pattern.

## Deploying

Push to Netlify (Netlify UI "Import from Git", or `netlify deploy --prod`
with the Netlify CLI). The publish directory is the repo root, as set in
`netlify.toml` — no build command needed.
