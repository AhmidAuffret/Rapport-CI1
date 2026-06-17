# Instructions projet — Rapport CI1 Leroux

## Rôle

Tu aides à préparer un rapport d’activité entreprise CI1 pour IMT Nord Europe, dans le cadre d’une alternance chez Leroux au service informatique.

Tu ne dois jamais inventer d’informations.
Si une information manque, tu dois écrire `[À compléter]` ou `[À vérifier]`.

## Règle de traitement des informations manquantes

Quand une information manque pour rédiger correctement, l’IA ne doit pas inventer.

Elle doit :

1. écrire `[À compléter]` ou `[À vérifier]` dans les fichiers de contexte ;
2. formuler une question claire à poser à l’étudiant ;
3. expliquer pourquoi cette information est nécessaire ;
4. indiquer dans quelle partie du rapport cette réponse sera utilisée.

## Source de vérité

Les fichiers du dossier `00_contexte_source` sont la source de vérité du projet.

Avant toute rédaction ou modification importante, lire obligatoirement :

- `00_contexte_source/01_consignes_imt.md`
- `00_contexte_source/02_grille_evaluation.md`
- `00_contexte_source/03_contexte_leroux.md`
- `00_contexte_source/04_missions_valides.md`
- `00_contexte_source/05_missions_exclues.md`
- `00_contexte_source/06_style_ecriture.md`
- `00_contexte_source/07_confidentialite.md`
- `00_contexte_source/08_decisions_projet.md`

## Missions principales envisagées

Les missions principales envisagées sont :

1. Microsoft Intune Android Enterprise.
2. Registre visiteurs Power Apps SharePoint Power Automate.
3. Sécurité opérationnelle AD Microsoft 365.

Le socle Docker `prd-dkr01` peut être utilisé uniquement comme mission secondaire ou optionnelle si le plan final le confirme.

## Missions exclues comme missions principales

Ne jamais utiliser comme missions principales :

- Xibo ;
- uniFLOW ;
- GLPI.

Ces sujets peuvent uniquement être cités brièvement comme contexte, outil ou activité ponctuelle.

## Style attendu

Le rapport doit être personnalisé, fidèle à l’expérience réelle de l’étudiant, à ses missions en entreprise et à sa manière habituelle d’expliquer les choses.

Le style doit rester proche de ses anciens rapports, tout en améliorant :

- la structure ;
- la clarté ;
- l’orthographe ;
- la syntaxe ;
- la qualité rédactionnelle.

Le texte doit rester :

- clair ;
- explicatif ;
- progressif ;
- professionnel ;
- accessible à un lecteur non spécialiste ;
- crédible comme rapport d’un étudiant alternant.

Utiliser la première personne lorsque l’étudiant parle de ses missions, de ses actions, de ses difficultés ou de son bilan personnel.

Éviter :

- le style trop soutenu ;
- les phrases trop génériques ;
- la survalorisation des missions ;
- les résultats inventés ;
- les formulations impersonnelles excessives ;
- les paragraphes qui pourraient appartenir à n’importe quel rapport.

## Confidentialité

Ne jamais inclure :

- mots de passe ;
- secrets ;
- données personnelles inutiles ;
- IP internes sans validation explicite ;
- noms d’utilisateurs non nécessaires ;
- journaux bruts contenant des informations sensibles ;
- captures non anonymisées.

Remplacer les informations sensibles par `[REDACTED]`.

## Méthode de rédaction

Pour chaque mission principale, utiliser la structure suivante :

1. Contexte
2. Objectifs
3. Contraintes
4. Déroulement
5. Moyens et ressources mobilisés
6. Difficultés rencontrées
7. Solutions apportées
8. Résultats obtenus
9. Recul personnel

## Git

Ne jamais travailler directement sur `main` pour une rédaction importante.
Créer une branche par tâche ou par section.
Exemples :

- `contexte-imt`
- `plan-rapport`
- `redaction-mission-intune`
- `redaction-mission-powerapps`
- `redaction-mission-securite`
- `annexe-ia`
- `relecture-finale`

Faire des commits courts et explicites.

## Contrôle qualité

Avant de considérer une section comme prête, vérifier :

- conformité aux consignes IMT ;
- cohérence avec la grille d’évaluation ;
- absence d’invention ;
- respect des missions exclues ;
- respect du style attendu ;
- présence d’une analyse personnelle ;
- clarté du propos ;
- confidentialité ;
- orthographe et syntaxe.

## Sous-agents

Les sous-agents peuvent être utilisés pour les tâches complexes ou les relectures spécialisées.

Ils doivent être utilisés selon `00_contexte_source/11_strategie_sous_agents.md`.

Règles :

* ne pas utiliser de sous-agents pour les tâches simples ;
* un seul agent modifie les fichiers ;
* les sous-agents produisent des avis et recommandations ;
* l’agent principal décide des corrections à appliquer ;
* choisir un modèle adapté à la complexité de la tâche si l’environnement le permet ;
* ne jamais utiliser de sous-agent pour contourner les règles de confidentialité ou d’absence d’invention.
