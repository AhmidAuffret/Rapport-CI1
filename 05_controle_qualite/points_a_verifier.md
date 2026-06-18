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
- Les informations nécessaires à la Partie I ont été partiellement complétées : activité exacte, secteur, sites principaux liés à l'activité, effectif approximatif, service informatique, composition du service, changement de tuteur et autonomie de l'étudiant.
- Les informations nécessaires à une rédaction définitive restent incomplètes sur les sources publiques, l'histoire, la culture, les valeurs, les chiffres financiers, les volumes de production, le site exact du service informatique et certains détails d'organisation.
- Les dates exactes, résultats mesurables et validations de production des missions principales restent à compléter ou vérifier.
- Les moyens humains, financiers et documentaires doivent encore être précisés ; ne pas inventer de budget, d’équipe ou de décision d’achat.
- Les illustrations sont prévues, mais aucune ne doit être réalisée ou intégrée avant validation du niveau de détail autorisé et de l’anonymisation.
- Une règle de prudence a été établie pour la confidentialité : anonymisation systématique des informations sensibles. La mention CONFIDENTIEL et la liste finale des éléments diffusables restent à vérifier avant toute version finale.

### Décision avant rédaction

- Première rédaction cadrée : possible.
- Rédaction finale ou validation du rapport : impossible à ce stade, tant que les points `[À compléter]`, `[À vérifier]` et `[À valider]` ci-dessous ne sont pas traités.
- Règle à appliquer pendant la rédaction : ne jamais transformer un objectif, un résultat attendu ou une hypothèse en fait validé sans source ou validation explicite.

## Points prioritaires avant rédaction

- Données officielles Leroux utilisables dans le rapport : activité, secteur, sites et effectif approximatif intégrés ; sources publiques encore à vérifier.
- Noms et postes des personnes à remercier : intégrés ; orthographe complète de `Quentin ****` et autorisation finale `[À vérifier]`.
- Description exacte de l’équipe informatique : service composé de deux personnes, responsable informatique et alternant administrateur systèmes et réseaux.
- Dates ou périodes des missions : durée approximative Intune environ deux mois, registre visiteurs environ un mois ; périodes calendaires exactes `[À compléter]`.
- Résultats mesurables disponibles : `[À vérifier]`.
- Moyens humains, financiers et documentaires mobilisés pour chaque mission : `[À compléter]`.
- Illustrations autorisées par l’entreprise : captures et schémas globalement autorisés si anonymisés ; liste finale `[À vérifier]`.
- Niveau de confidentialité demandé par l’entreprise : règle de prudence intégrée ; mention CONFIDENTIEL `[À vérifier]`.
- Décision finale sur Docker `prd-dkr01` : `[À valider]`.

## Informations bloquantes ou semi-bloquantes avant rédaction

### Bloquant avant Partie I

Informations nécessaires pour rédiger correctement la présentation de l'entreprise et du service :

- formulation officielle de l'activité principale de Leroux : intégrée comme entreprise industrielle agroalimentaire spécialisée dans la transformation de la chicorée ;
- sources publiques validées pour l'histoire, l'activité, l'implantation, la filière et les produits ;
- chiffres clés publics utilisables ou décision explicite de ne pas en utiliser : effectif approximatif intégré ; chiffre d'affaires et volumes à sourcer ;
- sites Leroux pouvant être cités dans le rapport : Orchies et Vieille-Église intégrés ;
- description exacte du service informatique : intégrée ;
- nom exact du service : "service informatique" ;
- taille de l'équipe informatique : deux personnes ;
- rôles ou métiers principaux présents dans l'équipe : responsable informatique et alternant administrateur systèmes et réseaux ;
- rattachement ou positionnement du service dans l'organisation : responsable informatique rattaché au DAF Quentin **** `[orthographe / anonymisation à confirmer]` ;
- interactions principales entre le service informatique et les autres services : échanges réguliers avec les utilisateurs intégrés ; services précis `[À compléter si nécessaire]` ;
- positionnement réel de l'étudiant dans l'équipe : intégré avec grande autonomie opérationnelle et validation finale par le tuteur ou l'entreprise ;
- nom, fonction et autorisation de citation du maître d'apprentissage : Loïc Humman puis Thierry Devigne intégrés ; autorisation finale de citation `[À vérifier]` ;
- niveau de confidentialité global du rapport : règle de prudence intégrée ; mention CONFIDENTIEL `[À vérifier]` ;
- autorisation ou non d'utiliser des noms de personnes, sites, services, schémas ou captures : partiellement intégrée ; validation finale `[À vérifier]`.

### Bloquant avant Partie II

Informations nécessaires pour rédiger correctement les missions :

- période exacte ou approximative de chaque mission principale : durées approximatives intégrées pour Intune et registre visiteurs ; période de la mission sécurité et dates calendaires `[À compléter]` ;
- objectif réel de la mission Microsoft Intune / Android Enterprise : administration homogène et sécurisée des tablettes, avec usages accueil et production ;
- rôle exact de l'étudiant sur Intune : rôle opérationnel de bout en bout intégré ;
- actions Intune réellement réalisées : compréhension du besoin, configuration, tests, enrôlement, ajustements, échanges et documentation si nécessaire intégrés ;
- statut réel de validation ou de déploiement des tablettes ;
- tests Intune réalisés et résultats confirmés ;
- objectif réel du registre visiteurs Power Apps / SharePoint / Power Automate : remplacement du registre papier par une solution numérique sur tablette ;
- état actuel du registre visiteurs : solution techniquement validée mais pas encore utilisée à l'accueil ;
- statut réel du registre papier : supprimé, maintenu ou remplacé partiellement ;
- solutions Power Apps / Power Automate réellement validées : application fonctionnelle, SharePoint, flow fonctionnel et signature PNG intégrés ;
- types d'incidents traités dans la mission sécurité AD / Microsoft 365 : verrouillages AD, connexions suspectes, authentification, journaux, postes, Microsoft 365 / Entra, Wi-Fi, NPS et mots de passe enregistrés intégrés ;
- rôle exact de l'étudiant dans les analyses de sécurité ;
- outils précis utilisés pour les diagnostics ;
- causes réellement identifiées ou hypothèses encore non confirmées ;
- exemples anonymisés utilisables ;
- limites de confidentialité propres aux missions techniques : règle d'anonymisation systématique intégrée ; exemples précis `[À vérifier]`.

### Non bloquant mais à traiter avant version finale

Informations utiles pour améliorer le rapport mais non nécessaires au premier brouillon :

- titre définitif du rapport ;
- validation finale du fil conducteur et du plan détaillé ;
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

- Données officielles Leroux utilisables dans le rapport : activité, secteur, sites principaux et effectif approximatif intégrés ; sources publiques `[À vérifier]`.
- Présentation officielle de Leroux validée : `[À vérifier]`.
- Secteur et activité exacte : industrie agroalimentaire, transformation de la chicorée.
- Chiffres clés publics sourcés : effectif approximatif interne environ 150 salariés ; chiffre d'affaires et volumes `[À vérifier avec sources publiques]`.
- Histoire, culture et valeurs : `[À vérifier]`.
- Organisation, processus ou organigramme utilisables : `[À vérifier]`.
- Clients, partenaires, concurrents ou environnement économique à mentionner : `[À vérifier]`.
- Sources publiques à citer en bibliographie : `[À compléter]`.

## Remerciements

- Noms et postes des personnes à remercier : Loïc Humman, Thierry Devigne, Quentin ****, Éloïse Six, Guilhain Lesaffre et collaborateurs du quotidien intégrés.
- Raison précise du remerciement pour chaque personne : `[À compléter]`.
- Validation de l’orthographe des noms et fonctions : `[À vérifier]`.
- Accord pour citer les personnes nommément si nécessaire : `[À vérifier]`.

## Service informatique et rôle de l'étudiant

- Description exacte de l’équipe informatique : service informatique composé du responsable informatique et de l'alternant administrateur systèmes et réseaux.
- Taille et organisation de l'équipe : deux personnes, organisation souple selon les besoins, priorités, projets et disponibilités.
- Rattachement ou positionnement du service : responsable informatique rattaché au DAF Quentin **** `[orthographe / anonymisation à confirmer]`.
- Métiers du service informatique et métiers internes en interaction avec l'étudiant : `[À compléter]`.
- Positionnement de l'étudiant dans l'équipe : alternant administrateur systèmes et réseaux avec grande autonomie opérationnelle.
- Nom et rôle du maître d'apprentissage : Loïc Humman au début de l'année, puis Thierry Devigne, responsables informatiques et tuteurs successifs.
- Interactions avec les autres métiers ou services : échanges réguliers avec les utilisateurs ; services précis `[À compléter si nécessaire]`.
- Niveau d’autonomie réel de l’étudiant selon les missions : autonomie opérationnelle importante, décisions finales structurantes ou financières validées par le tuteur ou l'entreprise.
- Formulation évitant de présenter l'étudiant comme responsable unique du SI : `[À vérifier]`.

## Missions principales

- Confirmation finale des trois missions principales :
  - Microsoft Intune / Android Enterprise : `[À vérifier]` ;
  - registre visiteurs Power Apps / SharePoint / Power Automate : `[À vérifier]` ;
  - sécurité opérationnelle AD / Microsoft 365 : `[À vérifier]`.
- Dates ou périodes de chaque mission : durée approximative Intune environ deux mois et registre visiteurs environ un mois ; période sécurité et dates calendaires `[À compléter]`.
- Étapes réellement réalisées par l'étudiant : complétées pour Intune et registre visiteurs ; sécurité à détailler par exemples anonymisés.
- Résultats mesurables disponibles : `[À vérifier]`.
- Résultats obtenus, attendus ou encore à vérifier clairement distingués : `[À vérifier]`.
- Moyens humains, matériels, techniques et éventuellement financiers identifiés : `[À compléter]`.
- Difficultés et solutions reliées à des faits réels : `[À vérifier]`.
- Analyse personnelle présente pour chaque mission : `[À vérifier]`.

### Microsoft Intune / Android Enterprise

- Tests réalisés sur les tablettes : tests et ajustements intégrés ; résultats précis `[À compléter]`.
- Statut exact de validation de la configuration : `[À vérifier]`.
- Volume de tablettes concernées si diffusable : `[À vérifier]`.
- Applications réellement déployées ou seulement prévues : `[À vérifier]`.
- Procédure ou documentation interne produite : `[À compléter]`.
- Points déplacés ou reformulés lors de la correction v2 : période calendaire exacte, nombre exact de tablettes, résultats précis des tests, documentation interne éventuelle, niveau d'autorisation pour citer les paramètres, outils, modèle de tablette et version Android.
- Paramètres précis à valider avant citation éventuelle : règle exacte de mot de passe, comportement exact d'effacement après échecs, plage horaire exacte de mise à jour, restrictions détaillées et applications réellement déployées ou seulement prévues.
- Question à poser à l'étudiant : peux-tu confirmer la période exacte de la mission Intune, le nombre de tablettes concernées, les tests réellement validés, les paramètres exacts autorisés à citer et l'existence ou non d'une procédure interne ?
- Pourquoi c'est nécessaire : ces informations permettent de préciser les résultats sans inventer de dates, de volumes, de gains ou de validation officielle.
- Partie du rapport concernée : Partie II, section `1. Microsoft Intune / Android Enterprise`, principalement `1.3 Moyens et outils utilisés`, `1.4 Démarche suivie`, `1.6 Résultats obtenus` et `1.7 Limites et points restant à suivre`.

### Registre visiteurs Power Apps / SharePoint / Power Automate

- Tablette utilisée à l’entrée : tablette d'accueil destinée au registre visiteurs ; modèle exact `[À vérifier]`.
- Service ou utilisateurs concernés : accueil ; service précis `[À compléter si nécessaire]`.
- Statut réel de mise en service : techniquement validé, pas encore utilisé à l'accueil.
- Suppression totale ou partielle du registre papier : non confirmée, ne pas annoncer comme réalisée.
- Fiabilité finale du flow `FLOW_CreateVisitorWithSignature` : flow fonctionnel et signature PNG correctement enregistrée.
- Données budgétaires exploitables pour cette mission : non intégrées à ce stade ; confirmer seulement si l'école ou l'entreprise souhaite faire apparaître un volet financier.
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

- Illustrations autorisées par l’entreprise : globalement autorisées si anonymisées ; sélection finale `[À vérifier]`.
- Captures d’écran autorisées et anonymisées : globalement autorisées si anonymisées ; captures exactes `[À vérifier]`.
- Schéma simplifié du service informatique validé : `[À vérifier]`.
- Architecture Intune / Android Enterprise validée : `[À vérifier]`.
- Architecture Power Apps / SharePoint / Power Automate validée : `[À vérifier]`.
- Chaîne de diagnostic sécurité AD / Microsoft 365 validée : `[À vérifier]`.
- Tableau de synthèse des missions validé : `[À vérifier]`.
- Table des illustrations et tableaux à générer : `[À vérifier]`.
- Annexes limitées aux éléments utiles à la compréhension : `[À vérifier]`.

## Confidentialité

- Niveau de confidentialité demandé par l'entreprise : aucune directive spécifique donnée, règle de prudence appliquée.
- Mention CONFIDENTIEL nécessaire ou non : `[À vérifier]`.
- Niveau de confidentialité de chaque mission : `[À vérifier]`.
- Noms de personnes validés ou remplacés par `[REDACTED]` : personnes à remercier intégrées ; autorisation finale et `Quentin ****` `[À vérifier]`.
- Noms de comptes et utilisateurs anonymisés : à anonymiser systématiquement.
- Adresses IP internes supprimées ou remplacées par `[REDACTED]` : à anonymiser systématiquement.
- Noms de serveurs internes supprimés ou validés : à anonymiser systématiquement sauf validation explicite.
- Journaux bruts exclus ou anonymisés : à anonymiser systématiquement ; éviter les journaux bruts.
- Données visiteurs réelles exclues du rapport : à exclure ou anonymiser systématiquement.
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
