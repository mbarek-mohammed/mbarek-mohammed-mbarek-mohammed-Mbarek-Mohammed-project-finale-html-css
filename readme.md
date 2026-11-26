# Mon Argent, Ma Liberté
 
Site de sensibilisation à la **violence économique** et au **contrôle financier** envers les femmes.
 
> *Her money. Her freedom.* Chaque femme doit pouvoir choisir, travailler et décider de son avenir.
 
## Objectif
 
Aider à reconnaître les signes du contrôle financier, comprendre comment il s'installe, et orienter vers des démarches concrètes et des ressources d'aide.
 
## Pages
 
| Page       | Fichier                        |              Contenu                                           |
|------------|--------------------------------|----------------------------------------------------------------|
| Accueil    | `index.html`                   | Présentation, vidéo « Le prix du silence », pourquoi en parler |
| Comprendre | `public/pages/Comprendre.html` | Les six formes de contrôle, comment ça s'installe              |
| Agir       | `public/pages/Agir.html`       | Premières démarches, FAQ, ressources d'aide (SOS)              |
 
## Technologies
 
- HTML5
- [Tailwind CSS](https://tailwindcss.com/) v4
- [daisyUI](https://daisyui.com/) v5 (menu mobile, accordéon FAQ)
- CSS personnalisé (`style.css`) pour la section vidéo

## Installation
 
```bash
npm install
```
 
## Compiler le CSS
 
Pendant le développement (recompile automatiquement) :
 
```bash
npx @tailwindcss/cli -i ./input.css -o ./public/css/output.css --watch
```
 
Pour une version finale (minifiée) :
 
```bash
npx @tailwindcss/cli -i ./input.css -o ./public/css/output.css --minify
```
 
Ensuite, ouvrez `index.html` dans le navigateur (ou utilisez l'extension *Live Server* de VS Code).
 
## Charte graphique
 
| Couleur    | Code      | Usage                   |
|------------|-----------|-------------------------|
| Orange     | `#ff7a00` | Header, titres, accents |
| Jaune      | `#ffd23f` | Boutons, cartes, ombres |
| Brun foncé | `#2b1200` | Texte, bordures, footer |
| Beige      | `#F5E6D3` | Fond de page            |
 
## Crédits
 
- Vidéo : « Le prix du silence » (YouTube)
- Images : illustrations et visuels du projet
## Auteur
 
Projet réalisé par MBAREK-MOHAMMED — © 2026 Mon Argent, Ma Liberté. Tous droits réservés.