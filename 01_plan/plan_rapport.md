# Plan détaillé du rapport CI1 Leroux

Statut : plan détaillé de travail, à valider avant rédaction finale.

Fil conducteur proposé :

> Comment une première année d’alternance en administration systèmes et réseaux permet-elle de contribuer à la continuité, à la sécurité et à la modernisation du système d’information d’une entreprise industrielle ?

Contraintes générales :

- rapport réflexif de première année CI1 ;
- cible de 25 à 40 pages hors annexes ;
- trois missions principales : Microsoft Intune / Android Enterprise, registre visiteurs Power Apps / SharePoint / Power Automate, sécurité opérationnelle AD / Microsoft 365 ;
- Docker `prd-dkr01` uniquement comme mission secondaire ou optionnelle ;
- Xibo, uniFLOW et GLPI exclus comme missions principales ;
- aucune information inventée : utiliser `[À compléter]` ou `[À vérifier]` si nécessaire ;
- anonymisation systématique des éléments sensibles avec `[REDACTED]`.

## Éléments préliminaires

Volume cible : hors pagination principale ou selon format final.

### Page de garde

- Objectif de la section : identifier clairement le rapport, l’école, l’entreprise et l’étudiant.
- Contenu attendu : nom de l’apprenti, promotion, entreprise Leroux, titre définitif, année universitaire, logo IMT Nord Europe et logo entreprise si autorisés.
- Critères IMT couverts : forme et structure du rapport, mise en forme professionnelle.
- Éléments à compléter : promotion exacte, titre définitif, logos autorisés, mention CONFIDENTIEL si nécessaire.
- Risques d’invention à éviter : ne pas inventer le titre validé, la promotion exacte ou une mention de confidentialité non confirmée.

### Remerciements

- Objectif de la section : remercier les personnes ayant accompagné l’alternance.
- Contenu attendu : personnes à remercier, rôle dans l’accompagnement, aide apportée.
- Critères IMT couverts : qualité de présentation, intégration dans l’entreprise.
- Éléments à compléter : noms, postes et raisons précises des remerciements.
- Risques d’invention à éviter : ne pas citer de personnes, fonctions ou responsabilités sans validation.

### Résumé, abstract et mots-clés

- Objectif de la section : présenter rapidement le sujet, le contexte, les missions et le bilan de l’année.
- Contenu attendu : résumé en français, mots-clés en français, abstract en anglais, keywords.
- Critères IMT couverts : clarté du propos, structure, qualité rédactionnelle.
- Éléments à compléter : formulation finale après rédaction du rapport.
- Risques d’invention à éviter : ne pas annoncer des résultats ou gains qui ne seraient pas confirmés dans le développement.

### Sommaire, table des illustrations et tableaux

- Objectif de la section : permettre une lecture structurée du rapport.
- Contenu attendu : sommaire détaillé et numéroté, table des figures, table des tableaux.
- Critères IMT couverts : forme et structure, usage judicieux des illustrations.
- Éléments à compléter : pagination finale, numérotation finale des figures et tableaux.
- Risques d’invention à éviter : ne pas inscrire d’illustration non validée ou non présente.

## Introduction

Volume cible : 1 à 2 pages.

### Accroche et contexte général

- Objectif de la section : introduire l’alternance CI1 dans un contexte industriel où le système d’information soutient la continuité, la sécurité et les usages métiers.
- Contenu attendu : présentation courte de l’alternance, de Leroux, du service informatique et du rôle d’alternant administrateur systèmes et réseaux.
- Critères IMT couverts : introduction soignée, présentation du contexte, clarté du propos.
- Éléments à compléter : description officielle de Leroux, formulation validée du service informatique.
- Risques d’invention à éviter : ne pas inventer l’activité précise, les chiffres clés, l’historique ou l’organisation interne de Leroux.

### Sujet, objectifs et fil conducteur

- Objectif de la section : annoncer la logique du rapport et le niveau CI1 attendu.
- Contenu attendu : fil conducteur, objectifs du rapport, lien avec la première année d’apprentissage.
- Critères IMT couverts : plan cohérent, démarche réflexive, bilan de première année.
- Éléments à compléter : validation du fil conducteur par l’étudiant et, si nécessaire, par l’encadrement.
- Risques d’invention à éviter : ne pas présenter l’étudiant comme responsable principal du SI ou comme décideur unique.

### Annonce du plan

- Objectif de la section : guider le lecteur vers les cinq parties du développement.
- Contenu attendu : présentation synthétique des parties I à V.
- Critères IMT couverts : structure du rapport, clarté, progression logique.
- Éléments à compléter : formulation finale après validation du plan.
- Risques d’invention à éviter : ne pas annoncer une partie ou une mission qui ne sera pas réellement traitée.

## Partie I — Présentation de Leroux et du service informatique

Volume cible : 6 à 8 pages.

### I.1 — Présentation générale de Leroux

- Objectif de la section : situer l’entreprise avant d’aborder les missions informatiques.
- Contenu attendu : activité, secteur, histoire, culture, valeurs, appartenance éventuelle à un groupe, chiffres clés publics et sources.
- Critères IMT couverts : présentation de l’entreprise, contexte économique et organisationnel, clarté du propos.
- Éléments à compléter : secteur exact, activité exacte, chiffres clés publics, sources publiques, éléments historiques autorisés.
- Risques d’invention à éviter : ne pas inventer chiffres, dates, clients, partenaires, concurrents, valeurs ou historique.

### I.2 — Environnement industriel et enjeux numériques

- Objectif de la section : expliquer pourquoi le SI est important dans le fonctionnement de l’entreprise.
- Contenu attendu : continuité de service, disponibilité des outils métiers, support utilisateurs, sécurité, modernisation progressive.
- Critères IMT couverts : compréhension du contexte global de travail, présentation du contexte technologique.
- Éléments à compléter : exemples d’applications métiers ou de contraintes industrielles validés.
- Risques d’invention à éviter : ne pas détailler d’architecture interne, de processus industriels ou de contraintes réglementaires sans validation.

### I.3 — Organisation et métiers en interaction avec le service informatique

- Objectif de la section : montrer comment le service informatique s’insère dans l’organisation.
- Contenu attendu : organisation générale, principaux services en interaction, types de demandes ou besoins numériques.
- Critères IMT couverts : organisation, processus, métiers avec lesquels l’étudiant interagit.
- Éléments à compléter : organigramme utilisable, services en interaction, métiers concernés.
- Risques d’invention à éviter : ne pas créer d’organigramme, de rattachement ou de processus non validé.

### I.4 — Présentation du service informatique

- Objectif de la section : présenter le service dans lequel l’étudiant travaille.
- Contenu attendu : missions du service, périmètre général, taille de l’équipe, organisation, rôle du maître d’apprentissage.
- Critères IMT couverts : présentation du service, organisation, intégration de l’étudiant.
- Éléments à compléter : description exacte du service, taille de l’équipe, fonctions, rattachement, nom et rôle du maître d’apprentissage.
- Risques d’invention à éviter : ne pas surdécrire les responsabilités du service ou nommer des personnes sans validation.

### I.5 — Positionnement de l’étudiant en CI1

- Objectif de la section : clarifier le rôle réel de l’étudiant et son niveau d’autonomie.
- Contenu attendu : alternant administrateur systèmes et réseaux, découverte progressive de l’environnement, participation aux projets, support, documentation, échanges avec l’équipe.
- Critères IMT couverts : intégration, développement du positionnement dans la structure, bilan réflexif.
- Éléments à compléter : exemples concrets d’interactions et de responsabilités réellement assumées.
- Risques d’invention à éviter : ne pas présenter l’étudiant comme responsable unique d’un projet ou décideur principal.

## Partie II — Missions réalisées

Volume cible : 12 à 16 pages.

Méthode commune à chaque mission principale :

1. Contexte
2. Objectifs
3. Contraintes
4. Déroulement
5. Moyens et ressources mobilisés
6. Difficultés rencontrées
7. Solutions apportées
8. Résultats obtenus
9. Recul personnel

### II.1 — Microsoft Intune / Android Enterprise

Volume cible : 4 à 5 pages.

- Objectif de la section : montrer comment l’étudiant a participé à la préparation d’une gestion plus homogène et sécurisée de tablettes Android professionnelles.
- Contenu attendu : contexte des tablettes, objectifs de standardisation, mode Android Enterprise fully managed, configuration Intune, restrictions, applications, tests, documentation.
- Critères IMT couverts : présentation des missions, étapes de réalisation, méthodes et outils, moyens mobilisés, difficultés et solutions, résultats, recul personnel.
- Éléments à compléter : tests réalisés, validation réelle de la configuration, procédure interne, nombre de tablettes si autorisé, date ou période de la mission.
- Risques d’invention à éviter : ne pas annoncer de déploiement généralisé, de volume de tablettes, de gain mesuré ou de validation production sans preuve.

Plan interne conseillé :

- Contexte : tablettes Android professionnelles, besoin d’administration homogène.
- Objectifs : standardisation, sécurité, simplicité d’usage, préparation du parc mobile.
- Contraintes : plage de mise à jour, mot de passe, effacement après échecs, restrictions d’usage, tests avant production.
- Déroulement : découverte d’Intune, préparation du mode fully managed, token d’enrôlement, groupe, applications, restrictions, tests.
- Moyens et ressources : Intune, Android Enterprise, tablettes, équipe informatique, documentation.
- Difficultés : compréhension des profils, groupes, restrictions, validation des paramètres appliqués.
- Solutions : tests progressifs, centralisation, documentation, ajustement des restrictions.
- Résultats : configuration préparée ou validée `[À vérifier]`, standardisation `[À vérifier]`, sécurité renforcée `[À vérifier]`.
- Recul personnel : montée en compétence MDM, équilibre sécurité / usage, importance des tests.

### II.2 — Registre visiteurs Power Apps / SharePoint / Power Automate

Volume cible : 5 à 6 pages.

- Objectif de la section : présenter la création d’un registre visiteurs numérique simple, traçable et utilisable sur tablette.
- Contenu attendu : remplacement du registre papier, Power Apps, liste SharePoint `Registre visiteurs`, Power Automate, signature PNG en pièce jointe, diagnostic des erreurs.
- Critères IMT couverts : présentation des missions, étapes de réalisation, méthodes et outils, gestion des ressources, difficultés et solutions, analyse des résultats.
- Éléments à compléter : tablette utilisée, utilisateurs ou service concerné, date de mise en service si validée, niveau de suppression du papier, fiabilité finale du flow.
- Risques d’invention à éviter : ne pas inclure de données visiteurs réelles, ne pas annoncer suppression totale du papier ou automatisation définitivement validée sans confirmation.

Plan interne conseillé :

- Contexte : besoin de registre visiteurs numérique à l’entrée de l’entreprise.
- Objectifs : centralisation, traçabilité, signature obligatoire, simplification de l’enregistrement.
- Contraintes : simplicité sur tablette, confidentialité des données visiteurs, gestion fiable de la signature.
- Déroulement : création du formulaire, champs SharePoint, dropdowns d’heures, date automatique, signature, appel du flow, création de l’élément et pièce jointe.
- Moyens et ressources : Power Apps, SharePoint, Power Automate, liste `Registre visiteurs`, historique d’exécution du flow, équipe informatique.
- Difficultés : signature vide, PNG cassé, conversion Data URI / base64, paramètre `pSignatureJson` à `null`, confusion texte / expression.
- Solutions : conversion JSON avec données binaires, seuil empirique de signature, nettoyage de la Data URI, `dataUriToBinary`, analyse de l’historique du flow.
- Résultats : centralisation dans SharePoint, signature obligatoire, meilleure traçabilité `[À vérifier]`, automatisation fiable `[À vérifier]`.
- Recul personnel : diagnostic progressif, importance des tests, transformation d’une saisie utilisateur en donnée exploitable.

### II.3 — Sécurité opérationnelle AD / Microsoft 365

Volume cible : 4 à 5 pages.

- Objectif de la section : montrer l’apprentissage d’une démarche d’investigation prudente sur des événements de sécurité ou de verrouillage de comptes.
- Contenu attendu : contexte AD local + Microsoft / Entra `[À vérifier]`, connexions suspectes, verrouillages AD, événements 4740, 4776, 4625, code `0xc0000234`, collecte et corrélation de journaux.
- Critères IMT couverts : démarche ingénieur, difficultés et solutions, analyse des résultats, gestion des moyens, recul personnel, confidentialité.
- Éléments à compléter : chronologie exacte, outils précis, exemples anonymisés, causes réellement validées, résultats confirmés.
- Risques d’invention à éviter : ne pas publier de journaux bruts, noms de comptes, noms de postes, IP internes ou attribution d’attaque non prouvée.

Plan interne conseillé :

- Contexte : participation à des analyses de sécurité opérationnelle.
- Objectifs : comprendre l’origine d’un verrouillage ou d’une connexion suspecte, recouper les sources, éviter les conclusions rapides.
- Contraintes : logs nombreux, symptômes non constants, confidentialité forte, prudence avant action.
- Déroulement : vérification de connexions, collecte côté contrôleur de domaine et poste, observation d’événements, comparaison d’hypothèses.
- Moyens et ressources : Active Directory, Microsoft 365 / Entra `[À vérifier]`, journaux Windows, équipe informatique, documentation.
- Difficultés : volume de logs, corrélation, symptômes variables, risque de conclure trop vite.
- Solutions : recoupement de journaux, analyse progressive, distinction symptôme / hypothèse / cause validée.
- Résultats : meilleure méthode de diagnostic, montée en compétence, cause identifiée sur certains cas `[À vérifier]`.
- Recul personnel : prudence en sécurité, méthode d’investigation, importance des preuves.

### II.4 — Mission secondaire optionnelle : socle Docker `prd-dkr01`

Volume cible : 0 à 1 page, uniquement si la décision finale confirme son intégration.

- Objectif de la section : citer un travail secondaire sans le transformer en mission principale.
- Contenu attendu : préparation d’un serveur Debian minimal comme base Docker, séparation OS / données Docker, test `hello-world`, limites non finalisées.
- Critères IMT couverts : méthodes et outils, ressources techniques, recul sur les limites.
- Éléments à compléter : décision finale d’intégration, niveau de détail autorisé, diffusion du hostname, mention de SFR Cloud Agility.
- Risques d’invention à éviter : ne pas centrer le rapport sur Docker, ne pas présenter reverse proxy, sauvegarde ou application finale comme finalisés, ne pas faire de Xibo une mission principale.

## Partie III — Méthodes, outils et ressources mobilisés

Volume cible : 3 à 5 pages.

### III.1 — Méthodes de travail

- Objectif de la section : montrer comment les missions ont été abordées de manière progressive et structurée.
- Contenu attendu : découverte, tests, documentation, échanges avec l’équipe, diagnostic par étapes, validation avant généralisation.
- Critères IMT couverts : présentation des méthodes, démarche ingénieur, étapes de réalisation, clarté.
- Éléments à compléter : exemples précis de documentation, procédures ou supports réellement produits.
- Risques d’invention à éviter : ne pas inventer une méthode formelle, un planning ou une procédure non utilisée.

### III.2 — Outils techniques mobilisés

- Objectif de la section : regrouper les outils sans répéter toute la Partie II.
- Contenu attendu : Microsoft 365, Active Directory, Intune, Android Enterprise, Power Apps, SharePoint, Power Automate, journaux Windows, outils de diagnostic.
- Critères IMT couverts : méthodes et outils utilisés, ressources techniques.
- Éléments à compléter : formulation exacte de l’environnement Microsoft / Entra, outils de diagnostic précis autorisés.
- Risques d’invention à éviter : ne pas lister d’outils non utilisés ou non validés.

### III.3 — Moyens et ressources

- Objectif de la section : répondre explicitement au critère IMT sur les moyens matériels, techniques, humains et financiers.
- Contenu attendu : ressources matérielles, ressources logicielles, accompagnement par l’équipe, documentation, contraintes de budget si connues.
- Critères IMT couverts : gestion des moyens et ressources, démarche ingénieur.
- Éléments à compléter : ressources humaines impliquées, contraintes financières ou absence d’information budgétaire.
- Risques d’invention à éviter : ne pas créer de budget, de coût ou d’arbitrage financier non confirmé.

### III.4 — Illustrations et supports prévus

- Objectif de la section : préparer un usage utile des schémas et tableaux.
- Contenu attendu : schémas simplifiés, tableaux de synthèse, captures anonymisées seulement si autorisées.
- Critères IMT couverts : usage judicieux des illustrations, clarté du propos, confidentialité.
- Éléments à compléter : illustrations autorisées par l’entreprise, niveau d’anonymisation, numérotation finale.
- Risques d’invention à éviter : ne pas intégrer de capture non anonymisée ou de schéma détaillant une architecture sensible.

## Partie IV — Bilan personnel et compétences développées

Volume cible : 4 à 6 pages.

### IV.1 — Bilan de la première année d’alternance

- Objectif de la section : prendre du recul sur l’intégration et la progression en CI1.
- Contenu attendu : découverte du service, adaptation au contexte industriel, évolution de l’autonomie, compréhension du rôle d’administrateur systèmes et réseaux.
- Critères IMT couverts : bilan personnel, intégration, positionnement dans la structure.
- Éléments à compléter : exemples concrets vécus par l’étudiant.
- Risques d’invention à éviter : ne pas généraliser avec des phrases qui pourraient appartenir à n’importe quel rapport.

### IV.2 — Compétences techniques développées

- Objectif de la section : relier les missions à des compétences techniques réellement mobilisées.
- Contenu attendu : gestion de terminaux mobiles, Power Platform, SharePoint, automatisation, AD / Microsoft 365, analyse de logs, documentation.
- Critères IMT couverts : connaissances utilisées, savoir-faire développés, méthodes et outils.
- Éléments à compléter : niveau réel d’autonomie sur chaque outil, exemples précis.
- Risques d’invention à éviter : ne pas se présenter comme expert ou responsable d’architecture si ce n’est pas le cas.

### IV.3 — Compétences humaines et organisationnelles

- Objectif de la section : montrer les savoir-être développés en entreprise.
- Contenu attendu : communication avec l’équipe, prudence, écoute des utilisateurs, rigueur, documentation, patience dans le diagnostic.
- Critères IMT couverts : savoir-être, intégration, prise de recul.
- Éléments à compléter : situations concrètes sans données personnelles.
- Risques d’invention à éviter : ne pas citer d’utilisateurs ou d’incidents identifiables.

### IV.4 — Difficultés personnelles et axes de progrès

- Objectif de la section : rendre le bilan crédible et réflexif.
- Contenu attendu : difficultés d’apprentissage, compréhension des outils, gestion de la complexité, axes d’amélioration pour la suite.
- Critères IMT couverts : bilan personnel, axes de progrès, démarche réflexive.
- Éléments à compléter : difficultés réellement rencontrées et formulation personnelle.
- Risques d’invention à éviter : ne pas transformer les difficultés en réussites exagérées.

## Partie V — Perspectives d’évolution

Volume cible : 1 à 2 pages.

### V.1 — Suites possibles des missions principales

- Objectif de la section : présenter les perspectives sans promettre de résultats non validés.
- Contenu attendu : poursuite des tests Intune, amélioration du registre visiteurs, consolidation de la méthode de diagnostic sécurité.
- Critères IMT couverts : perspectives futures et améliorations possibles, démarche ingénieur.
- Éléments à compléter : décisions réelles de l’entreprise, priorités validées, suites planifiées.
- Risques d’invention à éviter : ne pas annoncer de roadmap officielle ou de déploiement futur non confirmé.

### V.2 — Progression envisagée comme apprenti ingénieur

- Objectif de la section : faire le lien entre l’année CI1 et la suite de l’alternance.
- Contenu attendu : autonomie progressive, approfondissement technique, documentation, meilleure compréhension des enjeux SI, posture d’ingénieur.
- Critères IMT couverts : bilan personnel, perspectives, développement des compétences.
- Éléments à compléter : objectifs personnels réels pour la suite.
- Risques d’invention à éviter : ne pas formuler d’engagements ou de responsabilités non actés.

## Conclusion

Volume cible : 1 à 2 pages.

### Synthèse du rapport

- Objectif de la section : répondre au fil conducteur sans répéter tout le développement.
- Contenu attendu : rappel du contexte, synthèse des trois missions principales, apport à la continuité, la sécurité et la modernisation du SI.
- Critères IMT couverts : conclusion soignée, clarté, structure.
- Éléments à compléter : résultats réellement validés et limites.
- Risques d’invention à éviter : ne pas conclure sur des gains non prouvés.

### Bilan réflexif final

- Objectif de la section : conclure sur la progression de l’étudiant en première année.
- Contenu attendu : apprentissages, posture, limites, axes de progrès.
- Critères IMT couverts : bilan personnel, prise de recul.
- Éléments à compléter : formulation personnelle finale.
- Risques d’invention à éviter : éviter les formulations trop génériques ou trop valorisantes.

## Bibliographie

Volume cible : selon sources utilisées, hors ou dans pagination selon format final.

- Objectif de la section : sourcer les éléments publics, techniques et méthodologiques.
- Contenu attendu : sources publiques Leroux, documentation Microsoft, documentation Power Platform, documentation Android Enterprise, références IMT si nécessaires.
- Critères IMT couverts : rigueur, absence d’invention, qualité du rapport.
- Éléments à compléter : URLs, dates de consultation, sources effectivement utilisées.
- Risques d’invention à éviter : ne pas citer de source non consultée ou non utilisée.

## Annexes

Volume cible : hors pagination principale.

### Annexe IA obligatoire

- Objectif de la section : déclarer l’usage potentiel de l’IA de manière transparente.
- Contenu attendu : usages réalisés, niveau d’intervention, validation humaine, impact environnemental ou bilan carbone.
- Critères IMT couverts : conformité IMT, intégrité académique.
- Éléments à compléter : description exacte des usages et estimation / source pour l’impact environnemental.
- Risques d’invention à éviter : ne pas minimiser ou inventer l’usage de l’IA.

### Annexes techniques éventuelles

- Objectif de la section : fournir des éléments utiles sans alourdir le corps du rapport.
- Contenu attendu : schémas simplifiés, tableaux de synthèse, procédures anonymisées si autorisées.
- Critères IMT couverts : usage judicieux des illustrations, clarté, confidentialité.
- Éléments à compléter : liste finale des annexes autorisées.
- Risques d’invention à éviter : ne pas inclure de captures, journaux, IP, noms de comptes ou architectures sensibles non validées.
