# Portfolio — Nawfel Rahmani

Portfolio personnel de Nawfel Rahmani, data analyst et développeur web.
Site statique, écrit à la main en HTML, CSS et JavaScript. Aucune dépendance, aucun framework, aucun build.

**En ligne :** https://nawfelr.github.io

---

## Ce que contient ce dépôt

| Fichier | Rôle |
|---|---|
| `index.html` | Le site entier — structure, styles et scripts dans un seul fichier |
| `.nojekyll` | Désactive le traitement Jekyll de GitHub Pages |

Le site tient volontairement en un seul fichier : il n'y a ni dépendance externe à charger, ni étape de compilation, ni risque de lien cassé entre ressources. Seules les polices sont appelées depuis Google Fonts.

---

## Fonctionnalités

**Schéma évolutif au défilement.** La section trajectoire affiche un diagramme technique en SVG qui se redessine à chaque étape du parcours : courbe de constantes vitales, application web, chaîne d'analyse, pipeline orchestré, pipeline sécurisé. Piloté par `IntersectionObserver`, sans librairie.

**Bilingue français / anglais.** Bascule instantanée via des attributs `data-fr` et `data-en` sur chaque élément textuel. Aucun rechargement de page.

**Dossiers projets dépliables.** Chaque projet est documenté en quatre temps — problème, données, approche, résultat — dans un élément `<details>` natif, donc accessible au clavier par défaut.

**Feuille de style d'impression.** `Ctrl+P` transforme le site en CV papier : navigation et éléments décoratifs masqués, dossiers projets ouverts, passage en noir sur blanc.

**Accessibilité.** Lien d'évitement, repères sémantiques, états de focus visibles, respect de `prefers-reduced-motion`.

---

## Développement local

Aucune installation nécessaire. Ouvrir `index.html` dans un navigateur suffit.

Pour servir le fichier via HTTP (utile pour tester le comportement réel) :

```bash
python3 -m http.server 8000
```

Puis ouvrir http://localhost:8000

---

## Déploiement

Le site est déployé automatiquement par GitHub Pages à chaque `push` sur la branche `main`.

---

## Stack

HTML5 · CSS3 (variables personnalisées, grid, flexbox) · JavaScript (ES5, sans dépendance) · SVG

---

## Licence

Le code est libre de consultation et de réutilisation à des fins d'apprentissage.
Les contenus rédactionnels, le parcours et les projets décrits restent la propriété de Nawfel Rahmani.
