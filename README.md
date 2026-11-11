# Permis BE — théorie du permis B (Belgique)

Application web d'entraînement à l'examen théorique du permis B en Belgique (règles en vigueur en novembre 2026).
Fichiers statiques (HTML, CSS, JavaScript), sans dépendance ni étape de build, fonctionnant hors ligne et installable sur téléphone.

**En ligne :** https://jpdev-create.github.io/Permis-be/

## Contenu
- 399 questions expliquées (avec piège et référence), filtrées par Région (Wallonie, Bruxelles, Flandre)
- Questions générées à l'infini : carrefours de priorité résolus par un moteur de règles, panneaux, vitesses par Région, distances, barème
- 79 panneaux belges dessinés en SVG
- Examen blanc de 50 questions au barème réel (−1 / −5 pour une faute grave, 41/50 pour réussir), avec correction détaillée
- Perception des risques : 10 scènes animées, sur le principe du TPR wallon
- Révision espacée des erreurs, carnet d'erreurs, défi du jour, trophées, statistiques, historique
- Livre des règles en 22 chapitres, avec recherche

La progression est enregistrée dans le navigateur (export / import possible dans les Réglages).

## Mise en ligne
GitHub → *Settings → Pages* → Source : **Deploy from a branch**, branche `main`, dossier `/ (root)`.

## Fichiers
| Fichier | Rôle |
|---|---|
| `index.html`, `css/app.css` | Page et styles (clair / sombre) |
| `js/app.js` | Application : écrans, sessions, révision, statistiques |
| `js/questions.js`, `js/questions2.js` | Banque de questions |
| `js/gen.js` | Générateurs de questions |
| `js/signs.js` | Panneaux et schémas de carrefour en SVG |
| `js/rules.js`, `js/lessons.js` | Livre des règles et fiches |
| `js/tpr.js` | Scènes de perception des risques |
| `sw.js`, `manifest.webmanifest` | Fonctionnement hors ligne et installation |

Application d'entraînement indépendante, non officielle. En cas de doute, la référence reste le texte légal.
