# Marnixfeller.nl

Statische website voor drs. Marnix Feller, bedrijfspsycholoog.

## Publiceren via GitHub Pages
1. Maak een nieuwe repository (bijv. `marnixfeller-website`) en upload alle bestanden uit deze map (incl. de map `assets/`).
2. Ga naar **Settings → Pages**, kies branch `main` en map `/ (root)`, en sla op.
3. De site staat daarna op `https://<gebruikersnaam>.github.io/<repo>/`.

## Eigen domein (marnixfeller.nl)
- Het bestand `CNAME` bevat al `marnixfeller.nl`.
- Zet bij je domeinregistrar een DNS-record: `CNAME www → <gebruikersnaam>.github.io` en A-records voor de apex naar GitHub Pages (185.199.108.153 / .109 / .110 / .111).
- Vink in Settings → Pages "Enforce HTTPS" aan.

## Structuur
- `index.html` — de volledige one-page site (geen build stap nodig)
- `assets/` — foto's en klantlogo's
