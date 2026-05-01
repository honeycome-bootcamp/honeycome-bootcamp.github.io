# honeycome-bootcamp.github.io

Organization-level GitHub Pages policy repository for `honeycome-bootcamp`.

This repository is only used to publish host-level files for:

```txt
https://honeycome-bootcamp.github.io/
```

The certificate PDFs are published from the separate project site:

```txt
https://honeycome-bootcamp.github.io/cert-pages/
```

## GitHub Pages Settings

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/docs`

Do not add the `cert-pages` GitHub App token or certificate publishing workflow to this repository. It should remain a small, manually managed policy repository.

## Files

- `docs/robots.txt`: blocks crawlers from `/cert-pages/`
- `docs/.nojekyll`: disables Jekyll processing
- `docs/404.html`: minimal noindex 404 response

No `docs/index.html` is included. The organization root can remain 404 while still serving `/robots.txt`.
