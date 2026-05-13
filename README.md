<div align="center">

# MDNX Finance

**Plateforme de simulateurs financiers pour la France — fiscalité 2026.**

[![Site](https://img.shields.io/badge/Site-finance.mdnx.org-00ed64?style=flat-square&logo=safari&logoColor=001e2b)](https://finance.mdnx.org)
[![Contact](https://img.shields.io/badge/Contact-contact%40mdnx.org-001e2b?style=flat-square&logo=maildotru&logoColor=white)](mailto:contact@mdnx.org)
[![Status](https://img.shields.io/badge/Statut-En%20production-00ed64?style=flat-square)](https://finance.mdnx.org)

</div>

---

Simulateurs financiers France 2026 — salaire, impôts, immobilier, épargne, aides. Assistant IA inclus.

## Présentation

**MDNX Finance** regroupe **57 simulateurs financiers gratuits** couvrant la fiscalité française, le salaire, l'immobilier, l'épargne et les aides sociales — tous mis à jour avec les barèmes officiels **2026 (revenus 2025)**.

Le site est accessible librement, sans inscription, sans collecte de données personnelles. Les calculs s'effectuent localement dans le navigateur dès que c'est techniquement possible.

🔗 **Site en ligne :** https://finance.mdnx.org
📧 **Contact :** contact@mdnx.org

---

## Les 5 piliers

| Pilier | Exemples de simulateurs |
|---|---|
| **Salaire & emploi** | Brut → net, net après impôt, comparateur de salaires, solde de tout compte, coût employeur, rupture conventionnelle |
| **Impôt & fiscalité** | IR 2026, prélèvement à la source, PER, dons, frais réels, plus-values mobilières et immobilières |
| **Immobilier** | Capacité d'emprunt, mensualités, frais de notaire, rendement locatif, PTZ 2026, LMNP, achat vs location |
| **Épargne & investissement** | Livret A, LDDS, LEP, PEA, assurance-vie, ETF long terme, intérêts composés, retraite anticipée |
| **Aides & droits sociaux** | Prime d'activité, APL, RSA, AAH, ASPA, allocations familiales, bourse CROUS |

---

## Ce qui démarque MDNX Finance

- **Assistant IA pédagogique** — MDNX Assistant t'oriente vers le bon simulateur et t'explique les résultats, en français, sans jargon.
- **Calculs 2026 à jour** — Barèmes URSSAF, AGIRC-ARRCO, PMSS, SMIC, IR, PER, dons : tout est sourcé.
- **Sources officielles citées** — Chaque simulateur renvoie vers impots.gouv.fr, service-public.fr, urssaf.fr, anil.org, etc.
- **100 % gratuit, sans inscription** — Pas de paywall, pas de freemium.
- **Confidentialité par design** — Les données saisies dans les simulateurs ne sont ni stockées ni transmises.
- **Compliance** — Disclaimer par niveau de risque, formulations prudentes, transparence sur la monétisation.

---

## Captures d'écran du site MDNX Finance

<img width="2748" height="1530" alt="image" src="https://github.com/user-attachments/assets/30d60428-0da5-488e-bc30-8239e8d0b395" />

<img width="3096" height="1604" alt="image" src="https://github.com/user-attachments/assets/87dc3d9b-a09f-4b21-84e3-02982607b311" />

<img width="3096" height="1604" alt="image" src="https://github.com/user-attachments/assets/e2bd5df6-da14-4863-87c4-a8880934fb74" />

<img width="2936" height="1482" alt="image" src="https://github.com/user-attachments/assets/c56c96cf-78ee-49f4-8f8b-8af199a145c7" />


<!--
![Accueil — MDNX Finance](docs/screenshots/home.png)
*La page d'accueil avec les 5 piliers et la section assistant IA.*

![Simulateur Salaire brut → net](docs/screenshots/brut-net.png)
*Conversion brut/net avec cotisations URSSAF + AGIRC-ARRCO 2026.*

![Assistant IA](docs/screenshots/chatbot.png)
*MDNX Assistant — guide pédagogique conversationnel.*

![Bons plans financiers](docs/screenshots/parrainage.png)
*Page parrainage transparente — banques en ligne et services partenaires.*
-->

---

## Stack technique

| Couche | Technologie |
|---|---|
| **Frontend** | React 19, Vite, TypeScript, Tailwind CSS v3 |
| **Routing** | React Router v6 |
| **UI** | Radix UI + CVA (shadcn-style, manuel) |
| **Backend API** | Hono, Node.js 22, TypeScript |
| **Streaming** | SSE (Server-Sent Events) via fetch natif |
| **IA** | Claude (Anthropic) via OpenRouter — Haiku 4.5 par défaut, Sonnet 4.6 sur sujets complexes |
| **Rate limiting** | Redis (ioredis) — 5 messages/min, 30/jour par IP |
| **Infrastructure** | Docker, OVH VPS, Cloudflare DNS, Nginx Proxy Manager |
| **Observabilité** | Uptime Kuma |

---

## Roadmap

- [x] 57 simulateurs couvrant les 5 piliers
- [x] Assistant IA pédagogique (MDNX Assistant)
- [x] Page parrainage transparente
- [x] Compliance & disclaimers par niveau de risque
- [ ] Mode comparaison multi-simulateurs
- [ ] Export PDF des résultats
- [ ] Application mobile (PWA)

---

## Statut du code

Le **code source n'est pas publié** pour le moment. Le site, lui, est entièrement accessible et utilisable gratuitement sur https://finance.mdnx.org.

Pour toute question, suggestion d'amélioration, signalement de bug ou demande de simulateur :
📧 **contact@mdnx.org**

---

## Mentions

- Les résultats des simulateurs sont **indicatifs** et ne constituent pas un conseil financier, fiscal, juridique, social ou patrimonial.
- Pour toute décision importante, vérifiez les informations auprès des sources officielles ou d'un professionnel qualifié.
- MDNX Finance peut percevoir une rémunération via certains liens de parrainage (banques en ligne, services de paiement). Cela n'influence jamais les résultats des simulateurs. Voir https://finance.mdnx.org/bons-plans-financiers.

---

<div align="center">

**MDNX Finance** — Édité par Johan SAINT-PRIX — France
© 2026 — Tous droits réservés

</div>
