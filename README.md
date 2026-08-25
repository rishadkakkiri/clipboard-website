# Clipboard — website

Static landing page, privacy policy and support page for the Clipboard iPhone app.
Plain HTML + CSS, no build step.

    index.html      landing page
    privacy.html    privacy policy (use this URL in App Store Connect)
    support.html    support page (use this URL in App Store Connect)
    style.css       all styles
    assets/         app icon and screenshots
    .nojekyll       tells GitHub Pages to serve the files as-is

## Editing

Open `index.html` in a browser to preview, or run a local server:

    python3 -m http.server 8000     # then open http://localhost:8000

Push to `main` and GitHub Pages redeploys within a minute.
