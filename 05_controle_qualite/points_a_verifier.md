# Points à vérifier

Statut : points de contrôle avant rédaction du rapport.

## Synthèse du contrôle de cohérence du 2026-06-17

Statut général : le plan est cohérent pour commencer une première rédaction cadrée, à condition de conserver les marqueurs `[À compléter]`, `[À vérifier]` et `[REDACTED]` tant que les informations ne sont pas validées.

### Points cohérents

- Structure IMT minimale couverte dans le plan : page de garde, remerciements, sommaire, table des figures, résumés français et anglais, introduction, développement, conclusion, bibliographie, annexe IA obligatoire et annexes éventuelles.
- Grille d’évaluation couverte par la matrice : entreprise et missions, démarche ingénieur, conception du rapport, illustrations, confidentialité et annexe IA.
- Trois missions principales correctement placées en Partie II :
  - Microsoft Intune / Android Enterprise ;
  - registre visiteurs Power Apps / SharePoint / Power Automate ;
  - sécurité opérationnelle AD / Microsoft 365.
- Structure imposée pour chaque mission principale présente dans le plan : contexte, objectifs, contraintes, déroulement, moyens et ressources, difficultés, solutions, résultats et recul personnel.
- Xibo, uniFLOW et GLPI ne sont pas utilisés comme missions principales dans le plan.
- Docker `prd-dkr01` reste limité à une mission secondaire ou optionnelle, avec un volume maximal prévu de 0 à 1 page si la décision finale le confirme.
- Règles de style compatibles avec le plan : progression du contexte vers les actions, première personne pour le retour d’expérience, prudence sur les résultats et refus des formulations trop valorisantes.

### Incohérences ou fragilités détectées

- Le critère IMT sur la présentation des métiers était présent mais insuffisamment explicite dans la section `3.3 Service informatique` du plan : clarification ajoutée dans `01_plan/plan_rapport.md`.
- Les informations nécessaires à la Partie I restent trop incomplètes pour une rédaction définitive : activité exacte, chiffres clés, sources publiques, histoire, culture, valeurs, organisation et description du service.
- Les dates, périodes, résultats mesurables et validations de production des missions principales restent à compléter ou vérifier.
- Les moyens humains, financiers et documentaires doivent encore être précisés ; ne pas inventer de budget, d’équipe ou de décision d’achat.
- Les illustrations sont prévues, mais aucune ne doit être réalisée ou intégrée avant validation du niveau de détail autorisé et de l’anonymisation.
- Le niveau de confidentialité demandé par l’entreprise, la mention CONFIDENTIEL et les éléments diffusables restent à vérifier avant toute version finale.

### Décision avant rédaction

- Première rédaction cadrée : possible.
- Rédaction finale ou validation du rapport : impossible à ce stade, tant que les points `[À compléter]`, `[À vérifier]` et `[À valider]` ci-dessous ne sont pas traités.
- Règle à appliquer pendant la rédaction : ne jamais transformer un objectif, un résultat attendu ou une hypothèse en fait validé sans source ou validation explicite.

## Points prioritaires avant rédaction

- Données officielles Leroux utilisables dans le rapport : `[À vérifier]`.
- Noms et postes des personnes à remercier : `[À compléter]`.
- Description exacte de l’équipe informatique : `[À compléter]`.
- Dates ou périodes des missions : `[À compléter]`.
- Résultats mesurables disponibles : `[À vérifier]`.
- Moyens humains, financiers et documentaires mobilisés pour chaque mission : `[À compléter]`.
- Illustrations autorisées par l’entreprise : `[À vérifier]`.
- Niveau de confidentialité demandé par l’entreprise : `[À vérifier]`.
- Décision finale sur Docker `prd-dkr01` : `[À valider]`.

## Informations bloquantes ou semi-bloquantes avant rédaction

### Bloquant avant Partie I

Informations nécessaires pour rédiger correctement la présentation de l'entreprise et du service :

- formulation officielle de l'activité principale de Leroux ;
- sources publiques validées pour l'histoire, l'activité, l'implantation, la filière et les produits ;
- chiffres clés publics utilisables ou décision explicite de ne pas en utiliser ;
- sites Leroux pouvant être cités dans le rapport ;
- description exacte du service informatique ;
- nom exact du service ;
- taille de l'équipe informatique ;
- rôles ou métiers principaux présents dans l'équipe ;
- rattachement ou positionnement du service dans l'organisation ;
- interactions principales entre le service informatique et les autres services ;
- positionnement réel de l'étudiant dans l'équipe ;
- nom, fonction et autorisation de citation du maître d'apprentissage ;
- niveau de confidentialité global du rapport ;
- autorisation ou non d'utiliser des noms de personnes, sites, services, schémas ou captures.

### Bloquant avant Partie II

Informations nécessaires pour rédiger correctement les missions :

- période exacte ou approximative de chaque mission principale ;
- objectif réel de la mission Microsoft Intune / Android Enterprise ;
- rôle exact de l'étudiant sur Intune ;
- actions Intune réellement réalisées ;
- statut réel de validation ou de déploiement des tablettes ;
- tests Intune réalisés et résultats confirmés ;
- objectif réel du registre visiteurs Power Apps / SharePoint / Power Automate ;
- état actuel du registre visiteurs : prototype, test, production ou utilisation partielle ;
- statut réel du registre papier : supprimé, maintenu ou remplacé partiellement ;
- solutions Power Apps / Power Automate réellement validées ;
- types d'incidents traités dans la mission sécurité AD / Microsoft 365 ;
- rôle exact de l'étudiant dans les analyses de sécurité ;
- outils précis utilisés pour les diagnostics ;
- causes réellement identifiées ou hypothèses encore non confirmées ;
- exemples anonymisés utilisables ;
- limites de confidentialité propres aux missions techniques.

### Non bloquant mais à traiter avant version finale

Informations utiles pour améliorer le rapport mais non nécessaires au premier brouillon :

- titre définitif du rapport ;
- promotion exacte ;
- logos autorisés ;
- liste définitive des personnes à remercier ;
- formulation finale des résumés français et anglais ;
- choix définitif des illustrations ;
- table des figures et tableaux ;
- niveau de détail des annexes techniques ;
- décision finale sur l'intégration ou non de Docker `prd-dkr01` comme mission secondaire ;
- autorisation de mentionner SFR Cloud Agility si Docker est cité ;
- bibliographie finale avec dates de consultation ;
- annexe IA complète, incluant l'impact environnemental ou le bilan carbone ;
- correction orthographique et harmonisation de style avant export ;
- validation finale de la mention CONFIDENTIEL.

## Contexte entreprise

- Données officielles Leroux utilisables dans le rapport : `[À vérifier]`.
- Présentation officielle de Leroux validée : `[À vérifier]`.
- Secteur et activité exacte : `[À vérifier]`.
- Chiffres clés publics sourcés : `[À vérifier]`.
- Histoire, culture et valeurs : `[À vérifier]`.
- Organisation, processus ou organigramme utilisables : `[À vérifier]`.
- Clients, partenaires, concurrents ou environnement économique à mentionner : `[À vérifier]`.
- Sources publiques à citer en bibliographie : `[À compléter]`.

## Remerciements

- Noms et postes des personnes à remercier : `[À compléter]`.
- Raison précise du remerciement pour chaque personne : `[À compléter]`.
- Validation de l’orthographe des noms et fonctions : `[À vérifier]`.
- Accord pour citer les personnes nommément si nécessaire : `[À vérifier]`.

## Service informatique et rôle de l'étudiant

- Description exacte de l’équipe informatique : `[À compléter]`.
- Taille et organisation de l'équipe : `[À compléter]`.
- Rattachement ou positionnement du service : `[À compléter]`.
- Métiers du service informatique et métiers internes en interaction avec l'étudiant : `[À compléter]`.
- Positionnement de l'étudiant dans l'équipe : `[À compléter]`.
- Nom et rôle du maître d'apprentissage : `[À vérifier]`.
- Interactions avec les autres métiers ou services : `[À compléter]`.
- Niveau d’autonomie réel de l’étudiant selon les missions : `[À compléter]`.
- Formulation évitant de présenter l'étudiant comme responsable unique du SI : `[À vérifier]`.

## Missions principales

- Confirmation finale des trois missions principales :
  - Microsoft Intune / Android Enterprise : `[À vérifier]` ;
  - registre visiteurs Power Apps / SharePoint / Power Automate : `[À vérifier]` ;
  - sécurité opérationnelle AD / Microsoft 365 : `[À vérifier]`.
- Dates ou périodes de chaque mission : `[À compléter]`.
- Étapes réellement réalisées par l'étudiant : `[À compléter]`.
- Résultats mesurables disponibles : `[À vérifier]`.
- Résultats obtenus, attendus ou encore à vérifier clairement distingués : `[À vérifier]`.
- Moyens humains, matériels, techniques et éventuellement financiers identifiés : `[À compléter]`.
- Difficultés et solutions reliées à des faits réels : `[À vérifier]`.
- Analyse personnelle présente pour chaque mission : `[À vérifier]`.

### Microsoft Intune / Android Enterprise

- Tests réalisés sur les tablettes : `[À compléter]`.
- Statut exact de validation de la configuration : `[À vérifier]`.
- Volume de tablettes concernées si diffusable : `[À vérifier]`.
- Applications réellement déployées ou seulement prévues : `[À vérifier]`.
- Procédure ou documentation interne produite : `[À compléter]`.

### Registre visiteurs Power Apps / SharePoint / Power Automate

- Tablette utilisée à l’entrée : `[À vérifier]`.
- Service ou utilisateurs concernés : `[À compléter]`.
- Statut réel de mise en service : `[À vérifier]`.
- Suppression totale ou partielle du registre papier : `[À vérifier]`.
- Fiabilité finale du flow `FLOW_CreateVisitorWithSignature` : `[À vérifier]`.
- Absence de données visiteurs réelles dans le rapport : `[À vérifier]`.

### Sécurité opérationnelle AD / Microsoft 365

- Formulation exacte de l’environnement Microsoft / Entra : `[À vérifier]`.
- Outils précis utilisés pour les journaux et diagnostics : `[À compléter]`.
- Chronologie des analyses : `[À compléter]`.
- Causes réellement identifiées ou hypothèses non confirmées : `[À vérifier]`.
- Exemples anonymisés disponibles : `[À vérifier]`.
- Aucun journal brut sensible inclus : `[À vérifier]`.

## Mission secondaire Docker

- Décision finale sur Docker `prd-dkr01` : intégré comme mission secondaire ou non : `[À valider]`.
- Hostname `prd-dkr01` diffusable ou à remplacer par `[REDACTED]` : `[À vérifier]`.
- Mention de SFR Cloud Agility autorisée : `[À vérifier]`.
- Niveau de détail technique autorisé : `[À vérifier]`.
- Aucun recentrage du rapport sur Xibo : `[À vérifier]`.
- Reverse proxy, sauvegarde et application finale non présentés comme finalisés : `[À vérifier]`.

## Missions exclues

- Xibo non utilisé comme mission principale : `[À vérifier]`.
- uniFLOW non utilisé comme mission principale : `[À vérifier]`.
- GLPI non utilisé comme mission principale : `[À vérifier]`.
- GLPI cité seulement comme lien, outil consultable ou contexte ponctuel si nécessaire : `[À vérifier]`.

## Style d’écriture

- Texte personnel et fidèle à l’expérience réelle de l’étudiant : `[À vérifier]`.
- Missions non survalorisées et niveau d’autonomie présenté avec prudence : `[À vérifier]`.
- Explications progressives, du contexte vers les actions techniques : `[À vérifier]`.
- Première personne utilisée lorsque l’étudiant parle de ses actions, difficultés ou apprentissages : `[À vérifier]`.
- Style ni trop académique, ni trop générique, ni trop soutenu : `[À vérifier]`.
- Répétitions et formulations lourdes corrigées sans dénaturer la logique d’écriture de l’étudiant : `[À vérifier]`.
- Objectifs, actions réalisées, résultats obtenus et points `[À vérifier]` clairement distingués : `[À vérifier]`.

## Illustrations et annexes

- Illustrations autorisées par l’entreprise : `[À vérifier]`.
- Captures d’écran autorisées et anonymisées : `[À vérifier]`.
- Schéma simplifié du service informatique validé : `[À vérifier]`.
- Architecture Intune / Android Enterprise validée : `[À vérifier]`.
- Architecture Power Apps / SharePoint / Power Automate validée : `[À vérifier]`.
- Chaîne de diagnostic sécurité AD / Microsoft 365 validée : `[À vérifier]`.
- Tableau de synthèse des missions validé : `[À vérifier]`.
- Table des illustrations et tableaux à générer : `[À vérifier]`.
- Annexes limitées aux éléments utiles à la compréhension : `[À vérifier]`.

## Confidentialité

- Niveau de confidentialité demandé par l'entreprise : `[À vérifier]`.
- Mention CONFIDENTIEL nécessaire ou non : `[À vérifier]`.
- Niveau de confidentialité de chaque mission : `[À vérifier]`.
- Noms de personnes validés ou remplacés par `[REDACTED]` : `[À vérifier]`.
- Noms de comptes et utilisateurs anonymisés : `[À vérifier]`.
- Adresses IP internes supprimées ou remplacées par `[REDACTED]` : `[À vérifier]`.
- Noms de serveurs internes supprimés ou validés : `[À vérifier]`.
- Journaux bruts exclus ou anonymisés : `[À vérifier]`.
- Données visiteurs réelles exclues du rapport : `[À vérifier]`.
- Documents internes non diffusables exclus ou anonymisés : `[À vérifier]`.

## Conformité IMT

- Rapport entre 25 et 40 pages hors annexes : `[À vérifier]`.
- Structure minimale IMT respectée : `[À vérifier]`.
- Annexe IA présente et transparente : `[À vérifier]`.
- Impact environnemental ou bilan carbone de l’usage IA renseigné : `[À compléter]`.
- Mise en forme conforme : `[À vérifier]`.
- Illustrations titrées, numérotées, annotées et utiles : `[À vérifier]`.
- Bibliographie présente pour les sources publiques et techniques : `[À vérifier]`.
- Introduction présentant le sujet, les objectifs des missions et le plan : `[À vérifier]`.
- Conclusion répondant au fil conducteur : `[À vérifier]`.

## Risques principaux

- Inventer des résultats non validés.
- Donner trop d'importance à Xibo, uniFLOW ou GLPI.
- Inclure des données sensibles.
- Rédiger avant validation du contexte, du plan et du niveau de confidentialité.
- Employer un style trop générique ou trop valorisant.
- Oublier le recul personnel attendu dans un rapport réflexif CI1.
- Oublier les moyens et ressources mobilisés, notamment humains et financiers si l’information existe.
- Intégrer des illustrations non commentées ou non autorisées.
