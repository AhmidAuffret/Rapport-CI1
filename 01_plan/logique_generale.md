# Logique générale du rapport

Statut : fil conducteur de travail, à valider avant rédaction finale.

## Fil conducteur proposé

Comment une première année d’alternance en administration systèmes et réseaux permet-elle de contribuer à la continuité, à la sécurité et à la modernisation du système d’information d’une entreprise industrielle ?

Ce fil conducteur doit rester le repère principal du rapport. Il permet de relier le contexte Leroux, les missions techniques et le bilan personnel sans transformer le rapport en simple catalogue d’actions.

Décision de plan associée : le rapport doit montrer une progression de première année, pas une démonstration d’expertise complète. Les missions sont donc sélectionnées parce qu’elles permettent d’expliquer une contribution concrète, des limites, des vérifications et un recul personnel.

## Pourquoi ce fil conducteur correspond au niveau CI1

Le rapport CI1 doit surtout montrer la compréhension du contexte de travail et le bilan d’une première année d’apprentissage. Le fil conducteur correspond à ce niveau car il ne présente pas l’étudiant comme responsable unique du système d’information, mais comme un alternant qui découvre progressivement l’environnement, participe à des projets concrets et apprend à prendre du recul.

Il permet aussi de montrer une progression :

- comprendre le fonctionnement d’une entreprise industrielle et de son service informatique ;
- participer à des missions utiles au quotidien du SI ;
- apprendre à tester, documenter, diagnostiquer et demander validation ;
- distinguer ce qui est réalisé, ce qui reste à confirmer et ce qui ne doit pas être affirmé sans preuve ;
- construire une posture d’apprenti ingénieur fondée sur la rigueur, la prudence et l’analyse.

## Comment les trois missions principales répondent au fil conducteur

Les trois missions principales couvrent les trois axes du fil conducteur :

| Mission principale | Continuité | Sécurité | Modernisation |
| --- | --- | --- | --- |
| Microsoft Intune / Android Enterprise | Préparation d’équipements plus homogènes et maintenables | Restrictions, mot de passe, effacement après échecs | Gestion centralisée des tablettes professionnelles |
| Registre visiteurs Power Apps / SharePoint / Power Automate | Simplification d’un processus d’accueil | Traçabilité et confidentialité des données visiteurs | Passage d’un registre papier à une solution numérique |
| Sécurité opérationnelle AD / Microsoft 365 | Diagnostic visant à limiter l’impact sur les utilisateurs | Analyse de connexions, verrouillages et journaux | Construction d’une méthode d’investigation structurée |

### Microsoft Intune / Android Enterprise

Cette mission répond surtout aux axes de modernisation et de sécurité. La gestion centralisée des tablettes professionnelles permet d’aborder la standardisation des configurations, les restrictions d’usage, la préparation des applications et la logique de tests avant généralisation.

Lien avec le fil conducteur :

- modernisation : administration plus homogène du parc mobile ;
- sécurité : restrictions, mot de passe, effacement après échecs, blocage de certaines actions ;
- continuité : préparation d’équipements plus simples à utiliser et à maintenir.

Points à sécuriser avant rédaction :

- niveau réel de validation de la configuration ;
- tests effectués ;
- résultats observables ;
- volume de tablettes et dates, uniquement si confirmés.

### Registre visiteurs Power Apps / SharePoint / Power Automate

Cette mission répond surtout aux axes de modernisation et de continuité des usages internes. Le passage d’un registre papier à une solution numérique permet d’expliquer une démarche concrète : formulaire, stockage SharePoint, automatisation, signature, diagnostic des erreurs.

Lien avec le fil conducteur :

- modernisation : numérisation d’un processus d’accueil ;
- continuité : solution simple et utilisable sur tablette ;
- sécurité et traçabilité : enregistrement centralisé et gestion de la signature, sous réserve de confidentialité.

Points à sécuriser avant rédaction :

- statut réel de mise en service ;
- niveau de suppression du registre papier ;
- utilisateurs ou service concernés ;
- absence de données visiteurs réelles dans le rapport.

### Sécurité opérationnelle AD / Microsoft 365

Cette mission répond surtout à l’axe sécurité, avec une dimension forte de méthode. Elle permet de montrer que l’étudiant apprend à analyser des journaux, recouper des informations et formuler des hypothèses prudentes avant de conclure.

Lien avec le fil conducteur :

- sécurité : analyse de connexions suspectes, verrouillages de comptes et événements AD ;
- continuité : diagnostic visant à limiter l’impact sur les utilisateurs et les comptes ;
- progression CI1 : apprentissage d’une méthode d’investigation et distinction entre symptôme, hypothèse et cause validée.

Points à sécuriser avant rédaction :

- outils exacts utilisés ;
- chronologie des analyses ;
- exemples anonymisés ;
- causes réellement validées ou à marquer `[À vérifier]`.

## Pourquoi les missions incomplètes ne sont pas mises au centre

Docker `prd-dkr01` peut être mentionné comme mission secondaire ou optionnelle, mais il ne doit pas devenir une mission principale car plusieurs éléments ne sont pas finalisés : reverse proxy, sauvegarde et déploiement applicatif final. Le sujet peut illustrer une compétence système, mais il ne doit pas déplacer le centre du rapport.

Xibo, uniFLOW et GLPI ne doivent pas être utilisés comme missions principales. Ils peuvent seulement apparaître comme contexte, lien, outil consultable ou activité ponctuelle. Cette limite évite de construire une analyse centrale sur des sujets incomplets ou non retenus par les décisions projet.

## Comment le bilan personnel fera le lien avec la progression d’apprenti ingénieur

Le bilan personnel doit montrer comment les missions ont contribué à une progression réelle, sans survalorisation. Il doit rester écrit à la première personne lorsque l’étudiant parle de ses actions, de ses difficultés et de son recul.

Axes à traiter :

- montée en compétence technique sur Intune, Power Platform, SharePoint, Power Automate, AD / Microsoft 365 et l’analyse de logs ;
- meilleure compréhension des contraintes d’un SI industriel : continuité, disponibilité, sécurité, support et confidentialité ;
- développement d’une méthode : tester, vérifier, documenter, recouper les sources, demander validation ;
- progression dans la communication avec l’équipe informatique et les utilisateurs ;
- identification des limites actuelles et des axes de progrès pour la suite de l’alternance.

## Points de vigilance pour garder une logique cohérente

- Ne pas transformer le rapport en documentation technique pure.
- Relier chaque mission au contexte Leroux et au niveau CI1.
- Faire apparaître les difficultés et solutions pour chaque mission.
- Distinguer résultats obtenus, résultats attendus et éléments encore à vérifier.
- Garder le Docker en secondaire uniquement si le plan final le confirme.
- Maintenir Xibo, uniFLOW et GLPI hors des missions principales.
- Prévoir des illustrations utiles, titrées, numérotées, commentées et anonymisées.
- Utiliser `[À compléter]`, `[À vérifier]` ou `[REDACTED]` dès qu’une information n’est pas validée.
