# Comparaison des plateformes, version corrigée et objective

Le slide présenté compare sur les fonctionnalités et laisse de côté le critère qui décide vraiment pour une entreprise Salesforce : le partage de la donnée. Voici la version corrigée, avec les lignes d'architecture ajoutées et les erreurs rétablies.

## Architecture, le critère décisif (absent du slide)

| Critère | Pardot (actuel) | Salesforce MCN | HubSpot |
|---|---|---|---|
| Base de données native Salesforce | Non, base séparée reliée par connecteur | Oui, natif sur le coeur (Data Cloud) | Non, base séparée, synchro externe |
| Un seul système de référence, marketing et ventes | Partiel, via synchronisation | Oui | Non, deux systèmes |
| Flux de la donnée vers Salesforce | Synchro, latence possible | Temps réel, natif | Synchro externe, plus fragile |

C'est ici que se joue la décision. Pardot envoie déjà la donnée dans Salesforce, mais via une synchro. MCN supprime la synchro, tout est natif. HubSpot ajoute une base de plus, à synchroniser de l'extérieur.

## Fonctionnalités, version corrigée

| Critère | Pardot (actuel) | Salesforce MCN | HubSpot |
|---|---|---|---|
| Bases, email, landing pages, formulaires | Oui | Oui | Oui |
| A/B testing | Via code | Avancé, sans code | Avancé, sans code |
| Scoring, lead et IA prédictive | Oui, Einstein | Oui | Oui |
| Attribution multi-touch | Oui, first, last, even (Campaign Influence), modèles avancés via B2BMA | Oui, natif | Oui, dont U-shaped |
| IA de création de campagnes | Oui, Einstein et Agentforce | Oui, natif Agentforce | Oui, avancé |
| Agent IA, chatbot SDR | Oui, Agentforce SDR | Oui, Agentforce SDR (depuis octobre 2024) | Oui |
| Messagerie, SMS et WhatsApp | Non nativement | Oui | Oui |
| Multicanal natif | Non | Oui | Oui |
| Réseaux sociaux, gestion | Limité | Limité | Oui |
| SEO et recommandations de contenu | Non | Non | Oui |
| Formation et support, tutoriels vidéo | Oui, Trailhead et support Salesforce | Oui, Trailhead | Oui |

## Les erreurs du slide présenté

- **Attribution multi-touch marquée absente pour Pardot.** Faux. Pardot la fait via Campaign Influence (first, last, even) et des modèles avancés via B2B Marketing Analytics.
- **Agent IA et chatbot SDR marqués absents pour Salesforce et MCN.** Faux. Agentforce SDR existe et est disponible depuis octobre 2024.
- **Formation et tutoriels vidéo marqués absents pour Pardot et MCN.** Faux. Salesforce Trailhead est la référence du marché, et Pardot en bénéficie.
- **IA de création notée « basique » pour MCN.** Trompeur. MCN est natif Agentforce, c'est l'un de ses arguments majeurs, pas une brique basique.
- **Omission de fond.** Aucune ligne sur l'architecture et le partage de la donnée avec Salesforce, qui est le critère décisif.

## En clair

- Les lignes qui décident sont celles d'architecture, et elles étaient absentes du slide.
- HubSpot a de vrais atouts, réseaux sociaux, SEO, contenu. Ils ne compensent pas la création d'un silo de données de plus avec Salesforce.
- Pardot n'est pas mauvais. Il fait l'essentiel, l'attribution, l'IA, avec la formation Salesforce. Sa seule vraie limite est la base séparée.
- MCN garde tout ce que fait Pardot, corrige la limite de la base nativement, et ajoute l'IA. C'est l'évolution logique, dans Salesforce.

Sources : [Salesforce, Agentforce SDR](https://www.salesforce.com/news/stories/einstein-sales-agents-announcement/), [Pardot attribution, marcloud](https://marcloudconsulting.com/training/pardot-campaign-reporting-attribution/), [MCN natif, Bloomreach](https://www.bloomreach.com/en/blog/salesforce-marketing-cloud-next), [MCN sur le coeur, Arkus](https://www.arkusinc.com/archive/2025/why-salesforce-marketing-cloud-on-core), [HubSpot et Salesforce, Stacksync](https://www.stacksync.com/blog/hubspot-and-salesforce-sync-the-complete-guide-to-bi-directional-integration).
