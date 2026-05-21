# Product

## Register

brand

## Users

**Le dirigeant de PME française** — DG / CEO / gérant d'une entreprise de 10 à 100 salariés en finance, santé, industrie, ou cabinet (conseil, avocats, comptables).

Il arrive sur le site via un lien envoyé par le commercial, LinkedIn, ou une recherche. Il décide en 30 secondes si Lionia mérite un appel. Il sait que l'IA va transformer son secteur mais ne sait pas comment l'intégrer concrètement. Il a déjà vu passer des formations génériques qui n'ont rien changé. Il est inquiet pour la confidentialité des données et préoccupé par le retard sur ses concurrents.

Son job-to-be-done sur le site : valider en quelques secondes que Lionia comprend son métier, comprendre l'offre sans jargon, et booker un appel découverte sans friction.

## Product Purpose

Lionia positionne un accompagnement IA sur-mesure en trois niveaux progressifs — audit, formation contextualisée, agents IA custom — destiné aux PME françaises. Le site marketing existe pour générer des rendez-vous découverte qualifiés (objectif 5 à 10 par mois).

Le succès se mesure à un taux de conversion visiteur → RDV supérieur à 5%, et à la qualité des leads transmis au commercial. La page doit faire le travail d'un commercial silencieux : crédibiliser, clarifier l'offre, et déclencher l'action.

## Brand Personality

**Moderne, ambitieux, tech-forward** — appliqué au B2B français, calibré sur l'autorité calme d'un Stripe, Mercury, ou Ramp.

Voix : directe, confiante, concrète. Comme un expert qui parle à un pair, pas comme un vendeur qui pitche. Vouvoiement, B2B formel mais jamais froid. On dit "l'IA" pas "l'intelligence artificielle", "vos process" pas "vos processus organisationnels", "gagner du temps" pas "optimiser l'efficience opérationnelle".

Émotions visées : crédibilité, calme, sentiment "ces gens comprennent mon métier", envie de poursuivre la conversation.

## Anti-references

Trois pièges à éviter explicitement :

- **L'esthétique AI startup générique.** Gradients violet/cyan, néon sur fond noir, dark mode par défaut, glows partout, icônes de cerveau ou de robot, langage "ChatGPT-cosplay". Lionia n'est pas un outil IA — c'est un cabinet d'expertise. La page ne doit pas pouvoir être confondue avec une startup IA SaaS.
- **Le cabinet de conseil français rigide.** Bleu marine et or, serif corporate, photo stock de poignée de main, "Excellence · Innovation · Performance" en footer. La signal "cher mais ennuyeux" de Deloitte / PwC. Lionia est moderne, pas vieille école.
- **Le growth-hacker marketing.** CTAs énormes en néon, témoignages carrousel exagérés, urgence factice ("Plus que 2 places !"), highlight jaune fluo, langage Hotmart / Systeme.io. Tout ce qui sent l'infopreneur et tue la confiance d'un dirigeant.

## Design Principles

1. **Le site est la preuve.** Un dirigeant qui scrute la page pendant 5 secondes doit y voir le niveau de soin qu'il attend dans le travail livré. Chaque détail (espacement, copie, hiérarchie) est un signal de compétence. Pas d'AI slop, pas de placeholder, pas de "lorem ipsum sophistiqué".
2. **Calme et précis, pas excitant.** L'autorité vient de la retenue, pas du néon. Stripe-grade composure. Si une décoration n'ajoute rien à la compréhension, elle se retire. La confiance se gagne en typographie et en rythme, pas en effets.
3. **Concret bat abstrait, toujours.** Chaque promesse s'attache à un chiffre, un délai, un livrable. "30 jours", "audit en 2-3 jours", "rapport avec plan d'action priorisé" battent "transformation digitale" et "synergies IA". Si une phrase pourrait apparaître sur la home de n'importe quel concurrent, elle est réécrite.
4. **Pédagogique sans condescendance.** Le lecteur est un dirigeant, pas un débutant. On explique l'offre suffisamment pour qu'elle soit utile, jamais au point de paraître infantilisant. On suppose l'intelligence du visiteur.
5. **Friction zéro sur l'action.** Le CTA "Réserver un appel découverte" doit être atteignable en moins de 2 secondes depuis n'importe où dans la page. Pas de formulaire à 10 champs, pas de wall-of-text avant un bouton, pas de modal entre l'envie et le clic.

## Accessibility & Inclusion

**WCAG 2.1 AA** comme baseline professionnelle. Aligné avec les attentes RGAA du marché français B2B (des clients du secteur public ou santé peuvent auditer le site).

Concrètement :

- Contraste AA pour tout texte (4.5:1 corps, 3:1 large).
- Navigation clavier complète, focus visible jamais supprimé.
- `prefers-reduced-motion` respecté — animations désactivées quand demandé par l'utilisateur.
- Alt text descriptif sur les images informatives ; alt vide sur les images décoratives.
- Hiérarchie sémantique propre (un seul `<h1>` par page, ordre logique, structure de landmarks).
- Cibles d'interaction ≥ 44×44 px sur mobile.
