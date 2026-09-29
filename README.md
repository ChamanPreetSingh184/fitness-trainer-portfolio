# Trainer website

One static page: `index.html` (HTML + CSS + JS inline, no build step, no dependencies).

- Edit name, tagline, WhatsApp number, Instagram, services and photos in the `CONFIG` block near the bottom of `index.html`.
- Photos: see `images/README.md`.
- Preview locally: `python -m http.server 5173` and open http://localhost:5173
- Deploy: import the folder as a new Vercel project. Framework preset "Other", no build command, no output directory.
