# Directives et Invariants du Projet : Mémos Maths CM1/CM2 (A4 Portrait)

Ce projet fournit des affiches de mathématiques pédagogiques bilingues (Français Cycle 3 et Chinois 小学数学) conçues en HTML5/CSS3/SVG pur et pré-compilées en PDF.

## 1. Règle d'or : Format A4 Strict (1 Page Unique)
- Toute fiche (HTML et PDF) doit impérativement tenir sur **une seule page A4 portrait**.
- Dimensions du conteneur imprimable : `width: 198mm; height: 285mm; max-height: 285mm; overflow: hidden;`.
- Règle `@page` : `size: A4 portrait; margin: 6mm;`.
- Propriétés obligatoires : `-webkit-print-color-adjust: exact; print-color-adjust: exact; page-break-inside: avoid;`.
- Tout débordement sur une 2e page à l'impression est considéré comme un bug critique.

## 2. Validation systématique des exports PDF
- Après toute modification d'un fichier `.html`, régénérer immédiatement le PDF correspondant avec Google Chrome headless :
  `/Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --headless --disable-gpu --no-pdf-header-footer --print-to-pdf=<dest>.pdf --no-pdf-header-footer file://<source_absolue>.html`
- Vérifier systématiquement que le fichier PDF résultant compte exactement **1 page** :
  `mdls -name kMDItemNumberOfPages <dest>.pdf` (doit afficher `= 1`).

## 3. Parité bilingue et navigation croisée
- Le projet maintient une parité stricte entre les fiches françaises (racine) et chinoises (`zh/`).
- Chaque fiche HTML doit comporter dans sa barre `.screen-actions` :
  - Le bouton d'impression `window.print()`.
  - Le bouton de bascule vers la version correspondante dans l'autre langue.
  - Le lien de retour au portail (`index.html` ou `zh/index.html`).
- Tout ajout ou modification d'une formule/rubrique côté français doit être répercuté côté chinois (en adaptant aux conventions du programme chinois, ex: 万进制, 乘法分配律).
