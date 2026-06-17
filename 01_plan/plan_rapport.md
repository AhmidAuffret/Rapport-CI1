# Plan détaillé du rapport CI1 Leroux

Statut : plan détaillé de travail, à valider avant rédaction finale.

Ce fichier ne constitue pas une rédaction finale du rapport. Il sert à cadrer la structure, les volumes, les critères IMT couverts, les informations à compléter et les risques d'invention à éviter.

Fil conducteur proposé :

> Comment une première année d’alternance en administration systèmes et réseaux permet-elle de contribuer à la continuité, à la sécurité et à la modernisation du système d’information d’une entreprise industrielle ?

Contraintes générales :

- rapport réflexif de première année CI1 ;
- cible de 25 à 40 pages hors annexes ;
- trois missions principales :
  - Microsoft Intune / Android Enterprise ;
  - registre visiteurs Power Apps / SharePoint / Power Automate ;
  - sécurité opérationnelle AD / Microsoft 365 ;
- Docker `prd-dkr01` uniquement comme mission secondaire ou optionnelle si la décision finale le confirme ;
- Xibo, uniFLOW et GLPI exclus comme missions principales ;
- aucune information inventée : utiliser `[À compléter]` ou `[À vérifier]` si nécessaire ;
- anonymisation systématique des éléments sensibles avec `[REDACTED]`.

## 1. Éléments préliminaires

- Objectif de la partie : fournir les éléments obligatoires avant le développement du rapport et installer un cadre professionnel de lecture.
- Contenu attendu : page de garde, remerciements, résumé français, abstract anglais, mots-clés, sommaire, table des figures et tableaux.
- Critères IMT couverts : forme et structure du rapport, clarté du propos, mise en forme professionnelle, conformité aux attendus minimaux.
- Volume cible : hors pagination principale ou selon format final imposé par l'école.
- Éléments à compléter : promotion exacte, titre définitif, logos autorisés, mention CONFIDENTIEL, personnes à remercier, pagination finale.
- Risques d’invention à éviter : ne pas inventer de titre validé, de promotion, de noms de personnes, de fonctions ou de résultats non encore rédigés.
- Illustrations possibles : logos IMT Nord Europe et Leroux uniquement si leur usage est autorisé ; aucune capture technique.

### 1.1 Page de garde

- Objectif de la section : identifier clairement le rapport, l’école, l’entreprise et l’étudiant.
- Contenu attendu : nom de l’apprenti, promotion, entreprise Leroux, titre définitif, année universitaire, logo IMT Nord Europe, logo Leroux si autorisé, mention CONFIDENTIEL si nécessaire.
- Critères IMT couverts : forme et structure du rapport, mise en forme professionnelle.
- Volume cible : 1 page hors développement.
- Éléments à compléter : promotion exacte, titre définitif, année universitaire, autorisation des logos, niveau de confidentialité.
- Risques d’invention à éviter : ne pas indiquer une promotion, un titre ou une mention de confidentialité non validés.
- Illustrations possibles : logos officiels autorisés.

### 1.2 Remerciements

- Objectif de la section : remercier les personnes ayant accompagné l’alternance.
- Contenu attendu : personnes à remercier, rôle dans l’accompagnement, raison concrète du remerciement.
- Critères IMT couverts : intégration dans l’entreprise, qualité de présentation, personnalisation du rapport.
- Volume cible : 0,5 à 1 page hors développement.
- Éléments à compléter : noms, postes, orthographe exacte, accord de citation, raisons précises des remerciements.
- Risques d’invention à éviter : ne pas citer de personne, fonction ou responsabilité sans validation.
- Illustrations possibles : aucune.

### 1.3 Résumé en français et mots-clés

- Objectif de la section : présenter brièvement le contexte, les missions principales et le bilan général.
- Contenu attendu : résumé en français, mots-clés liés à l’alternance, au SI industriel, à Intune, Power Platform et AD / Microsoft 365.
- Critères IMT couverts : clarté, structure, qualité rédactionnelle.
- Volume cible : 0,5 page hors développement.
- Éléments à compléter : formulation finale après rédaction complète du rapport.
- Risques d’invention à éviter : ne pas annoncer de résultat, de gain ou de déploiement non confirmé dans le corps du rapport.
- Illustrations possibles : aucune.

### 1.4 Abstract en anglais et keywords

- Objectif de la section : fournir l’équivalent anglais du résumé et des mots-clés.
- Contenu attendu : abstract en anglais cohérent avec le résumé français, keywords.
- Critères IMT couverts : structure, clarté, qualité de présentation.
- Volume cible : 0,5 page hors développement.
- Éléments à compléter : traduction finale après validation du résumé français.
- Risques d’invention à éviter : ne pas ajouter en anglais des informations absentes du résumé français.
- Illustrations possibles : aucune.

### 1.5 Sommaire

- Objectif de la section : permettre une lecture structurée du rapport.
- Contenu attendu : sommaire détaillé, numéroté, cohérent avec les cinq parties du développement, la conclusion, la bibliographie et les annexes.
- Critères IMT couverts : forme et structure du rapport, plan cohérent.
- Volume cible : hors développement, selon pagination finale.
- Éléments à compléter : numérotation et pages finales.
- Risques d’invention à éviter : ne pas afficher de partie ou d’annexe qui ne serait pas réellement présente.
- Illustrations possibles : aucune.

### 1.6 Table des figures et tableaux

- Objectif de la section : lister les illustrations utiles au rapport.
- Contenu attendu : table des figures, table des tableaux, titres explicites, numérotation finale.
- Critères IMT couverts : usage judicieux des illustrations, mise en forme professionnelle.
- Volume cible : hors développement, selon nombre final d’illustrations.
- Éléments à compléter : liste finale des schémas, tableaux et captures autorisés.
- Risques d’invention à éviter : ne pas référencer d’illustration non réalisée, non autorisée ou non anonymisée.
- Illustrations possibles : aucune dans cette section.

## 2. Introduction

- Objectif de la partie : introduire le contexte de l’alternance, les objectifs du rapport et la logique suivie.
- Contenu attendu : contexte général, rôle de l’étudiant, objectifs des missions, fil conducteur, annonce du plan.
- Critères IMT couverts : introduction soignée, contexte, structure, clarté du propos.
- Volume cible : 1 à 2 pages.
- Éléments à compléter : description officielle de Leroux, formulation validée du service informatique, titre définitif du rapport.
- Risques d’invention à éviter : ne pas inventer l’activité exacte de Leroux, des chiffres clés, une organisation interne ou des résultats de mission.
- Illustrations possibles : aucune, sauf très court schéma introductif si validé après rédaction.

### 2.1 Accroche et contexte général

- Objectif de la section : situer l’alternance CI1 dans un contexte industriel où le SI soutient les usages métiers.
- Contenu attendu : présentation courte de Leroux, du service informatique et du rôle d’alternant administrateur systèmes et réseaux.
- Critères IMT couverts : présentation du contexte, intégration dans l’entreprise, clarté.
- Volume cible : 0,5 page.
- Éléments à compléter : activité exacte de Leroux, éléments publics utilisables, description validée du service.
- Risques d’invention à éviter : ne pas créer d’historique, de chiffres ou de processus internes non sourcés.
- Illustrations possibles : aucune.

### 2.2 Sujet, objectifs et fil conducteur

- Objectif de la section : annoncer la question directrice et expliquer pourquoi elle correspond au rapport CI1.
- Contenu attendu : fil conducteur, objectifs du rapport, lien avec la découverte de l’entreprise et le bilan de première année.
- Critères IMT couverts : structure, démarche réflexive, bilan de première année.
- Volume cible : 0,5 page.
- Éléments à compléter : validation du fil conducteur par l’étudiant et l’encadrement si nécessaire.
- Risques d’invention à éviter : ne pas présenter l’étudiant comme responsable unique du SI ou décideur principal.
- Illustrations possibles : aucune.

### 2.3 Annonce du plan

- Objectif de la section : guider le lecteur vers les cinq parties du développement.
- Contenu attendu : présentation synthétique de la partie entreprise, des missions, des méthodes, du bilan personnel et des perspectives.
- Critères IMT couverts : forme et structure, plan cohérent, clarté.
- Volume cible : 0,5 page.
- Éléments à compléter : formulation finale après validation du plan.
- Risques d’invention à éviter : ne pas annoncer une mission ou une annexe non retenue.
- Illustrations possibles : aucune.

## 3. Partie I - Présentation de Leroux et du service informatique

- Objectif de la partie : montrer la compréhension du contexte d’entreprise, de l’environnement industriel et du service informatique.
- Contenu attendu : présentation générale de Leroux, contexte industriel, organisation, service informatique, rôle de l’étudiant.
- Critères IMT couverts : présentation de l’entreprise, du service, de l’organisation, des métiers en interaction et du positionnement dans la structure.
- Volume cible : 6 à 8 pages.
- Éléments à compléter : sources publiques, chiffres clés, organigramme validé, description exacte de l’équipe informatique, interactions principales.
- Risques d’invention à éviter : ne pas inventer l’histoire, les valeurs, les clients, les partenaires, les chiffres clés, l’organisation ou les noms de responsables.
- Illustrations possibles : schéma simplifié du service informatique, organigramme anonymisé si autorisé, tableau court des enjeux SI.

### 3.1 Présentation générale de Leroux

- Objectif de la section : situer l’entreprise avant d’aborder les missions informatiques.
- Contenu attendu : activité, secteur, histoire, culture, valeurs, groupe ou filiales si applicable, chiffres clés publics et sources.
- Critères IMT couverts : présentation de l’entreprise, contexte économique et organisationnel.
- Volume cible : 1,5 à 2 pages.
- Éléments à compléter : secteur exact, activité exacte, chiffres clés publics, sources publiques, éléments historiques autorisés.
- Risques d’invention à éviter : ne pas inventer de dates, clients, partenaires, concurrents, valeurs ou chiffres.
- Illustrations possibles : frise historique uniquement si dates sourcées ; tableau de chiffres clés uniquement si sources publiques validées.

### 3.2 Environnement industriel

- Objectif de la section : expliquer les contraintes d’un SI dans une entreprise industrielle.
- Contenu attendu : continuité de service, disponibilité des outils métiers, support utilisateurs, sécurité, confidentialité, tests avant production.
- Critères IMT couverts : compréhension du contexte global de travail, contexte technologique, organisation des processus.
- Volume cible : 1 à 1,5 page.
- Éléments à compléter : exemples d’applications métiers ou de contraintes industrielles validés.
- Risques d’invention à éviter : ne pas détailler de processus industriel, d’architecture interne ou de contrainte réglementaire non validée.
- Illustrations possibles : schéma très simplifié des enjeux SI, sans architecture sensible.

### 3.3 Service informatique

- Objectif de la section : présenter le service dans lequel l’étudiant travaille.
- Contenu attendu : missions du service, périmètre général, taille de l’équipe, organisation, rattachement, interactions internes.
- Critères IMT couverts : présentation du service, organisation, métiers avec lesquels l’étudiant interagit.
- Volume cible : 1,5 à 2 pages.
- Éléments à compléter : description exacte de l’équipe, taille, fonctions, rattachement, rôle du maître d’apprentissage.
- Risques d’invention à éviter : ne pas surdécrire les responsabilités du service ou nommer des personnes sans validation.
- Illustrations possibles : schéma simplifié du service informatique avec fonctions ou `[REDACTED]`.

### 3.4 Rôle de l’étudiant dans l’organisation

- Objectif de la section : clarifier le positionnement réel de l’étudiant en CI1.
- Contenu attendu : alternant administrateur systèmes et réseaux, découverte progressive de l’environnement, participation aux projets, support, documentation, échanges avec l’équipe.
- Critères IMT couverts : intégration, positionnement dans la structure, bilan réflexif.
- Volume cible : 0,5 à 1 page.
- Éléments à compléter : exemples concrets d’interactions, niveau d’autonomie réel, responsabilités réellement assumées.
- Risques d’invention à éviter : ne pas présenter l’étudiant comme responsable unique d’un projet ou décideur principal.
- Illustrations possibles : mini-tableau des types d’activités, sans données personnelles.

## 4. Partie II - Missions réalisées

- Objectif de la partie : présenter les trois missions principales et montrer la démarche suivie, les difficultés, les solutions et les résultats.
- Contenu attendu : Intune / Android Enterprise, registre visiteurs Power Apps / SharePoint / Power Automate, sécurité opérationnelle AD / Microsoft 365.
- Critères IMT couverts : présentation des missions, étapes de réalisation, moyens et ressources, difficultés, solutions, analyse des résultats, démarche ingénieur.
- Volume cible : 12 à 16 pages.
- Éléments à compléter : dates ou périodes, étapes réellement réalisées, résultats mesurables disponibles, validations, exemples anonymisés.
- Risques d’invention à éviter : ne pas inventer de déploiement généralisé, de gains mesurés, de volumes, de dates, de validations de production ou de résolution définitive.
- Illustrations possibles : architectures simplifiées, chaîne de diagnostic, tableau de synthèse des missions, captures anonymisées uniquement si autorisées.

Structure commune à chaque mission principale :

1. Contexte
2. Objectifs
3. Contraintes
4. Déroulement
5. Moyens et ressources mobilisés
6. Difficultés rencontrées
7. Solutions apportées
8. Résultats obtenus
9. Recul personnel

### 4.1 Microsoft Intune / Android Enterprise

- Objectif de la section : montrer comment l’étudiant a participé à la préparation d’une gestion plus homogène et sécurisée de tablettes Android professionnelles.
- Contenu attendu : tablettes Android professionnelles, Intune, Android Enterprise fully managed, token d’enrôlement `android_tab_prod`, groupe `android_tab_production`, applications, restrictions, tests, documentation.
- Critères IMT couverts : missions, étapes de réalisation, méthodes et outils, moyens mobilisés, difficultés, solutions, résultats, recul personnel.
- Volume cible : 4 à 5 pages.
- Éléments à compléter : tests réalisés, validation réelle de la configuration, procédure interne, nombre de tablettes si autorisé, date ou période de la mission.
- Risques d’invention à éviter : ne pas annoncer de déploiement généralisé, de volume de tablettes, de gain mesuré ou de validation production sans preuve.
- Illustrations possibles : architecture Intune / Android Enterprise simplifiée ; tableau des objectifs, contraintes et paramètres ; capture anonymisée si autorisée.

Plan interne conseillé :

- Contexte : besoin d’administration homogène des tablettes Android professionnelles.
- Objectifs : standardisation, sécurité, simplicité d’usage, préparation du parc mobile.
- Contraintes : plage de mises à jour, mot de passe, effacement après échecs, restrictions d’usage, tests avant production.
- Déroulement : découverte d’Intune, préparation du mode fully managed, token d’enrôlement, groupe, applications, restrictions, tests.
- Moyens et ressources : Intune, Android Enterprise, tablettes Samsung Galaxy Tab S10 FE+, équipe informatique, documentation.
- Difficultés : compréhension des profils, groupes, restrictions, validation des paramètres appliqués.
- Solutions : tests progressifs, centralisation, documentation, ajustement des restrictions.
- Résultats : configuration préparée ou validée `[À vérifier]`, standardisation `[À vérifier]`, sécurité renforcée `[À vérifier]`.
- Recul personnel : montée en compétence MDM, équilibre sécurité / usage, importance des tests.

### 4.2 Registre visiteurs Power Apps / SharePoint / Power Automate

- Objectif de la section : présenter la création d’un registre visiteurs numérique simple, traçable et utilisable sur tablette.
- Contenu attendu : application Power Apps, liste SharePoint `Registre visiteurs`, flow `FLOW_CreateVisitorWithSignature`, signature PNG en pièce jointe, diagnostic des erreurs.
- Critères IMT couverts : missions, étapes de réalisation, méthodes et outils, gestion des ressources, difficultés, solutions, analyse des résultats.
- Volume cible : 5 à 6 pages.
- Éléments à compléter : tablette utilisée, utilisateurs ou service concerné, date de mise en service si validée, niveau réel de suppression du papier, fiabilité finale du flow.
- Risques d’invention à éviter : ne pas inclure de données visiteurs réelles, ne pas annoncer suppression totale du papier ou automatisation définitivement validée sans confirmation.
- Illustrations possibles : architecture Power Apps / SharePoint / Power Automate ; schéma du parcours d’un enregistrement ; tableau des champs sans données réelles.

Plan interne conseillé :

- Contexte : besoin de registre visiteurs numérique à l’entrée de l’entreprise.
- Objectifs : centralisation, traçabilité, signature obligatoire, simplification de l’enregistrement.
- Contraintes : simplicité sur tablette, confidentialité des données visiteurs, gestion fiable de la signature.
- Déroulement : formulaire, champs SharePoint, dropdowns d’heures, date automatique, signature, appel du flow, création de l’élément et pièce jointe.
- Moyens et ressources : Power Apps, SharePoint, Power Automate, liste `Registre visiteurs`, historique d’exécution du flow, équipe informatique.
- Difficultés : signature vide, PNG cassé, conversion Data URI / base64, paramètre `pSignatureJson` à `null`, confusion texte / expression.
- Solutions : conversion JSON avec données binaires, seuil empirique de signature, nettoyage de la Data URI, `dataUriToBinary`, analyse de l’historique du flow.
- Résultats : centralisation dans SharePoint, signature obligatoire, meilleure traçabilité `[À vérifier]`, automatisation fiable `[À vérifier]`.
- Recul personnel : diagnostic progressif, importance des tests, transformation d’une saisie utilisateur en donnée exploitable.

### 4.3 Sécurité opérationnelle AD / Microsoft 365

- Objectif de la section : montrer l’apprentissage d’une démarche d’investigation prudente sur des événements de sécurité ou de verrouillage de comptes.
- Contenu attendu : environnement AD local + Microsoft / Entra `[À vérifier]`, connexions suspectes, verrouillages AD, événements 4740, 4776, 4625, code `0xc0000234`, collecte et corrélation de journaux.
- Critères IMT couverts : démarche ingénieur, difficultés et solutions, analyse des résultats, gestion des moyens, recul personnel, confidentialité.
- Volume cible : 4 à 5 pages.
- Éléments à compléter : chronologie exacte, outils précis, exemples anonymisés, causes réellement validées, résultats confirmés.
- Risques d’invention à éviter : ne pas publier de journaux bruts, noms de comptes, noms de postes, IP internes ou attribution d’attaque non prouvée.
- Illustrations possibles : chaîne de diagnostic sécurité AD / Microsoft 365 ; tableau symptôme / hypothèse / vérification / conclusion ; aucun log brut.

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

### 4.4 Mission secondaire optionnelle : socle Docker `prd-dkr01`

- Objectif de la section : citer un travail secondaire sans le transformer en mission principale, uniquement si la décision finale le confirme.
- Contenu attendu : préparation d’un serveur Debian minimal comme base Docker, séparation OS / données Docker, test `hello-world`, limites non finalisées.
- Critères IMT couverts : méthodes et outils, ressources techniques, recul sur les limites.
- Volume cible : 0 à 1 page, intégrée seulement si elle ne déséquilibre pas la Partie II.
- Éléments à compléter : décision finale d’intégration, niveau de détail autorisé, diffusion du hostname, mention de SFR Cloud Agility.
- Risques d’invention à éviter : ne pas centrer le rapport sur Docker, ne pas présenter reverse proxy, sauvegarde ou application finale comme finalisés, ne pas faire de Xibo une mission principale.
- Illustrations possibles : aucune par défaut ; tableau court de mission secondaire si retenue.

## 5. Partie III - Méthodes, outils et ressources mobilisés

- Objectif de la partie : expliquer la manière de travailler et les ressources utilisées sans répéter toute la Partie II.
- Contenu attendu : méthodes de travail, outils techniques, moyens humains, matériels, documentaires et financiers si connus, illustrations prévues.
- Critères IMT couverts : présentation des méthodes et outils, gestion des moyens et ressources, démarche ingénieur, clarté.
- Volume cible : 3 à 5 pages.
- Éléments à compléter : procédures réellement produites, ressources humaines impliquées, contraintes financières ou absence d’information budgétaire, outils précis autorisés.
- Risques d’invention à éviter : ne pas inventer de méthode formelle, planning, budget, arbitrage financier ou outil non utilisé.
- Illustrations possibles : tableau de synthèse des outils et ressources ; tableau des méthodes par mission.

### 5.1 Méthodes de travail

- Objectif de la section : montrer comment les missions ont été abordées de manière progressive.
- Contenu attendu : découverte, tests, documentation, échanges avec l’équipe, diagnostic par étapes, validation avant généralisation.
- Critères IMT couverts : méthodes utilisées, démarche ingénieur, étapes de réalisation.
- Volume cible : 1 page.
- Éléments à compléter : exemples précis de documentation, procédures ou supports réellement produits.
- Risques d’invention à éviter : ne pas inventer une méthode projet ou un planning non utilisé.
- Illustrations possibles : tableau méthode / mission / exemple.

### 5.2 Outils techniques mobilisés

- Objectif de la section : regrouper les outils utilisés dans les missions principales.
- Contenu attendu : Microsoft 365, Active Directory, Intune, Android Enterprise, Power Apps, SharePoint, Power Automate, journaux Windows, outils de diagnostic.
- Critères IMT couverts : méthodes et outils utilisés, ressources techniques.
- Volume cible : 1 à 1,5 page.
- Éléments à compléter : formulation exacte de l’environnement Microsoft / Entra, outils de diagnostic précis autorisés.
- Risques d’invention à éviter : ne pas lister d’outils non utilisés ou non validés.
- Illustrations possibles : tableau des outils par mission et usage.

### 5.3 Moyens et ressources

- Objectif de la section : répondre explicitement au critère IMT sur les moyens matériels, techniques, humains et financiers.
- Contenu attendu : ressources matérielles, logicielles, humaines, documentaires, contraintes financières si connues.
- Critères IMT couverts : gestion des moyens et ressources, démarche ingénieur.
- Volume cible : 1 à 1,5 page.
- Éléments à compléter : ressources humaines impliquées, contraintes financières ou mention `[À compléter]` si l’information n’est pas disponible.
- Risques d’invention à éviter : ne pas créer de budget, de coût, de décision d’achat ou d’arbitrage non confirmé.
- Illustrations possibles : tableau synthétique des ressources mobilisées.

### 5.4 Illustrations et supports prévus

- Objectif de la section : préparer un usage utile des schémas et tableaux.
- Contenu attendu : schémas simplifiés, tableaux de synthèse, captures anonymisées seulement si autorisées.
- Critères IMT couverts : usage judicieux des illustrations, clarté, confidentialité.
- Volume cible : 0,5 à 1 page.
- Éléments à compléter : illustrations autorisées par l’entreprise, niveau d’anonymisation, numérotation finale.
- Risques d’invention à éviter : ne pas intégrer de capture non anonymisée ou de schéma détaillant une architecture sensible.
- Illustrations possibles : liste commentée des cinq schémas utiles définis dans `03_annexes/schemas_a_prevoir.md`.

## 6. Partie IV - Bilan personnel et compétences développées

- Objectif de la partie : répondre au caractère réflexif du rapport CI1 en montrant la progression de l’étudiant.
- Contenu attendu : bilan de la première année, compétences techniques, compétences humaines et organisationnelles, difficultés personnelles, axes de progrès.
- Critères IMT couverts : bilan personnel, connaissances utilisées, savoir-être, savoir-faire, points forts, axes de progrès, positionnement dans la structure.
- Volume cible : 4 à 6 pages.
- Éléments à compléter : exemples personnels réels, niveau d’autonomie réel, difficultés vécues, axes de progression.
- Risques d’invention à éviter : ne pas produire un bilan générique, survalorisant ou déconnecté des missions réellement menées.
- Illustrations possibles : tableau compétences / missions / preuves ; aucun élément personnel sensible.

### 6.1 Bilan de la première année d’alternance

- Objectif de la section : prendre du recul sur l’intégration et la progression en CI1.
- Contenu attendu : découverte du service, adaptation au contexte industriel, évolution de l’autonomie, compréhension du rôle d’administrateur systèmes et réseaux.
- Critères IMT couverts : bilan personnel, intégration, positionnement.
- Volume cible : 1 à 1,5 page.
- Éléments à compléter : exemples concrets vécus par l’étudiant.
- Risques d’invention à éviter : éviter les phrases génériques sans lien avec l’expérience réelle.
- Illustrations possibles : aucune par défaut.

### 6.2 Compétences techniques développées

- Objectif de la section : relier les missions à des compétences techniques réellement mobilisées.
- Contenu attendu : gestion de terminaux mobiles, Power Platform, SharePoint, automatisation, AD / Microsoft 365, analyse de logs, documentation.
- Critères IMT couverts : connaissances utilisées, savoir-faire, méthodes et outils.
- Volume cible : 1 à 1,5 page.
- Éléments à compléter : niveau réel d’autonomie sur chaque outil, exemples précis.
- Risques d’invention à éviter : ne pas se présenter comme expert ou responsable d’architecture si ce n’est pas le cas.
- Illustrations possibles : tableau des compétences techniques par mission.

### 6.3 Compétences humaines et organisationnelles

- Objectif de la section : montrer les savoir-être développés en entreprise.
- Contenu attendu : communication avec l’équipe, prudence, écoute des utilisateurs, rigueur, documentation, patience dans le diagnostic.
- Critères IMT couverts : savoir-être, intégration, prise de recul.
- Volume cible : 1 page.
- Éléments à compléter : situations concrètes sans données personnelles.
- Risques d’invention à éviter : ne pas citer d’utilisateurs ou d’incidents identifiables.
- Illustrations possibles : aucune par défaut.

### 6.4 Difficultés personnelles et axes de progrès

- Objectif de la section : rendre le bilan crédible et réflexif.
- Contenu attendu : difficultés d’apprentissage, compréhension des outils, gestion de la complexité, axes d’amélioration pour la suite.
- Critères IMT couverts : bilan personnel, axes de progrès, démarche réflexive.
- Volume cible : 1 à 2 pages.
- Éléments à compléter : difficultés réellement rencontrées et formulation personnelle.
- Risques d’invention à éviter : ne pas transformer les difficultés en réussites exagérées.
- Illustrations possibles : tableau court des axes de progrès si utile.

## 7. Partie V - Perspectives d’évolution

- Objectif de la partie : présenter les suites possibles sans inventer de feuille de route officielle.
- Contenu attendu : pistes de poursuite des missions, améliorations possibles, progression envisagée comme apprenti ingénieur.
- Critères IMT couverts : perspectives futures, améliorations possibles, bilan personnel, démarche ingénieur.
- Volume cible : 1 à 2 pages.
- Éléments à compléter : priorités validées, décisions réelles de l’entreprise, objectifs personnels.
- Risques d’invention à éviter : ne pas présenter des pistes comme des décisions officielles ou des engagements de l’entreprise.
- Illustrations possibles : tableau court des perspectives, avec statut `[À vérifier]` si nécessaire.

### 7.1 Suites possibles des missions principales

- Objectif de la section : identifier des pistes de continuité pour les trois missions.
- Contenu attendu : poursuite des tests Intune, amélioration du registre visiteurs, consolidation de la méthode de diagnostic sécurité.
- Critères IMT couverts : perspectives futures, améliorations possibles.
- Volume cible : 0,5 à 1 page.
- Éléments à compléter : suites réellement envisagées ou validées.
- Risques d’invention à éviter : ne pas annoncer de déploiement futur ou de roadmap officielle non confirmée.
- Illustrations possibles : tableau mission / piste / statut.

### 7.2 Progression envisagée comme apprenti ingénieur

- Objectif de la section : faire le lien entre la CI1 et la suite de l’alternance.
- Contenu attendu : autonomie progressive, approfondissement technique, documentation, compréhension des enjeux SI, posture d’ingénieur.
- Critères IMT couverts : bilan personnel, perspectives, développement des compétences.
- Volume cible : 0,5 à 1 page.
- Éléments à compléter : objectifs personnels réels pour la suite.
- Risques d’invention à éviter : ne pas formuler de responsabilités futures non actées.
- Illustrations possibles : aucune.

## 8. Conclusion

- Objectif de la partie : répondre au fil conducteur et synthétiser le bilan sans ajouter d’information nouvelle.
- Contenu attendu : rappel du contexte, synthèse des trois missions, apports à la continuité, à la sécurité et à la modernisation du SI, recul personnel final.
- Critères IMT couverts : conclusion soignée, clarté, structure, bilan personnel.
- Volume cible : 1 à 2 pages.
- Éléments à compléter : résultats réellement validés, limites, formulation personnelle finale.
- Risques d’invention à éviter : ne pas conclure sur des gains non démontrés ou des résultats non traités dans le développement.
- Illustrations possibles : aucune.

### 8.1 Synthèse du rapport

- Objectif de la section : rappeler ce que les missions ont permis de comprendre ou de contribuer à faire.
- Contenu attendu : synthèse du contexte, des trois missions principales et de leur lien avec le fil conducteur.
- Critères IMT couverts : conclusion, clarté, cohérence.
- Volume cible : 0,5 à 1 page.
- Éléments à compléter : résultats confirmés et limites.
- Risques d’invention à éviter : ne pas ajouter de nouveau résultat.
- Illustrations possibles : aucune.

### 8.2 Bilan réflexif final

- Objectif de la section : conclure sur la progression de l’étudiant en première année.
- Contenu attendu : apprentissages, posture, limites, axes de progrès.
- Critères IMT couverts : bilan personnel, prise de recul.
- Volume cible : 0,5 à 1 page.
- Éléments à compléter : formulation personnelle finale.
- Risques d’invention à éviter : éviter les formulations trop génériques ou trop valorisantes.
- Illustrations possibles : aucune.

## 9. Bibliographie

- Objectif de la partie : sourcer les éléments publics, techniques et méthodologiques utilisés dans le rapport.
- Contenu attendu : sources publiques Leroux, documentation Microsoft, documentation Power Platform, documentation Android Enterprise, références IMT si nécessaires.
- Critères IMT couverts : rigueur, absence d’invention, qualité du rapport.
- Volume cible : selon sources utilisées, hors ou dans pagination selon format final.
- Éléments à compléter : URLs, dates de consultation, sources effectivement utilisées.
- Risques d’invention à éviter : ne pas citer de source non consultée, non utilisée ou non fiable.
- Illustrations possibles : aucune.

## 10. Annexes

- Objectif de la partie : fournir les éléments complémentaires utiles sans alourdir le corps du rapport.
- Contenu attendu : annexe IA obligatoire, schémas simplifiés, tableaux de synthèse, procédures anonymisées si autorisées.
- Critères IMT couverts : conformité IMT, usage judicieux des illustrations, clarté, confidentialité.
- Volume cible : hors pagination principale.
- Éléments à compléter : liste finale des annexes autorisées, niveau d’anonymisation, usage réel de l’IA, impact environnemental ou bilan carbone.
- Risques d’invention à éviter : ne pas inclure de captures, journaux, IP, noms de comptes, données visiteurs ou architectures sensibles non validées.
- Illustrations possibles : cinq schémas listés dans `03_annexes/schemas_a_prevoir.md`, sans données sensibles.

### 10.1 Annexe IA obligatoire

- Objectif de la section : déclarer l’usage potentiel de l’IA de manière transparente.
- Contenu attendu : usages réalisés, niveau d’intervention, validation humaine, impact environnemental ou bilan carbone.
- Critères IMT couverts : conformité IMT, intégrité académique.
- Volume cible : selon modèle final, hors développement.
- Éléments à compléter : description exacte des usages et source de l’estimation environnementale.
- Risques d’invention à éviter : ne pas minimiser, exagérer ou inventer l’usage de l’IA.
- Illustrations possibles : tableau des usages IA si utile.

### 10.2 Annexes techniques éventuelles

- Objectif de la section : fournir des supports utiles uniquement s’ils améliorent la compréhension.
- Contenu attendu : schémas simplifiés, tableaux de synthèse, procédures anonymisées si autorisées.
- Critères IMT couverts : usage judicieux des illustrations, clarté, confidentialité.
- Volume cible : selon éléments validés, hors développement.
- Éléments à compléter : schémas retenus, captures autorisées, niveau de détail technique autorisé.
- Risques d’invention à éviter : ne pas transformer les annexes en documentation interne complète ou exposer des informations sensibles.
- Illustrations possibles : schéma du service informatique, architecture Intune, architecture Power Platform, chaîne de diagnostic sécurité, tableau de synthèse des missions.
