# Pourquoi le Webmaster ne peut pas tenir le CRM en même temps

Note d'argumentaire pour la discussion sur l'organisation marketing. Sources vérifiées lors de la recherche (5 recherches, sources vendor-neutres et gouvernance). À garder comme appui de la partie 2 du deck.

## En une phrase

Le site est un canal, le CRM est le système de référence qui mesure ce canal. Par gouvernance, par compétence et par charge, ces deux responsabilités appellent deux propriétaires distincts. Regrouper les deux sur une seule personne dégrade la donnée et brouille la mesure.

## L'argument, point par point

### 1. Le propriétaire du CRM est un rôle dédié, pas une tâche ajoutée à un canal

Dans les référentiels de rôles CRM, le CRM a son propriétaire opérationnel (l'administrateur qui configure le système, gère les accès et maintient la qualité de la donnée) et son propriétaire stratégique (qui tient la feuille de route et répond de la valeur commerciale). Dans les grandes organisations, c'est un poste dédié, pas une responsabilité partagée en marge d'un autre métier.
Sources : [TechnologyAdvice](https://technologyadvice.com/blog/sales/crm-roles-and-responsibilities/), [Vtiger](https://www.vtiger.com/blog/crm-roles-and-responsibilities/), [BLND](https://blnd.agency/crm-agency-roles-admin-vs-manager/).

### 2. La gouvernance veut un propriétaire clair par système, et l'opérateur d'un canal ne doit pas tenir le système qui le mesure

La séparation des devoirs existe pour réduire les conflits d'intérêt et protéger l'intégrité de la donnée. Celui qui met en place un contrôle ne doit pas aussi l'approuver ou l'auditer. En gouvernance de la donnée CRM, chaque actif de donnée doit avoir un propriétaire responsable, faute de quoi la responsabilité disparaît et la qualité se dégrade. Le site est un canal d'acquisition, le CRM est le système de référence qui note et attribue ce canal. Les réunir revient à confier au propriétaire du canal la note de son propre canal.
Sources : [Imperva, séparation des devoirs](https://www.imperva.com/learn/data-security/separation-of-duties/), [LogicManager](https://www.logicmanager.com/resources/corporate-governance/governance-101-why-separation-of-duties-is-non-negotiable/), [SyncMatters, gouvernance CRM](https://syncmatters.com/blog/crm-data-governance-best-practices-for-scaling-teams).

### 3. La gestion du site et le Marketing Operations sont deux métiers, avec des compétences et des indicateurs différents

Les métiers du site sont tournés vers le client : contenu, SEO, UX, mesurés au trafic, à la conversion, à l'engagement. Les métiers du Marketing Operations sont d'infrastructure : stack, automation, qualité et intégrité de la donnée, mesurés à l'efficacité des processus, à la justesse de la donnée, à la performance des systèmes. Une seule personne qui couvre les deux ne fait ni l'un ni l'autre en profondeur.
Sources : [FullEnrich, comparaison des rôles](https://fullenrich.com/jobtitle/Digital-Marketing-Specialist-VS-Marketing-Operations-Specialist), [MarketingOps.com, compétences](https://marketingops.com/the-background-11-skill-sets-of-amazing-marketing-operations-professionals/), [Smart Insights, website ops](https://www.smartinsights.com/managing-digital-marketing/personal-career-development/succeed-website-operations-manager/).

### 4. Une prise en charge du CRM au coup par coup dégrade la donnée, c'est un mode d'échec documenté

La qualité de la donnée décline dès qu'un chantier de nettoyage s'arrête, sauf s'il existe un propriétaire et un gardien dédiés. La plupart des équipes ont des consommateurs de donnée mais ni propriétaire ni gardien. Une mauvaise qualité de donnée CRM est estimée coûter 15 à 25 % du chiffre annuel. Le modèle sain sépare un propriétaire de la donnée (qui pose la règle) et un gardien de la donnée (l'administrateur CRM qui l'applique), tous deux dédiés. Un webmaster qui absorbe le CRM petit à petit, c'est exactement la prise en charge partielle qui se dégrade.
Sources : [RevBlack](https://www.revblack.com/articles/data-quality-nightmares-why-your-crm-is-lying-to-you), [ZielLab, qualité de donnée RevOps](https://ziellab.com/post/crm-data-quality-b2b-revops-guide), [Validity](https://www.validity.com/blog/data-quality-management/).

### 5. Un propriétaire unique et clair est une bonne pratique reconnue du Marketing Operations, la propriété diffuse est une erreur nommée

Chaque outil a besoin d'un propriétaire désigné. Les problèmes de stack martech remontent directement à l'absence de propriété et de gouvernance, là où la responsabilité se dilue et où les systèmes se dégradent en silence. La recommandation est de traiter la gouvernance du martech comme une fonction de direction, avec un propriétaire doté d'autorité.
Sources : [ORM-Tech, absence de propriété](https://orm-tech.com/news/20260710-martech-stack-issues-trace-to-missing-ownership-and-governan/), [MarketingOps.com, audit du stack](https://marketingops.com/marketing-tech-stack-audit-guide-for-marketing-operations/), [CMSWire](https://www.cmswire.com/digital-experience/why-martech-consolidation-in-2026-requires-fixing-workflows-not-just-cutting-vendors/).

## Pourquoi laisser le site à son propriétaire actuel est le bon choix

Ce n'est pas retirer une responsabilité, c'est donner un vrai propriétaire aux deux métiers.

- Le site mérite un propriétaire dédié et concentré. Contenu, SEO, UX, conversion sont un métier complet, avec ses propres indicateurs.
- Deux propriétaires clairs valent mieux qu'un seul flou. La bonne pratique de gouvernance, c'est un propriétaire responsable par système. Un pour le canal, un pour le système de référence. Rien ne tombe entre les deux.
- La mesure reste indépendante. Le site est un canal noté. Le système qui le note doit avoir un propriétaire séparé, pour que les chiffres restent crédibles.
- La spécialisation protège la qualité de la donnée. La prise en charge partielle du CRM se dégrade. Deux propriétaires dédiés protègent les deux.

## Le point honnête, et pourquoi il joue en notre faveur

À petite échelle, regrouper ces rôles est normal, le CRM se retrouve souvent en IT ou aux opérations comme tâche partagée. L'argument de séparation se renforce à mesure que l'échelle et les enjeux grandissent. Ayming n'est pas à petite échelle. Nous avons un Salesforce groupe (One Salesforce), une chaîne d'attribution réelle, une donnée multi-pays. Le CRM est une infrastructure d'entreprise partagée, qui alimente les ventes et le reporting groupe, pas un canal marketing. C'est le point structurel qui referme le dossier. Le site est un canal France, le CRM est une infrastructure partagée. Laisser un rôle de canal absorber une infrastructure d'entreprise inverse les altitudes. Le site à son propriétaire, l'infrastructure à un propriétaire dédié, au bon niveau.
