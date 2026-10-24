# Stan — Portfolio

Développeur Python, spécialiste automatisation et DevOps. Freelance (Karakuri Studio).
Projets personnels construits et exploités en conditions réelles (CI/CD, services systemd, monitoring), d'abord sur un Raspberry Pi 5 auto-hébergé, en cours de migration vers le cloud.

## Projets

| Projet | Description | Stack | Dépôt |
|---|---|---|---|
| **RecovR** | Pré-recouvrement : suivi des factures clients, contrôle des pièces justificatives, alertes de retard, exports CSV/Excel — déployé sur [recovr.stan-aria.dev](https://recovr.stan-aria.dev) ; connecteurs Chorus Pro / Ariba en feuille de route | Django 4.2, PostgreSQL, allauth, GitLab CI → GitHub, gunicorn/whitenoise | [recovr_software](https://github.com/stan-kempachi/recovr_software) |
| **Photo → Devis** | Un email avec une photo → un devis généré par IA et renvoyé automatiquement | Python stdlib (IMAP/SMTP), API Claude (vision), systemd, n8n | [photo-devis](https://github.com/stan-kempachi/photo-devis) |
| **Karakuri Studio** | Usine de contenu automatisée pour Instagram/TikTok : brief → script → voix → montage → publication, pilotée depuis Discord/Telegram, paiement Stripe, monitoring | Python, n8n, ElevenLabs, FFmpeg, Stripe, Meta/TikTok APIs, Cloudflare Tunnel | privé — *démo sur demande* |
| **ARIA** | Agent autonome et générateur d'applications (Django/Flask/FastAPI + React) à partir d'un prompt, avec validation humaine via Telegram, RAG ChromaDB, proxy multi-apps `*.stan-aria.dev` | Claude API, n8n, LangGraph, ChromaDB, Node.js, Cloudflare | privé — *démo sur demande* |
| **cookiecutter-python-template** | Template de projet Python clé en main : Poetry, pre-commit, CI, structure | Cookiecutter, Poetry | [cookiecutter-python-template](https://github.com/stan-kempachi/cookiecutter-python-template) |

## Parcours professionnel (extraits)

- **BPCE-IT** (2025–) — automatisation SecOps : Cisco XDR, SOAR, workflows SOC (remédiation phishing, quarantaine, notifications), n8n
- **DGFIP** (2022–2025) — intégration SOAR au SOC, 100+ playbooks en production, lead d'une équipe de 3 développeurs, CI/CD GitLab/Jenkins

## Contact

stan@karakuri.studio
