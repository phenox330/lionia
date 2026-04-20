# Product Requirements Document: Landing Page — Formation IA & Agents sur mesure

## Product Vision

**Problem Statement**
Les dirigeants de PME françaises (10-100 salariés) savent qu'ils doivent intégrer l'IA mais ne savent pas par où commencer. 54% des professionnels français n'ont reçu aucune formation IA. Les formations génériques (YouTube, Coursera) ne répondent pas à leurs besoins spécifiques. Ils cherchent un partenaire de confiance qui comprend leurs process métier et les accompagne concrètement.

**Solution**
Une landing page qui positionne l'offre comme un accompagnement IA sur-mesure en 3 niveaux : audit IA (porte d'entrée), formation contextualisée aux process réels du client, et création d'agents IA custom. Le CTA principal est la prise de rendez-vous découverte. L'option souveraineté des données est mentionnée comme bonus, pas comme pilier.

**Success Criteria**
- Nombre de RDV découverte bookés par mois (objectif : 5-10 dans les 3 premiers mois)
- Taux de conversion visiteur → RDV (cible : >5%)
- Leads qualifiés transmis au commercial

## Target Users

### Primary Persona: Le Dirigeant PME
- **Role**: DG / CEO / Gérant de PME (10-100 salariés)
- **Secteurs**: Finance, santé, industrie, cabinets (comptables, avocats, conseil)
- **Pain Points**:
  - Sait que l'IA va transformer son secteur mais ne sait pas comment l'intégrer concrètement
  - A vu des formations génériques qui ne s'appliquent pas à ses process spécifiques
  - Inquiet de prendre du retard sur ses concurrents
  - N'a pas de compétences IA en interne et pas le budget pour un poste dédié
  - Préoccupé par la confidentialité des données de l'entreprise
- **Motivations**: Gagner en productivité, rester compétitif, moderniser sans prendre de risque
- **Goals**: Comprendre en 30 secondes ce que vous proposez, se dire "ces gens comprennent mon métier", booker un appel sans friction

## Core Features (MVP)

### Must-Have Features

#### 1. Hero Section — Proposition de valeur claire
**Description**: Section d'accroche avec headline orientée résultat (pas feature), sous-titre explicatif, et CTA principal "Réserver un appel découverte". Doit répondre à la question "qu'est-ce que vous faites et pourquoi je devrais m'en soucier ?" en moins de 5 secondes.
**User Value**: Le dirigeant pressé comprend immédiatement l'offre et peut agir
**Success Metric**: Taux de scroll > 60%, taux de clic CTA hero > 3%

#### 2. Section Offres — Les 3 niveaux d'accompagnement
**Description**: Présentation des 3 offres de manière progressive :
- **Audit IA** (porte d'entrée) — "On analyse vos process et on identifie vos quick wins IA en 2-3 jours"
- **Formation sur-mesure** — "On forme votre équipe sur VOS process, pas sur des cas génériques"
- **Agents IA custom** — "On construit des assistants IA intégrés à vos outils existants"
Chaque offre a une description courte, les bénéfices clés, et un CTA secondaire.
**User Value**: Le dirigeant comprend le parcours et choisit son point d'entrée (l'audit)
**Success Metric**: Clic sur au moins une offre > 20% des visiteurs

#### 3. Section Confiance — Crédibilité et réassurance
**Description**: Éléments de preuve sociale et de réassurance :
- Logos clients (quand disponibles) ou secteurs servis
- 2-3 résultats chiffrés (même projetés : "30% de temps gagné sur le traitement documentaire")
- Mention légère de la souveraineté : "Option hébergement 100% français disponible pour vos données sensibles"
- Mention des secteurs d'expertise (finance, santé, industrie, cabinets)
**User Value**: Réduit l'anxiété du dirigeant, crée la confiance avant le premier contact
**Success Metric**: Les visiteurs qui scrollent jusqu'à cette section bookent 2x plus de RDV

#### 4. CTA & Booking — Prise de RDV sans friction
**Description**: Intégration d'un outil de booking (Cal.com recommandé, gratuit) permettant de réserver un créneau de 30 min directement depuis la page. Le CTA "Réserver un appel découverte — gratuit, 30 min" est répété 2-3 fois dans la page (hero, après offres, footer).
**User Value**: Zéro friction — pas de formulaire à 10 champs, pas d'email à envoyer, booking direct
**Success Metric**: Ratio CTA cliqué → RDV complété > 50%

#### 5. Section "Pourquoi nous" — Différenciation
**Description**: 3-4 points de différenciation clairs :
- Sur-mesure (pas de formation catalogue, on s'adapte à vos process)
- Approche progressive (audit → formation → agents, à votre rythme)
- Expertise sectorielle (finance, santé, industrie, cabinets)
- Option souveraineté des données (hébergement français, modèles open-source)
**User Value**: Le dirigeant comprend pourquoi choisir vous plutôt qu'un autre
**Success Metric**: Temps passé sur la section > 15 secondes

### Should-Have Features (Post-MVP)
- **Blog / Ressources**: Articles sur l'IA par secteur pour le SEO et la crédibilité
- **Case studies détaillées**: Pages dédiées avec résultats chiffrés par client
- **Calculateur ROI**: Outil interactif "Estimez vos gains avec l'IA"
- **Badge Qualiopi**: Quand la certification sera obtenue (année 2)
- **Chatbot IA**: Démonstration live de vos capacités sur la page

## User Flows

### Primary User Journey
1. Le dirigeant arrive sur la page (via lien envoyé par le commercial, LinkedIn, ou recherche)
2. Il lit le hero — comprend l'offre en 5 secondes
3. Il scroll — découvre les 3 niveaux d'offre, s'identifie à l'audit comme point d'entrée
4. Il voit les éléments de confiance — secteurs, résultats, souveraineté
5. Il clique "Réserver un appel découverte"
6. Il choisit un créneau sur Cal.com — reçoit une confirmation email
7. Le commercial reçoit la notification et prépare l'appel

### Secondary Flow (envoi par le commercial)
1. Le commercial envoie le lien de la landing page par email/LinkedIn au prospect
2. Le prospect consulte la page comme validation ("ces gens sont sérieux")
3. Le prospect revient vers le commercial pour fixer un RDV (ou booke directement)

## Out of Scope (v1)

Explicitly NOT building in MVP:
- Espace client / dashboard
- Paiement en ligne / e-commerce
- LMS / plateforme de formation en ligne
- Blog ou section ressources
- Multi-langue (français uniquement)
- Chatbot ou assistant IA intégré
- Formulaire de contact complexe (le booking suffit)
- Page pricing détaillée (les prix sont discutés en RDV)
- Certification Qualiopi / mentions OPCO (pas encore obtenue)
- Intégration CRM

## Open Questions

- Nom de l'entreprise / marque — à définir avant le dev
- Identité visuelle (logo, couleurs, typo) — à créer ou choisir un template
- Photos / visuels — stock photos ou illustrations ?
- Texte exact du hero (headline + sous-titre) — à itérer
- Outil de booking : Cal.com (recommandé, gratuit) vs Calendly (freemium) vs autre
- Nom de domaine à acheter

## Success Metrics

**Primary Metrics**:
- RDV découverte bookés : 5-10 / mois dans les 3 premiers mois
- Taux de conversion visiteur → RDV : > 5%

**Secondary Metrics**:
- Temps moyen sur la page : > 1 min 30
- Taux de rebond : < 50%
- Source des visiteurs (lien direct vs. organique vs. LinkedIn)

## Timeline & Milestones

- **Design & contenu validé**: 1 semaine après choix du nom/branding
- **MVP en ligne**: 1 semaine de dev après validation du contenu
- **Premier test avec leads existants**: Dès mise en ligne
- **Itération basée sur feedback**: En continu

## Stack Technique Recommandé

| Composant | Recommandation | Raison | Coût |
|-----------|---------------|--------|------|
| **Framework** | Next.js (App Router) | SEO natif, rapide, moderne, flexible | Gratuit |
| **Styling** | Tailwind CSS + shadcn/ui | Composants pro sans designer, itération rapide | Gratuit |
| **Hébergement** | Vercel | Deploy en 1 clic, CDN mondial, analytics basiques | Gratuit (hobby plan) |
| **Booking** | Cal.com | Open-source, gratuit, embed facile, notifications email | Gratuit |
| **Analytics** | Vercel Analytics ou Plausible | Simple, RGPD-friendly | Gratuit / 9€/mois |
| **Domaine** | Via OVH ou Gandi | Fournisseurs français, ~10-15€/an | ~12€/an |

**Coût total estimé : ~12€/an** (juste le domaine)
