# TP interactifs — Parcours Pix (Formip)

Simulateurs HTML autonomes pour les Travaux Pratiques du cours Thinkific
« Développez vos Compétences Numériques & Cybersécurité – Certification Pix ».

## Comment c'est utilisé
Chaque TP est un dossier auto-suffisant `tp/<slug>/index.html`, embarqué dans une
leçon **Multimédia** de Thinkific via « Use externally hosted content » (URL).
Le simulateur signale la réussite au lecteur via `postMessage('show_complete','*')`
→ la leçon se valide automatiquement.

## Servir le contenu (https, compatible iframe Thinkific)
- **GitHub Pages** : `https://<owner>.github.io/<repo>/tp/<slug>/`
- **jsDelivr (CDN, repo public)** : `https://cdn.jsdelivr.net/gh/<owner>/<repo>@<branche>/tp/<slug>/index.html`

## TP disponibles
- `tp/gmail/` — Simulateur « Nouveau message » Gmail (rédiger un e-mail pro, validation à l'envoi).
