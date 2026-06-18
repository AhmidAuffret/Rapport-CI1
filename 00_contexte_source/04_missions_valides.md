# Missions validées pour le rapport

Statut : contexte consolidé pour préparer le rapport, sans rédaction finale.

## Synthèse des choix

| Sujet | Statut | Utilisation dans le rapport |
| --- | --- | --- |
| Microsoft Intune / Android Enterprise | Mission principale | À développer comme mission principale |
| Registre visiteurs Power Apps / SharePoint / Power Automate | Mission principale | À développer comme mission principale |
| Sécurité opérationnelle AD / Microsoft 365 | Mission principale | À développer comme mission principale |
| Socle Docker `prd-dkr01` | Mission secondaire ou optionnelle | À utiliser seulement si le plan final le confirme |
| Xibo | Exclu comme mission principale | Citation courte possible uniquement |
| uniFLOW | Exclu comme mission principale | Citation courte possible uniquement |
| GLPI | Exclu comme mission principale | Citation courte ou lien possible uniquement |

## 1. Microsoft Intune / Android Enterprise

Statut : mission principale.

### Contexte

L'entreprise utilise des tablettes Android professionnelles. L'objectif est de les administrer de manière homogène et sécurisée avec Microsoft Intune et Android Enterprise.

La mission représente environ deux mois de travail au total. Cette durée comprend la prise en main de Microsoft Intune, la configuration de la tablette destinée au registre visiteurs à l'accueil et la configuration des tablettes utilisées en production.

Éléments connus :

- deux usages distincts :
  - tablette d'accueil pour le registre visiteurs ;
  - tablettes utilisées en production ;
- tablettes Samsung Galaxy Tab S10 FE+ ;
- Android 15 ;
- mode Android Enterprise fully managed ;
- token d'enrôlement : `android_tab_prod` ;
- groupe associé : `android_tab_production` ;
- applications prévues ou déployées : Word, Excel, PowerPoint, OneNote, Teams, Outlook, Collabora, Adobe Reader ;
- liens web possibles : GMAO, Fastilog, GLPI.

GLPI peut être cité uniquement comme lien ou outil consultable, jamais comme mission principale.

### Objectifs

- Standardiser la configuration des tablettes professionnelles.
- Sécuriser l'usage des appareils mobiles.
- Simplifier l'utilisation pour les utilisateurs.
- Préparer une gestion plus homogène du parc mobile.
- Tester les configurations avant une utilisation en production.

### Contraintes

- Plage de mises à jour : 03:00 à 05:00.
- Mot de passe : 8 caractères.
- Effacement après 10 échecs.
- Restrictions connues :
  - blocage du reset ;
  - blocage USB/supports externes ;
  - blocage hotspot ;
  - blocage des modifications Wi-Fi ;
  - blocage de l'ajout de comptes Google.
- Ne pas décrire de déploiement généralisé ou de résultat mesurable si ce n'est pas validé.

### Déroulement

Actions connues ou à exploiter :

- découverte de Microsoft Intune et d'Android Enterprise ;
- compréhension du besoin ;
- préparation du mode fully managed ;
- utilisation du token d'enrôlement `android_tab_prod` ;
- association au groupe `android_tab_production` ;
- configuration des restrictions ;
- configuration des applications ;
- enrôlement des tablettes ;
- tests et ajustements ;
- échanges avec les utilisateurs ou le tuteur ;
- documentation si nécessaire : `[À compléter si une procédure formelle a été produite]`.

Rôle de l'étudiant : gestion du processus de bout en bout sur la partie opérationnelle. Les choix techniques finaux et les décisions financières restent validés par le tuteur ou l'entreprise.

### Moyens et ressources mobilisés

- Microsoft Intune ;
- Android Enterprise ;
- tablettes Samsung Galaxy Tab S10 FE+ ;
- tablette d'accueil destinée au registre visiteurs ;
- tablettes de production ;
- compte ou accès d'administration : `[À vérifier]` ;
- équipe informatique ;
- documentation Microsoft ou documentation interne : `[À compléter]`.

### Difficultés rencontrées

- Compréhension initiale de Microsoft Intune et d'Android Enterprise.
- Distinction entre les profils, les groupes, les restrictions et les applications.
- Validation des paramètres réellement appliqués sur tablette : `[À compléter]`.
- Nécessité de tester avant toute généralisation.

### Solutions apportées

- Approche progressive par tests.
- Paramétrage de restrictions adaptées à un usage professionnel.
- Centralisation de la configuration dans Intune.
- Ajustements après tests et échanges avec les utilisateurs ou le tuteur.
- Documentation des points compris et des choix retenus : `[À compléter si une procédure formelle a été produite]`.

### Résultats obtenus

- Configuration Intune Android Enterprise mise en place sur la partie opérationnelle.
- Deux usages traités : tablette d'accueil pour le registre visiteurs et tablettes utilisées en production.
- Tablettes de production utilisées en production.
- Tablettes mieux standardisées : `[À vérifier pour formulation finale]`.
- Sécurité renforcée par restrictions et mot de passe : `[À vérifier pour formulation finale]`.
- Simplicité d'usage pour les utilisateurs : `[À vérifier pour formulation finale]`.

Ne pas inventer de volume de tablettes, de date de déploiement ou de gain mesuré.
Ne pas présenter l'étudiant comme décideur final des choix techniques structurants ou financiers.

### Recul personnel

Points à développer dans le rapport :

- montée en compétence sur la gestion de terminaux mobiles ;
- compréhension progressive d'Intune et d'Android Enterprise ;
- intérêt des tests avant production ;
- importance de trouver un équilibre entre sécurité et simplicité d'utilisation.

## 2. Registre visiteurs avec Power Apps, SharePoint et Power Automate

Statut : mission principale.

### Contexte

L'objectif est de remplacer un registre visiteurs papier par une application utilisée sur tablette à l'entrée de l'entreprise. La demande initiale est venue de Loïc Humman, alors tuteur et responsable informatique.

La mission a duré environ un mois.

Architecture connue :

- application Power Apps ;
- source de données : liste SharePoint `Registre visiteurs` ;
- création de l'enregistrement via Power Automate ;
- signature stockée comme pièce jointe PNG sur l'élément SharePoint.

### Objectifs

- Supprimer ou réduire l'usage du registre papier.
- Centraliser les passages visiteurs dans SharePoint.
- Rendre la signature obligatoire.
- Améliorer la traçabilité.
- Fiabiliser l'enregistrement avec une automatisation.

### Contraintes

- Conserver une utilisation simple sur tablette.
- Enregistrer les informations nécessaires sans collecter de données inutiles.
- Gérer correctement la signature.
- Respecter la confidentialité des données visiteurs.
- Ne pas inclure de données personnelles réelles dans le rapport.

### Déroulement

Colonnes principales connues :

- Nom ;
- Prénom ;
- Société ;
- PersonneVisitée ;
- HeureArrivee ;
- HeureDepart ;
- DateDePassage.

Éléments Power Apps connus :

- formulaire : `Formulaire` ;
- `DataCardValue1` : Nom ;
- `DataCardValue45` : Prénom ;
- `DataCardValue47` : Société ;
- `DataCardValue46` : PersonneVisitée ;
- `DataCardValue48` : DateDePassage ;
- date automatique : `Today()` ;
- date non modifiable : `DisplayMode.View` ;
- heures via dropdowns : `ddArrH`, `ddArrM`, `ddDepH`, `ddDepM` ;
- minutes par pas de 5 ;
- contrôle signature : `Pen_Signature` ;
- conversion signature : `JSON(Pen_Signature.Image, JSONFormat.IncludeBinaryData)` ;
- seuil empirique signature : environ 7000 caractères.

Flow Power Automate connu :

- nom : `FLOW_CreateVisitorWithSignature` ;
- trigger : Power Apps V2 ;
- paramètres :
  1. `pNom` ;
  2. `pPrenom` ;
  3. `pSociete` ;
  4. `pPersonneVisitee` ;
  5. `pHeureArrivee` ;
  6. `pHeureDepart` ;
  7. `pSignatureJson` ;
  8. `pDatedepass`.

Étapes connues du flow :

- création de l'élément SharePoint ;
- nettoyage de la Data URI ;
- condition vérifiant `data:image/` ;
- ajout de la pièce jointe `signature.png` ;
- conversion avec `dataUriToBinary`.

### Moyens et ressources mobilisés

- Power Apps ;
- SharePoint ;
- Power Automate ;
- tablette utilisée à l'entrée : tablette d'accueil destinée au registre visiteurs `[modèle exact à vérifier]` ;
- liste SharePoint `Registre visiteurs` ;
- historique d'exécution du flow ;
- équipe informatique ;
- utilisateurs ou service d'accueil concernés : accueil `[À compléter si un service précis doit être nommé]` ;
- service maintenance pour l'installation du support physique de la tablette.

### Difficultés rencontrées

- Signature vide générant une image blanche.
- PNG cassé lors des premiers essais.
- Mauvaise conversion base64 / Data URI.
- `pSignatureJson` reçu à `null`.
- Confusion entre texte et expression dans Power Automate.
- Nécessité d'utiliser l'historique d'exécution du flow.

### Solutions apportées

- Conversion de l'image de signature en JSON avec données binaires.
- Vérification empirique de la présence d'une signature.
- Nettoyage de la Data URI avant conversion.
- Utilisation de `dataUriToBinary` pour générer la pièce jointe.
- Contrôle de l'historique d'exécution Power Automate pour diagnostiquer les erreurs.

### Résultats obtenus

Résultats confirmés :

- partie applicative terminée ;
- application Power Apps fonctionnelle ;
- données enregistrées dans SharePoint ;
- flux Power Automate fonctionnel ;
- signature correctement enregistrée en pièce jointe PNG ;
- registre visiteurs numérique validé techniquement.

Limites et état de mise en service :

- le registre visiteurs numérique n'est pas encore utilisé à l'accueil ;
- la mise en service dépend du service maintenance, qui doit installer le support physique permettant de sécuriser la tablette à l'accueil et d'éviter les vols ;
- suppression du registre papier : non confirmée, ne pas l'annoncer comme réalisée.

Ne pas inventer de date de mise en service, de nombre de visiteurs ou de validation d'usage à l'accueil si ces éléments ne sont pas confirmés.

### Recul personnel

Points à développer dans le rapport :

- progression dans la compréhension de Power Apps et Power Automate ;
- importance du diagnostic par historique d'exécution ;
- difficulté de transformer une saisie utilisateur en donnée exploitable et fiable ;
- intérêt d'une solution simple pour un usage terrain.

## 3. Sécurité opérationnelle AD / Microsoft 365

Statut : mission principale.

### Contexte

L'étudiant a participé à des analyses liées à la sécurité opérationnelle des comptes et des postes : phishing, connexions suspectes, verrouillage de comptes AD et incidents d'authentification.

Cette mission ne doit pas être présentée comme un projet unique. Il s'agit d'une mission continue liée aux incidents et demandes quotidiennes du service informatique. Elle doit être présentée comme un travail de diagnostic, d'analyse et de méthode, pas comme un projet fermé.

Éléments connus :

- environnement hybride AD local + Microsoft / Entra ;
- vérification de connexions ;
- analyse de journaux ;
- cas de verrouillage AD ;
- problèmes d'authentification ;
- vérification de postes utilisateurs ;
- vérification Microsoft 365 / Entra ;
- incidents liés au Wi-Fi, au NPS ou à des mots de passe enregistrés ;
- événements observés : 4740, 4776, 4625 ;
- code observé : `0xc0000234` ;
- collecte de logs côté contrôleur de domaine et poste utilisateur ;
- comparaison du comportement selon l'état de session utilisateur.

### Objectifs

- Comprendre l'origine d'un verrouillage ou d'une connexion suspecte.
- Éviter les conclusions rapides.
- Recouper plusieurs sources de logs.
- Distinguer problème poste, service, ancien mot de passe, équipement ou tentative extérieure.
- Proposer des actions adaptées.

### Contraintes

- Logs nombreux et parfois difficiles à corréler.
- Symptômes non constants.
- Prudence nécessaire avant modification d'un compte ou d'un poste.
- Confidentialité forte sur les comptes, journaux et événements.
- Ne pas publier de journaux bruts contenant des données sensibles.

### Déroulement

Actions connues :

- vérification de connexions ;
- analyse de journaux ;
- collecte de logs côté contrôleur de domaine ;
- collecte de logs côté poste utilisateur ;
- vérification de postes utilisateurs ;
- vérification Microsoft 365 / Entra ;
- diagnostic d'incidents liés au Wi-Fi, au NPS ou à des mots de passe enregistrés ;
- observation d'événements 4740, 4776 et 4625 ;
- prise en compte du code `0xc0000234` ;
- comparaison de plusieurs hypothèses ;
- comparaison selon l'état de session utilisateur.

Étapes exactes, outils précis et chronologie : `[À compléter]`.

### Moyens et ressources mobilisés

- Active Directory ;
- Microsoft 365 / Entra : `[À vérifier pour la formulation exacte]` ;
- journaux d'événements Windows ;
- contrôleur de domaine : nom à anonymiser ou remplacer par `[REDACTED]` ;
- poste utilisateur : nom à anonymiser ou remplacer par `[REDACTED]` ;
- échanges avec l'équipe informatique ;
- documentation Microsoft ou documentation interne : `[À compléter]`.

### Difficultés rencontrées

- Volume important de logs.
- Corrélation difficile entre plusieurs sources.
- Symptômes non constants.
- Risque de conclure trop vite.
- Besoin de tester plusieurs hypothèses.

### Solutions apportées

- Recoupement de plusieurs journaux.
- Analyse progressive des événements.
- Comparaison entre poste utilisateur et contrôleur de domaine.
- Vérification avant action sur un compte ou un poste.
- Formulation d'hypothèses plutôt que conclusion non démontrée.

### Résultats obtenus

Résultats à présenter avec prudence :

- meilleure méthode de diagnostic ;
- montée en compétence sur AD / Microsoft 365 ;
- meilleure compréhension des incidents sécurité ;
- prise de recul sur l'importance des logs ;
- résolution ou traitement ponctuel de certains incidents : `[À vérifier au cas par cas]` ;
- cause identifiée sur certains cas : `[À vérifier avant toute formulation définitive]`.

Ne pas inventer de volume d'incidents, de résolution définitive ou d'attribution d'une attaque si cela n'est pas confirmé.
Ne pas présenter cette mission comme un projet fermé avec une date de début et de fin unique.

### Recul personnel

Points à développer dans le rapport :

- apprentissage d'une démarche d'investigation ;
- importance de la prudence en sécurité ;
- nécessité de croiser les sources ;
- distinction entre symptôme, hypothèse et cause validée.

## 4. Socle Docker `prd-dkr01`

Statut : mission secondaire ou optionnelle.

### Contexte

Un serveur Debian minimal a été préparé comme hôte Docker propre et maintenable.

Éléments connus :

- hostname : `prd-dkr01` ;
- VM SFR Cloud Agility ;
- Debian 13 minimal ;
- administration SSH avec `adm-dkr` ;
- root SSH interdit ;
- Docker installé depuis le dépôt officiel ;
- test `hello-world` validé ;
- séparation OS / données Docker ;
- disque de données monté sur `/var/lib/docker` ;
- `containerd` déplacé sous `/var/lib/docker/containerd-root` ;
- utilisation de `sudo docker` ;
- compte non ajouté au groupe Docker.

### Objectifs

- Préparer un socle Docker propre et maintenable.
- Séparer l'OS et les données Docker.
- Limiter les risques liés aux accès d'administration.
- Poser une base technique exploitable plus tard.

### Actions connues

- préparation d'une VM Debian minimale ;
- configuration SSH avec root interdit ;
- installation de Docker depuis le dépôt officiel ;
- validation avec `hello-world` ;
- montage du disque de données sur `/var/lib/docker` ;
- déplacement de `containerd` sous `/var/lib/docker/containerd-root`.

### Outils utilisés

- Debian 13 ;
- Docker ;
- SSH ;
- SFR Cloud Agility ;
- commandes d'administration système : `[À compléter]`.

### Difficultés

- Reverse proxy non finalisé.
- Sauvegarde non finalisée.
- Pas de déploiement applicatif final à présenter comme mission principale.
- Risque de centrer le sujet sur Xibo, ce qui est interdit pour une mission principale.

### Résultats attendus ou obtenus

- Socle Docker initial validé par le test `hello-world`.
- Séparation OS / données Docker mise en place.
- Base d'administration plus propre.
- Exploitation en mission principale : non validée.

### Points à compléter

- Décider si Docker reste dans le rapport comme mission secondaire.
- Préciser le niveau de détail autorisé.
- Vérifier si le hostname `prd-dkr01` peut être conservé ou doit être remplacé par `[REDACTED]`.
- Confirmer si la VM SFR Cloud Agility peut être citée.

### Risques d'invention à éviter

- Ne pas présenter Docker comme mission principale.
- Ne pas présenter Xibo comme objectif central.
- Ne pas affirmer qu'un reverse proxy, une sauvegarde ou une application finale ont été finalisés.
- Ne pas inventer de gain de performance ou de disponibilité.
