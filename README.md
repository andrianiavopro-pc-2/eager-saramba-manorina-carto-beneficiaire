# EAGER — Cartographie des bénéficiaires

Site statique. Ouvrir `index.html` (accueil national, 11 régions cliquables).

## Mise en ligne (GitHub Pages)
1. Créer un dépôt GitHub et y déposer tout le contenu de ce dossier.
2. Settings → Pages → Source : branche `main`, dossier `/root`.
3. L'URL publique sera `https://<compte>.github.io/<depot>/`.

## Structure
- `index.html` — accueil national
- `regions/<region>.html` — carte interactive par région (districts / communes)
- `pdf/<region>.pdf` — fiche PDF d'une page par région
- `data/<region>.json` — données source agrégées

Données agrégées (aucune donnée nominative). Fond : geoBoundaries, découpage post-réforme 2021.
