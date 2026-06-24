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
- `tp/gmail/` — Simulateur de messagerie complet (boîte de réception + rédaction d'un e-mail pro, destinataires en Cci, validation à l'envoi).
- `tp/partage-doc/` — Simulateur Google Drive (partager un dossier au bon niveau d'accès : Éditeur / Commentateur / Lecteur + accès général restreint).
