# Farhan Iqbal — Realty Landing Page

Single-page website for Farhan Iqbal, Sales Representative with Property.ca Inc., Brokerage in Toronto.

## Live page

GitHub Pages: <https://calgary007.github.io/Realty_Landing_Page/>

## Files

- `index.html` — the landing page (styles and small scripts are inline)
- `assets/` — business card front, portrait, property.ca logos, favicon

## Content sources

- Contact details and business card front: Farhan Iqbal's business card and Property.ca Inc., Brokerage.
- Client testimonials: Farhan Iqbal's public [Condos.ca profile](https://condos.ca/condo-pros/farhan-iqbal). The eight testimonials are reproduced there and labelled as Condos.ca testimonials on the page.

## Local preview

```powershell
python -m http.server 8080
```

Open <http://localhost:8080>.

## Custom domain

Add the domain under **Settings → Pages → Custom domain** in GitHub. GitHub creates the `CNAME` file in this repository. At the domain registrar, point the apex domain to GitHub Pages with the four GitHub A records and point `www` to `calgary007.github.io` with a CNAME record. Once DNS is verified, enable **Enforce HTTPS**.
