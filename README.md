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
- `tp/docs-styles/` — Simulateur Google Docs (structurer avec les styles de titre, collaborer à plusieurs, exporter en PDF).
- `tp/depannage-m5/` — Centre de dépannage (Module 5) : 5 ateliers interactifs sur maquettes Windows 11 (Wi-Fi, Gestionnaire des tâches, sortie audio, recherche d'aide fiable, veille RSS), un par leçon du module.
- `tp/securite-m6/` — Centre de sécurité (Module 6 · CRCN Domaine 4) : 6 ateliers (mot de passe & jauge de force, double authentification 2FA, repérage de phishing, Wi-Fi public/HTTPS/VPN, vie privée & RGPD, sobriété numérique).
- `tp/recherche-m2/` — Rechercher & évaluer l'information (Module 2 · CRCN Domaine 1) : 3 étapes (construire une requête efficace, évaluer la fiabilité des sources, recouper l'information).
- `tp/pixlab-m2/` — Pix Lab « Mène l'enquête » (Module 2) : 4 ateliers (moteur de recherche, juger la fiabilité d'une source, ranger son espace cloud, partager sans exposer les données personnelles).
