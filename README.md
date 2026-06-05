# Maison Aurielle – Online Store

Shopify-Theme für **Maison Aurielle** (maisonaurielle.net) – feiner Schmuck und zeitlose Uhren aus der Schweiz.

Dieses Repository ist über **Shopify ↔ GitHub Sync** mit dem Store verbunden:
Änderungen am `main`-Branch werden automatisch mit dem verbundenen Theme im Shopify-Admin synchronisiert.

## Basis

Das Theme basiert auf [Shopify Dawn](https://github.com/Shopify/dawn) und wurde auf die Marke Maison Aurielle angepasst.

## Maison-Aurielle-Anpassungen

- **Farbwelt:** warmes Elfenbein/Creme, Espresso-Anthrazit, antikes Champagner-Gold (`config/settings_data.json`)
- **Typografie:** Playfair Display (Headings) + Assistant (Fließtext)
- **Hero-Sektion:** `sections/hero-maison.liquid` + `assets/section-hero-maison.css`
- **Brand-CSS:** `assets/maison-custom.css` (eingebunden in `layout/theme.liquid`)
- **Startseite:** `templates/index.json` (Hero → Sommer-Favoriten → Kategorien → Markengeschichte → Uhren → Vorteile → Halsketten → Newsletter)
- **Header/Footer:** `sections/header-group.json`, `sections/footer-group.json`
- **Sprache:** Deutsch als Standard-Locale (`locales/de.default.json`)

## Struktur

```
assets/      CSS, JS, Bilder
config/      Theme-Einstellungen (settings_schema.json, settings_data.json)
layout/      theme.liquid, password.liquid
locales/     Übersetzungen (Standard: de)
sections/    Sektionen inkl. Section-Groups (header/footer)
snippets/    Wiederverwendbare Snippets
templates/   Seiten-Templates (index, product, collection, …)
```
