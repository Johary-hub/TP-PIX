# Instructions pour Claude Code — repo TP Pix

Ce dossier contient des simulateurs HTML pour les TP du cours Pix Formip.
Les fichiers sont produits dans Cowork puis poussés ici par Claude Code.

## Rôle de Claude Code
1. Committer et pousser les fichiers ajoutés/modifiés sous `tp/`.
2. Ne JAMAIS committer de secret (token, clé). Vérifier `git status` avant push.
3. Après push, rappeler l'URL publique de chaque TP modifié (voir README).

## Conventions
- 1 TP = 1 dossier `tp/<slug>/index.html`, autonome (CSS/JS inline, pas de build).
- Chaque simulateur émet `window.parent.postMessage('show_complete','*')` à la réussite
  et `'hide_complete'` au chargement (gating de complétion Thinkific).
- Commits : message clair, ex. `tp(gmail): consigne 4 collègues en Cci + validation`.

## Commandes type
```
git add tp/
git commit -m "tp(<slug>): <description>"
git push origin <branche>
```
