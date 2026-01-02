# Portfolio personnel — Yankey Dev

Site portfolio simple présentant : à propos, compétences, projets, contact et un bouton "m'embaucher".

## Description
Site statique HTML/CSS (Bootstrap léger) pour présenter votre travail, compétences et moyens de contact. Conçu pour être responsive et facile à personnaliser.

## Sections
- À propos — présentation courte
- Compétences — listes/technos
- Projets — captures, descriptions et liens
- Contact — email / formulaire
- M'embaucher — CTA visible dans l'en-tête

## Technologies
- HTML5
- CSS (style.css)
- Bootstrap (css/bootstrap.min.css)
- Images stockées dans le dossier `image/`

## Installation locale (Windows)
1. Ouvrir le dossier du projet dans VS Code.
2. Ouvrir un terminal (PowerShell) et lancer un serveur simple :
   - Avec Python installé :
     ```powershell
     py -3 -m http.server 8000
     ```
     puis ouvrir `http://localhost:8000` dans le navigateur.
   - Ou installer l'extension Live Server et cliquer sur "Go Live" dans VS Code.
3. Ouvrir [index.html](http://_vscodecontentref_/0) directement pour un aperçu local sans serveur.

## Structure du projet
- [index.html](http://_vscodecontentref_/1) — page principale
- css/
  - bootstrap.min.css
  - style.css
- image/ — logos, hero, vignettes de projets
- [README.md](http://_vscodecontentref_/2) — (ce fichier)

## Personnalisation rapide
- Modifier le texte : ouvrir [index.html](http://_vscodecontentref_/3) et remplacer les contenus dans les balises `<h1>`, `<p>`, etc.
- Changer le logo : remplacer [logo.png](http://_vscodecontentref_/4) ou modifier la balise `<img>` de `.logo`.
- Changer l'image principale : remplacer [code.jpg](http://_vscodecontentref_/5) ou modifier le chemin dans [index.html](http://_vscodecontentref_/6).
- Couleurs et styles : éditer [style.css](http://_vscodecontentref_/7) (ex. `.embaucher`, `.developper`).
- Ajouter un projet : ajouter une section/vignette dans [index.html](http://_vscodecontentref_/8) et placer l'image dans [image](http://_vscodecontentref_/9).

Exemple pour remplacer le hero :
```html
<img src="image/mon-hero.jpg" alt="coding" />
