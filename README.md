# 📐 Mémos Maths Cycle 3 (CM1 / CM2)

Affiches de référence et mémos synthétiques de mathématiques conformes aux programmes officiels de l'Éducation Nationale pour le **Cycle 3 (CM1 / CM2)**.

Chaque fiche est conçue en **HTML5 / CSS3 / SVG vectoriel** pur pour tenir rigoureusement sur **une seule page A4 portrait**, prête pour l'impression ou l'affichage en classe et dans le classeur de référence.

---

## 📑 Sommaire des Fiches

| Fiche | Thème | Fichier | Contenu clé |
| :--- | :--- | :--- | :--- |
| **N° 1** | **Nombres & Calculs** | [`memo_1_nombres_calculs.html`](memo_1_nombres_calculs.html) | Tableau de numération jusqu'au milliard, fractions (disques & barres), décimaux, 4 opérations posées avec retenues (+1), division euclidienne & décimale, astuces de calcul mental. |
| **N° 2** | **Grandeurs & Mesures** | [`memo_2_grandeurs_mesures.html`](memo_2_grandeurs_mesures.html) | Tableaux de conversion (longueurs, masses, contenances) & règle d'or, formules en toutes lettres (carré, rectangle, triangle, cercle), tableau d'aires à 2 colonnes, volumes 3D, durées & horloge 24h, angles et utilisation du rapporteur. |
| **N° 3** | **Espace & Géométrie** | [`memo_3_espace_geometrie.html`](memo_3_espace_geometrie.html) | Notations géométriques $[AB], (d), \perp, //$, classification des triangles et quadrilatères, cercle et diamètre, symétrie axiale, solides 3D avec perspectives, patrons dépliés et formule d'Euler ($F+S=A+2$). |
| **N° 4** | **Organisation de Données & Proportionnalité** | [`memo_4_organisation_proportionnalite.html`](memo_4_organisation_proportionnalite.html) | 4 outils graphiques (tableau double entrée, bâtons, courbe, camembert), coefficient de proportionnalité, règle de trois, produit en croix, repérage graphique $(0,0)$, 5 pourcentages repères, soldes/hausses, échelles et triangle magique vitesse $D=V\times T$. |

Le portail central [`index.html`](index.html) rassemble les liens vers toutes les fiches avec des aperçus synthétiques.

---

## 🖨️ Conseils d'Impression (A4 Portrait)

Pour un rendu optimal lors de l'impression :

1. Ouvrez la fiche souhaitée dans votre navigateur (Chrome, Firefox, Safari ou Edge).
2. Cliquez sur le bouton orange **« 🖨️ Imprimer la Fiche »** en haut de page (ou raccourci `Cmd + P` / `Ctrl + P`).
3. Dans la boîte de dialogue d'impression :
   - **Destination** : Enregistrer au format PDF ou choisir votre imprimante.
   - **Format** : A4.
   - **Orientation** : Portrait.
   - **Échelle** : 100% (ou « Adapter à la zone d'impression »).
   - **Marges** : Minimum ou Aucune (les marges de 6 mm sont déjà intégrées en CSS).
   - **Options d'arrière-plan** : **Cocher impérativement « Graphismes d'arrière-plan »** (pour imprimer les aplats de couleur et badges).

---

## 🚀 Utilisation en Local

Vous pouvez ouvrir directement les fichiers `.html` dans n'importe quel navigateur, ou lancer un serveur local :

```bash
# Lancer un serveur local léger
python3 -m http.server 8000
```

Puis ouvrez dans votre navigateur : [http://localhost:8000](http://localhost:8000)

---

## 🛠️ Caractéristiques Techniques

- **100% Autonome** : Aucun framework lourd, aucune dépendance externe obligatoire hors police Google Fonts (Nunito).
- **Graphismes Vectoriels SVG** : Schémas géométriques, horloges, patrons 3D et diagrammes parfaitement nets à toute résolution d'impression.
- **CSS Print-Ready** : Règles `@page { size: A4 portrait; margin: 6mm; }` et `@media print` garantissant le respect d'une page unique sans débordement.
- **Accessibilité & Pédagogie** :
  - Codes couleur harmonieux par domaine mathématique.
  - Formules écrites en toutes lettres pour éviter toute confusion chez les élèves de Cycle 3.
  - Exemples concrets et astuces de calcul mental intégrés.

---

## 📄 Licence

Ce matériel est mis à disposition pour un usage éducatif, personnel et en classe.
