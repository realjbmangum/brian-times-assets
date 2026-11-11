# brian-times-assets

Public illustration assets for The Brian Times personal newsletter. Images only, no personal data.

- `hero/hero-YYYY-MM-DD.jpg`: the daily front-page illustration (generated art, not photographs).
- `incoming/*.b64`: a staging area. A file committed here as base64 text is decoded by
  `.github/workflows/decode.yml` into `hero/` and then removed.
