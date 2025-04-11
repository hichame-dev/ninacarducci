# 🚀 Optimisation du site Nina Carducci

## 🎯 Objectif du projet

Ce projet consiste à **auditer, corriger et optimiser un site web existant** pour améliorer :

- ✅ Les performances (vitesse de chargement)
- ✅ Le référencement naturel (SEO)
- ✅ L’accessibilité
- ✅ Les bonnes pratiques de code

Le tout en s’appuyant sur les rapports générés par **Lighthouse**, avec validation via les outils Chrome DevTools et navigateur.

---

## 🧪 Étapes réalisées

- ✅ Analyse des performances via Lighthouse
- ✅ Nettoyage du code HTML / CSS / JS
- ✅ Optimisation des images (formats, poids)
- ✅ Ajout des balises meta SEO
- ✅ Amélioration du contraste et des titres pour l’accessibilité
- ✅ Compression des fichiers CSS et JS
- ✅ Mise en place du fichier `.gitignore`
- ✅ Gestion du workflow Git (`main` / `dev`)

---

## 📊 Score Lighthouse (après optimisation)

| Catégorie       | Score 🚀 |
|------------------|----------|
| Performance      |  🟢  100 |
| Accessibilité    |  🟢  96  |
| SEO              |  🟢  100 |
| Bonnes pratiques |  🟢  100 |

*Tests réalisés en local avec Chrome sur la version optimisée du site.*

---

## 🌐 Lien vers le site optimisé

🔗 [Voir le site en ligne](https://hichame-dev.github.io/ninacarducci/)

---

## 🧰 Stack technique

- HTML5
- CSS3
- JavaScript 
- Google Lighthouse
- Chrome DevTools
- Git & GitHub

---

## 🔀 Workflow Git

| Branche   | Rôle                              |
|-----------|-----------------------------------|
| `main`    | Code en production (version finale stable) |
| `dev`     | Travaux en cours (optimisations, debug)   |
| `feature/x` | Fonctionnalités ou fixes spécifiques    |

---

## 🧑‍💻 Auteur

Développé par **Hichame Dev**  
🔗 [GitHub @hichame-dev](https://github.com/hichame-dev)

---

## ⚖️ Licence

Ce projet est sous licence MIT — libre de l'utiliser, de le modifier et de le partager.


# 📦 Optimisations réalisées sur le site de Nina Carducci

## 1. 🧱 Structure & hiérarchie
- Balise `<title>` ajoutée
- Une seule balise `<h1>` pertinente
- Hiérarchie de titres : `<h2>`, `<h3>`
- Suppression des `<h6>` inutiles, remplacés par `<p>`

## 2. 🔍 Référencement naturel (SEO)
- Meta description ajoutée
- Balises Open Graph et Twitter Card intégrées (hors image)
- Prévision image OG ultérieure

## 3. ♿ Accessibilité
- Libellés "Previous"/"Next" → "Précédent"/"Suivant"
- Liens clarifiés : "À propos" → "À propos de Nina Carducci"
- Attributs `alt` descriptifs sur toutes les images
- `aria-label` sur Instagram et boutons carrousel
- Texte accessible avec `visually-hidden`

## 4. 🖼️ Optimisation des images
- Conversion WebP : nina.png, yoji-iwa.jpg, galerie, slider...
- Redimensionnement : galerie (600x600), carrousel (1440x960)
- Compression qualité 75–90%
- Utilisation des balises `<picture>`
- Suppression de `loading="lazy"` sur l’image LCP
- Préchargement avec `<link rel="preload">`

## 5. 🎠 Carrousel responsive
- Media query dédiée (≤ 1000px)
- Hauteur max à 500px
- Structure Bootstrap conservée
- `width`/`height` dans `<img>` pour éviter CLS

## 6. 🧹 Nettoyage CSS
- Doublons supprimés
- Breakpoints conservés (1180 / 1000 / 650)
- Carrousel intégré proprement dans le CSS responsive

## 7. ⚡ Performances
- Score Lighthouse : 98/100
- LCP et lazy load optimisés
- Réduction forte du poids images (ex : nina.png = 2 Mo → 32 Ko)
- CSS et JS **minifiés**
- Responsive **entièrement retravaillé**