# 🌍 Bulle & Pistache

Le site des contes du monde de la chaîne **Bulle & Pistache** — les plus beaux
contes de chaque pays, chantés en français pour les 2 à 5 ans.

👉 **https://laurentroche-noschool.github.io/bulle-et-pistache/**

## Ce qu'il y a dessus

- **Les contes** — les 8 épisodes publiés, qui renvoient vers YouTube
- **La carte** — d'où vient chaque conte, avec son monument
- **À la suite** — la playlist pour enchaîner les 8 contes
- **À lire** — les 8 contes en prose et en chanson, 84 pages illustrées
- **L'histoire** — pourquoi cette chaîne, et les deux guides
- **Les personnages** — 9 fiches
- **Les morales** — expliquées, avec une question à poser à l'enfant

## Comment le mettre à jour

Le site tient dans **un seul fichier**, `index.html` : tout est embarqué,
images comprises. Pas de build, pas de dépendances.

```bash
git add index.html && git commit -m "mise à jour du site" && git push
```

GitHub Pages republie automatiquement en une minute.
La source de travail est dans le projet, sous `Bulle-et-Pistache/11_Site_Internet/`.

## Brancher un nom de domaine

Settings → Pages → Custom domain : saisir le domaine (par exemple
`bulleetpistache.fr`), puis créer chez le registrar un CNAME vers
`laurentroche-noschool.github.io`. Le nom du compte disparaît alors de l'adresse.

---
🎬 La chaîne : https://www.youtube.com/@bullepistache
