# kelly-connemara-research

The **Kelly Story** — a public history of the Ó Ceallaigh (Kelly) surname and the
Connemara Kelly maternal line, with a password-protected family tree.

This repository is a **deploy target**. Its content is mirrored automatically from the
`kelly-public-site/` folder of the private research project by a GitHub Actions
workflow on every push — do not edit the HTML here directly; edit it in the source
project and it will sync.

- `index.html` — the public surname history (name, septs, Uí Maine, Connemara)
- `heraldry.html` — the O'Kelly arms, the enfield crest and the motto
- `tree.html` — the family tree, **encrypted client-side (AES-256-GCM)** and shown only
  after a passphrase is entered. No living people are included.

Served via GitHub Pages (and/or Cloudflare Pages).
