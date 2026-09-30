# PackLedger — MVP (produit #1 de Merxan)

Outils self-serve de conformité PPWR (Règlement UE 2025/40, applicable depuis le
12/08/2026) pour vendeurs e-commerce : convertit des données de commandes en
registrations EPR/PPWR par pays, volumes par matériau, checklist de conformité et
dossier de preuve téléchargeable.

- **Cahier des charges** : `req-6f5d819108` (master d'idées — rank #1, score 81)
- **Business instance** : `biz-7bb6eed9fe`
- **Statut** : MVP construit, tests en cours → validation humaine avant publication
- **Recherche (2026-09-30)** : PPWR Art. 44-45, registration par pays, marketplaces
  vérifient (Amazon/EBay/Temu/Zalando) ; concurrents = services gérés d'enregistrement
  (Eldris £240-990/pays/an), guides (ppwratlas, circulatepack) — aucun ledger
  CSV→registrations self-serve identifié. Sources : ppwratlas.com, epr.eldris.ai,
  amzbase.com (Règlement (UE) 2025/40).

## Fichiers

- `index.html` — le produit (outil statique, aucun backend, données jamais envoyées)
- `README.md` — ce fichier

## Déploiement (free tier)

GitHub Pages ou Netlify Drop. Aucun secret, aucune donnée serveur — tout est
calculé dans le navigateur.