# Partie II — Missions réalisées

Statut : Version brouillon en cours

## 1. Microsoft Intune / Android Enterprise

### 1.1 Contexte et besoin initial

La première mission principale que je présente concerne la gestion des tablettes Android professionnelles avec Microsoft Intune et Android Enterprise. Elle s'inscrit dans le fonctionnement du service informatique, car ces équipements doivent rester adaptés aux usages de l'entreprise tout en étant suffisamment cadrés.

Chez Leroux, les tablettes répondent à deux besoins distincts. Le premier concerne une tablette destinée au registre visiteurs à l'accueil. Le second concerne des tablettes utilisées en production. Les usages ne sont pas les mêmes, mais l'objectif reste proche : disposer d'appareils configurés de manière cohérente, avec les applications utiles, les restrictions nécessaires et un niveau de sécurité adapté à un contexte professionnel.

La mission a représenté environ deux mois de travail. Cette durée comprend la prise en main de Microsoft Intune, la configuration de la tablette destinée au registre visiteurs et la configuration des tablettes de production. La période exacte n'est pas indispensable pour comprendre la mission dans ce brouillon ; elle devra être confirmée dans la version finale.

Microsoft Intune a été utilisé avec Android Enterprise en mode fully managed. Ce mode correspond à des appareils entièrement gérés par l'entreprise. La tablette n'est donc pas pensée comme un appareil personnel auquel on ajoute quelques règles, mais comme un équipement professionnel préparé pour un usage défini.

Pour moi, cette mission a aussi été une découverte. Je connaissais déjà certains principes de gestion de comptes, de postes ou d'outils Microsoft, mais la gestion d'appareils mobiles demande une logique différente. Il faut comprendre comment l'enrôlement, les profils, les groupes, les applications, les restrictions et les tests se complètent.

### 1.2 Objectifs de la mission

Le premier objectif était de standardiser la configuration des tablettes professionnelles. L'idée était d'éviter que chaque appareil soit configuré manuellement de manière différente. Une configuration commune permet au service informatique de mieux savoir ce qui est appliqué et de limiter les écarts entre tablettes.

Le deuxième objectif concernait la sécurité. Les tablettes étant utilisées dans un cadre professionnel, certaines fonctions devaient être limitées. Il ne s'agissait pas de bloquer l'utilisateur pour le principe, mais de réduire les risques liés à un appareil mobile : modifications non maîtrisées, ajout de comptes non prévus, partage d'accès ou usages qui ne correspondent pas au cadre défini.

Le troisième objectif était de simplifier l'usage pour les utilisateurs. Une tablette professionnelle doit être cadrée, mais elle doit rester utilisable. Si la configuration est trop restrictive ou mal adaptée, elle peut gêner le travail au lieu de l'aider. Il fallait donc rechercher un équilibre entre sécurité, simplicité et contraintes réelles du terrain.

Un autre objectif était de préparer une gestion plus centralisée du parc mobile. Grâce à Intune, le service informatique peut retrouver les appareils enrôlés, appliquer des configurations, déployer des applications et suivre plus facilement l'état général des tablettes. Cela ne remplace pas les vérifications humaines, mais cela donne un cadre plus fiable qu'une configuration uniquement manuelle.

Enfin, la mission devait permettre de tester les configurations avant de les considérer comme utilisables. Dans un environnement professionnel, il ne suffit pas de créer une règle dans un portail d'administration. Il faut vérifier son comportement réel sur la tablette, car certaines restrictions peuvent dépendre de la synchronisation ou du mode de gestion utilisé.

### 1.3 Moyens et outils utilisés

Les principaux outils utilisés ont été Microsoft Intune et Android Enterprise. Intune a servi à créer et appliquer les configurations. Android Enterprise a fourni le cadre de gestion des tablettes Android professionnelles, avec un mode fully managed adapté à des appareils appartenant à l'entreprise.

Les appareils concernés sont des tablettes Android professionnelles. Le modèle exact et la version Android sont connus dans le contexte de travail, mais leur citation devra être confirmée avant la version finale. Dans cette section, je parle donc des tablettes de manière générale, sans indiquer de volume précis.

L'enrôlement des tablettes s'appuyait sur un token dédié et sur un groupe associé à l'usage production. Comme ces noms correspondent à une configuration interne, je ne les détaille pas. Dans le rapport, il est suffisant de parler d'un token d'enrôlement dédié et d'un groupe de tablettes de production.

Les applications prévues ou déployées sur les tablettes comprenaient des outils bureautiques et collaboratifs comme Word, Excel, PowerPoint, OneNote, Teams et Outlook. D'autres applications utiles étaient également disponibles, comme Collabora et Adobe Reader. Ces applications correspondent à des besoins d'usage professionnel : consultation, saisie, communication ou ouverture de documents.

Des liens web utiles étaient aussi prévus sur les tablettes, notamment vers la GMAO, Fastilog et GLPI. GLPI est ici seulement cité comme lien ou outil disponible sur tablette. Il ne s'agit pas d'une mission principale du rapport, conformément aux règles du projet.

Les moyens humains mobilisés reposaient principalement sur le service informatique. Mon tuteur définissait le cadre et validait les décisions importantes. De mon côté, j'ai pris en charge la partie opérationnelle : recherches, configuration, tests, enrôlement, ajustements et échanges lorsque cela était nécessaire. Les choix techniques structurants et les décisions financières restaient validés par le tuteur ou par l'entreprise.

Les moyens financiers ne sont pas détaillés dans ce brouillon, car je ne dispose pas d'information validée sur un budget, un coût d'achat ou un arbitrage financier lié aux tablettes et aux licences. Je me limite donc aux moyens matériels, techniques, humains et documentaires réellement connus.

La documentation a aussi été une ressource importante, même si l'existence d'une procédure formelle reste à confirmer. Pour prendre en main Intune, il a fallu s'appuyer sur les informations disponibles, tester directement dans l'environnement et vérifier le résultat sur les tablettes.

### 1.4 Démarche suivie

Dans un premier temps, j'ai cherché à comprendre le besoin. Il ne s'agissait pas seulement de savoir quelles tablettes devaient être configurées, mais aussi de comprendre leur usage. La tablette d'accueil était liée au registre visiteurs, alors que les tablettes de production répondaient à un autre contexte d'utilisation. Cette distinction évitait d'appliquer une configuration unique sans tenir compte du terrain.

J'ai ensuite pris en main Microsoft Intune et Android Enterprise. Cette étape a demandé du temps, car l'outil comporte plusieurs notions qui se croisent : enrôlement de l'appareil, profils de configuration, restrictions, groupes, applications et affectations. Au début, le risque était de confondre ces éléments ou de ne pas comprendre exactement où devait être appliquée une règle.

Une fois le principe général compris, j'ai travaillé sur le mode Android Enterprise fully managed. L'enrôlement permettait de rattacher la tablette à la gestion Intune, puis de lui appliquer les paramètres associés au groupe prévu pour son usage.

La configuration a ensuite porté sur les restrictions d'usage. Plusieurs paramètres ont été appliqués ou préparés pour cadrer l'utilisation professionnelle : limitation de certaines modifications système ou réseau, restriction de certains usages non prévus et encadrement de l'ajout de comptes. Ces choix permettent de limiter les manipulations qui pourraient sortir la tablette de son usage prévu. Le détail exact de certains paramètres devra être confirmé avant la version finale.

La sécurité de l'accès à l'appareil a également été prise en compte. Une règle de mot de passe a été définie, avec un effacement prévu après plusieurs échecs selon le comportement de la stratégie appliquée. Cette règle doit être présentée avec prudence : elle renforce la protection de l'appareil, mais elle demande aussi d'être expliquée aux utilisateurs concernés pour éviter les mauvaises manipulations.

La gestion des mises à jour faisait aussi partie de la configuration. Une plage horaire hors période d'usage principal a été prévue pour limiter l'impact sur l'utilisation de la tablette pendant le travail. Ce réglage montre qu'une configuration technique doit tenir compte du moment où l'appareil est réellement utilisé.

J'ai aussi travaillé sur les applications nécessaires. L'objectif était que les tablettes disposent des outils utiles sans laisser l'utilisateur chercher ou installer lui-même les applications. Les applications bureautiques, collaboratives et de consultation de documents devaient être disponibles selon les besoins. Les liens web utiles devaient également faciliter l'accès aux outils métiers ou de support prévus.

Après la configuration, les tests ont été essentiels. Il fallait vérifier que la tablette s'enrôlait correctement, que les applications attendues apparaissaient et que les restrictions étaient bien prises en compte. Par exemple, un test non sensible consistait à contrôler qu'une tablette enrôlée affichait les applications prévues tout en restant utilisable malgré les restrictions appliquées. Les résultats précis de ces tests restent à détailler si des preuves ou validations supplémentaires sont disponibles.

Les ajustements ont fait partie de la démarche. Une configuration Intune n'est pas forcément parfaite dès le premier essai. Certains paramètres peuvent être trop stricts, mal compris ou ne pas produire immédiatement l'effet attendu. J'ai donc avancé par essais, vérifications et corrections, en gardant le tuteur comme point de validation pour les choix importants.

Cette démarche m'a montré qu'un outil d'administration centralisée ne supprime pas le besoin de méthode. Intune permet de pousser des règles, mais il faut quand même comprendre le besoin, vérifier les effets réels et garder une trace de ce qui est fait.

### 1.5 Difficultés rencontrées

La première difficulté a été la prise en main de Microsoft Intune. L'outil est complet, mais il peut être difficile à aborder au début. Plusieurs notions se ressemblent ou s'enchaînent : enrôlement, groupe, profil, restriction, application, affectation. Comprendre le rôle de chaque élément a demandé du temps.

Une autre difficulté a été de distinguer ce qui se configure dans le portail et ce qui est réellement appliqué sur la tablette. Le fait de créer une règle ne suffit pas. Il faut que l'appareil soit bien enrôlé, qu'il appartienne au bon groupe, qu'il synchronise les paramètres et que la restriction soit compatible avec le mode de gestion choisi. Cette vérification est importante, car elle évite de croire qu'une configuration est effective alors qu'elle ne l'est pas encore.

La gestion des restrictions a aussi demandé de la prudence. Certaines restrictions semblent évidentes sur le papier, mais elles peuvent avoir un impact sur l'usage réel. Par exemple, limiter des modifications système ou réseau peut être pertinent pour éviter des changements non maîtrisés, mais cela suppose que la configuration prévue soit correcte. De la même manière, encadrer certains usages non prévus renforce le cadre professionnel, mais il faut vérifier que cela ne bloque pas un besoin légitime.

La différence entre la tablette d'accueil et les tablettes de production a également nécessité de réfléchir aux usages. Une tablette destinée au registre visiteurs n'a pas forcément les mêmes besoins qu'une tablette utilisée en production. Même si la mission porte globalement sur Intune et Android Enterprise, il ne fallait pas oublier que les équipements correspondent à des situations différentes.

Le manque de données mesurées constitue une limite pour la rédaction. Je peux affirmer que les tablettes ont été configurées via Intune et que les tablettes de production sont utilisées en production, car ces éléments sont validés dans le contexte. En revanche, je ne peux pas inventer un nombre exact de tablettes, un gain de temps, une baisse d'incidents ou un indicateur chiffré. Ces éléments devront être complétés seulement s'ils sont confirmés.

Enfin, cette mission demandait de rester à ma place d'alternant. J'ai géré le processus de bout en bout sur la partie opérationnelle, mais cela ne signifie pas que j'ai décidé seul des orientations importantes. Les choix finaux, surtout lorsqu'ils engagent l'entreprise, restent validés par le tuteur ou par l'entreprise. Cette limite est normale et elle rend la présentation plus juste.

### 1.6 Résultats obtenus

Le premier résultat est la mise en place d'une configuration Intune pour les tablettes Android professionnelles concernées. Les tablettes ont été configurées avec Android Enterprise en mode fully managed, ce qui permet une gestion plus cadrée que des appareils configurés individuellement.

Les tablettes de production sont utilisées en production. Cette information peut être présentée, car elle est validée dans les fichiers de contexte. Il faut toutefois rester prudent sur le périmètre exact : le nombre de tablettes, les dates précises et l'étendue complète du déploiement restent à confirmer.

La configuration contribue à mieux cadrer l'usage professionnel des appareils. Les restrictions appliquées donnent au service informatique une meilleure maîtrise des tablettes, notamment sur les usages qui ne correspondent pas au cadre prévu. La règle de mot de passe et l'effacement prévu après plusieurs échecs ajoutent aussi une protection supplémentaire, sous réserve de confirmer le comportement exact de la stratégie appliquée.

Les applications prévues ont été configurées ou rendues disponibles selon les besoins identifiés, avec des outils comme Word, Excel, PowerPoint, OneNote, Teams, Outlook, Collabora et Adobe Reader. Les liens web utiles, notamment vers la GMAO, Fastilog et GLPI, permettent aussi de rapprocher la tablette de ses usages concrets. Là encore, GLPI reste uniquement cité comme lien ou outil disponible, pas comme sujet principal.

Un autre résultat est l'amélioration de l'homogénéité de la configuration. Grâce à Intune, les tablettes peuvent recevoir une configuration commune selon leur groupe et leur usage. Cela facilite le suivi par le service informatique et limite les écarts entre appareils. Je formule ce point comme une amélioration de maîtrise, sans que cela constitue un indicateur chiffré de performance.

La mission a aussi permis de mieux structurer la gestion du parc mobile. Le service informatique dispose d'un cadre plus centralisé pour suivre et configurer les tablettes. Cela ne veut pas dire que tout est terminé ou que plus aucun ajustement ne sera nécessaire. Les usages réels doivent continuer à être observés, surtout dans un environnement où les besoins peuvent évoluer.

Pour l'entreprise, l'apport principal est donc une configuration qui contribue à mieux homogénéiser et cadrer les tablettes professionnelles. Pour moi, le résultat est aussi une montée en compétence sur un outil d'administration moderne, utilisé dans beaucoup d'environnements professionnels.

### 1.7 Limites et points restant à suivre

Plusieurs limites doivent être indiquées clairement pour éviter de survaloriser la mission. Le nombre exact de tablettes, la période calendaire précise et l'étendue complète du déploiement devront être confirmés dans la version finale.

Les résultats mesurables ne sont pas disponibles à ce stade. Je ne peux donc pas indiquer de gain de temps, de baisse d'incidents, de taux de conformité ou de pourcentage de déploiement. Les résultats sont donc présentés de manière qualitative.

La documentation reste également à confirmer. Si une procédure interne ou une note de configuration a été produite, elle pourra être mentionnée de manière générale, sans exposer de détails sensibles. Si elle n'a pas été formalisée, il faudra indiquer que la documentation reste un axe d'amélioration.

Un autre point à suivre concerne l'usage réel des tablettes dans le temps. Une configuration peut fonctionner au moment des tests, mais il faut observer si elle reste adaptée après plusieurs jours ou semaines d'utilisation. Les retours des utilisateurs et du tuteur sont donc importants pour ajuster les restrictions ou les applications si nécessaire.

La confidentialité doit aussi rester surveillée. Les noms exacts des tokens, groupes, appareils ou paramètres internes ne sont pas indispensables à la compréhension du rapport. Dans la version finale, il faudra conserver une formulation générale ou remplacer les éléments sensibles par `[REDACTED]` si l'entreprise le demande.

Enfin, cette mission reste dépendante de validations internes. Même si j'ai réalisé une grande partie du travail opérationnel, les décisions finales sont validées par le tuteur ou par l'entreprise. Cette limite doit rester visible pour ne pas donner une image incorrecte de mon rôle.

### 1.8 Recul personnel sur la mission

Cette mission m'a permis de mieux comprendre la gestion des terminaux mobiles en entreprise. Avant de travailler sur Intune, je voyais surtout la tablette comme un appareil à configurer. Avec cette mission, j'ai compris qu'il fallait raisonner en parc, en usages, en restrictions, en applications et en suivi.

J'ai aussi appris que la sécurité ne consiste pas seulement à bloquer le plus de fonctions possible. Une restriction doit avoir un sens par rapport au besoin. Si elle protège l'appareil mais empêche l'utilisateur de travailler correctement, elle doit être revue. Cette idée m'a aidé à mieux comprendre l'équilibre entre sécurité et simplicité d'utilisation.

La prise en main d'Intune m'a demandé de la patience. Au début, il n'était pas évident de comprendre pourquoi une règle ne s'appliquait pas immédiatement ou comment les groupes, profils et applications interagissaient. En avançant étape par étape, j'ai appris à vérifier plutôt qu'à supposer. Cette méthode me sert aussi dans d'autres missions.

Cette mission m'a également montré l'importance des tests. Dans un portail d'administration, une configuration peut sembler correcte, mais seul le test sur l'appareil permet de vérifier le résultat réel. J'ai donc compris qu'il fallait toujours comparer ce qui est attendu avec ce qui se passe réellement sur la tablette.

Sur le plan professionnel, cette mission m'a donné plus d'autonomie. J'ai pu prendre en charge la recherche, la configuration, les essais et les ajustements. En même temps, j'ai gardé en tête que certaines décisions devaient être validées par le tuteur. Cette limite m'a appris à travailler de façon plus responsable : avancer seul quand c'est possible, mais demander validation quand le sujet peut avoir un impact plus large.

Enfin, cette mission fait le lien avec le fil conducteur du rapport. Elle contribue à la modernisation du système d'information par la gestion centralisée des tablettes, à la sécurité par les restrictions et les règles d'accès, et à la continuité par une configuration plus homogène des équipements utilisés. Elle reste cependant une mission de première année : elle montre surtout une progression, une méthode et une meilleure compréhension des contraintes d'un environnement professionnel.

## 2. Registre visiteurs Power Apps / SharePoint / Power Automate

### 2.1 Contexte et besoin initial

La deuxième mission principale que je présente concerne la création d'un registre visiteurs numérique avec Power Apps, SharePoint et Power Automate. Elle répond à un besoin concret de l'accueil : remplacer à terme le registre papier par une solution plus simple à utiliser et plus facile à suivre côté informatique.

Au départ, les passages des visiteurs étaient notés sur un support papier. Ce fonctionnement restait utilisable, mais il limitait la centralisation des informations et le suivi des enregistrements. La demande initiale est venue de mon tuteur de l'époque, qui était alors responsable informatique. Le besoin était de disposer d'une application sur tablette capable d'enregistrer les visiteurs, de stocker les données dans SharePoint et d'ajouter une signature réalisée directement sur l'écran.

La mission a duré environ un mois. Elle ne consistait pas seulement à créer un formulaire. Il fallait aussi organiser le stockage des informations, automatiser la création de l'enregistrement et traiter correctement la signature pour qu'elle soit conservée comme pièce jointe PNG.

Il est important de préciser dès le départ l'état réel de la solution. La partie applicative a été terminée et validée techniquement. En revanche, elle n'est pas encore utilisée à l'accueil. Sa mise en service dépend toujours de l'installation d'un support physique par le service maintenance afin de sécuriser la tablette. Je ne peux donc pas écrire que le registre papier a déjà été remplacé.

### 2.2 Objectifs de la mission

Le premier objectif était de proposer une application simple à utiliser sur tablette. L'accueil devait pouvoir saisir les informations utiles sans passer directement par une liste SharePoint ou par un outil trop technique.

Le deuxième objectif était de centraliser les informations dans SharePoint afin de conserver les passages dans un registre numérique plus facile à consulter et à suivre. Les champs retenus couvrent les informations principales : nom, prénom, société, personne visitée, heure d'arrivée, heure de départ et date de passage.

Le troisième objectif concernait la signature. Il fallait pouvoir signer sur la tablette puis conserver cette signature avec l'enregistrement du visiteur. La solution retenue a été de stocker la signature comme pièce jointe PNG sur l'élément SharePoint créé.

Enfin, je devais fiabiliser l'enregistrement avec Power Automate et rester prudent sur la confidentialité des données visiteurs. Le but n'était pas de faire quelque chose de trop technique, mais de construire une solution qui fonctionne et qui reste compréhensible.

### 2.3 Moyens et outils utilisés

Je me suis appuyé sur trois outils principaux. Power Apps m'a servi à construire l'interface sur tablette, SharePoint à stocker les informations du registre, et Power Automate à automatiser la création de l'enregistrement ainsi que l'ajout de la signature.

La tablette d'accueil fait partie des moyens matériels mobilisés. Son modèle exact reste `[À vérifier]`, mais ce point n'est pas indispensable pour comprendre la mission. L'historique d'exécution Power Automate a aussi été un moyen de travail important, car il m'a permis de vérifier les valeurs reçues et de comprendre les erreurs pendant les tests.

Les moyens humains reposaient principalement sur le service informatique. Mon tuteur de l'époque a exprimé le besoin initial et validé les choix importants. De mon côté, j'ai pris en charge la partie opérationnelle : compréhension du besoin, création de l'application, configuration de la liste SharePoint, préparation du flux, tests et corrections. Le service maintenance intervient aussi indirectement, car la mise en service dépend du support physique de la tablette.

Pour les moyens financiers, aucune donnée budgétaire exploitable n'est intégrée à ce stade dans le rapport. Je ne peux donc pas détailler de coût matériel, de coût de licence ou d'arbitrage financier sans validation.

### 2.4 Contraintes de la mission

La première contrainte était de garder une utilisation simple sur tablette, car l'outil devait rester rapide à comprendre à l'accueil. Il fallait aussi protéger la confidentialité des données visiteurs et éviter d'exposer des informations personnelles dans le rapport.

La fiabilité de l'enregistrement constituait une autre contrainte importante, en particulier pour la signature. Il ne suffisait pas que l'application fonctionne en apparence : il fallait vérifier que les données et la signature arrivaient correctement jusqu'à SharePoint.

Enfin, la mission restait dépendante d'un point matériel extérieur à la partie applicative. Même avec une solution validée techniquement, l'absence de support physique empêchait une mise en service immédiate à l'accueil.

### 2.5 Démarche suivie

Dans un premier temps, j'ai cherché à comprendre le besoin métier. Le but n'était pas seulement de remplacer un cahier par un écran. Il fallait identifier les informations nécessaires à l'accueil, réfléchir à la façon de les saisir sur tablette et prévoir le stockage dans un outil accessible au service informatique.

Le travail s'est organisé en plusieurs phases assez simples : cadrage du besoin, préparation de la liste SharePoint, création de l'application Power Apps, mise en place du flux Power Automate, puis tests et ajustements.

La première étape technique a consisté à préparer la liste SharePoint. Cette liste devait contenir les champs nécessaires au registre : nom, prénom, société, personne visitée, heure d'arrivée, heure de départ et date de passage. La date est renseignée automatiquement et les heures sont saisies via des listes déroulantes dans Power Apps, ce qui limite les erreurs de format.

J'ai ensuite travaillé sur l'application Power Apps. L'objectif était de créer un formulaire clair, avec les champs nécessaires et une zone de signature. La signature est réalisée directement sur la tablette, puis envoyée au flux Power Automate en même temps que les autres informations.

Le flux Power Automate prend ensuite le relais. Il reçoit les informations envoyées par Power Apps, crée l'élément SharePoint, puis traite la signature. Concrètement, Power Apps envoie une chaîne image encodée, puis le flux la nettoie avant conversion binaire et ajout de la pièce jointe PNG dans SharePoint.

Les tests ont pris une place importante dans la démarche. J'ai beaucoup utilisé l'historique d'exécution de Power Automate pour voir ce que le flux recevait réellement, à quel moment il bloquait et si la pièce jointe était bien créée. Sans cet historique, il aurait été beaucoup plus difficile de comprendre les erreurs.

J'ai aussi testé plusieurs cas autour de la signature. Une vraie signature devait produire un fichier PNG exploitable. Une signature vide devait être détectée pour éviter d'enregistrer une image blanche comme si elle était valide. Ces tests ont montré que le contrôle de signature pouvait renvoyer une image même lorsqu'aucune vraie signature n'était faite.

À partir de ces essais, un seuil empirique a été retenu. Une signature vide renvoyait quand même une image blanche. Un seuil autour de 7000 caractères a donc été utilisé, dans ce contexte testé, pour détecter qu'un tracé avait bien été saisi. Ce seuil n'est pas une règle universelle. C'est une solution pragmatique issue des tests réalisés sur cette application et il resterait à revérifier si l'application, le contrôle ou l'appareil changeaient.

Une fois les erreurs principales corrigées, la solution a été validée techniquement avec le tuteur. L'application permet de saisir les informations, le flux crée l'élément dans SharePoint et la signature est ajoutée en pièce jointe PNG. La partie applicative peut donc être considérée comme prête côté technique, mais la mise en service réelle reste dépendante du support physique de la tablette.

### 2.6 Difficultés rencontrées

La principale difficulté a été la gestion de la signature entre Power Apps et Power Automate. Au départ, la signature PNG obtenue n'était pas toujours exploitable. Le problème venait de la manière dont l'image était transmise, interprétée puis convertie avant d'être ajoutée dans SharePoint.

Lors de certains tests, le paramètre de signature arrivait à `null` dans Power Automate. Cela m'a obligé à vérifier pas à pas si le problème venait de Power Apps, de l'appel du flux ou de l'expression utilisée. J'ai aussi rencontré des difficultés liées à la différence entre texte et expression dans Power Automate, ainsi qu'au nettoyage de la chaîne de signature avant conversion. Tant que cette chaîne n'était pas correctement préparée, la condition de vérification pouvait échouer ou produire un fichier inutilisable.

Pour résoudre ces points, j'ai repris les tests étape par étape, contrôlé les valeurs reçues dans l'historique du flux et conservé une méthode simple pour la détection de signature vide.

Enfin, la signature vide a été une difficulté particulière. Le contrôle de signature renvoyait quand même une image blanche. Il ne suffisait donc pas de vérifier que la signature existait techniquement. Il fallait aussi distinguer une image blanche d'un tracé réellement saisi. C'est ce point qui a conduit à la mise en place du seuil empirique autour de 7000 caractères.

### 2.7 Résultats obtenus

Le premier résultat est une application Power Apps fonctionnelle pour le registre visiteurs. Elle permet de saisir les informations nécessaires et de réaliser une signature sur la tablette. L'interface reste pensée pour un usage simple, sans demander à l'utilisateur de manipuler directement SharePoint ou Power Automate.

Les données saisies sont enregistrées dans une liste SharePoint. Cette liste joue le rôle de registre numérique. Elle contient les informations principales du passage : nom, prénom, société, personne visitée, heure d'arrivée, heure de départ et date de passage.

La signature est correctement enregistrée en pièce jointe PNG sur l'élément SharePoint créé. C'était le point le plus délicat de la mission, car il fallait transformer une signature dessinée dans Power Apps en fichier exploitable dans SharePoint. Les tests ont permis d'obtenir un fichier `signature.png` valide.

Le flux Power Automate est fonctionnel. Il crée l'élément SharePoint, traite la signature et ajoute la pièce jointe. L'historique d'exécution a permis de vérifier les étapes et de corriger les erreurs rencontrées pendant les tests. Ce résultat montre que l'automatisation répond au besoin technique prévu.
 
Pour l'entreprise, la plus-value reste à présenter avec prudence. À ce stade, la solution apporte surtout une base exploitable pour centraliser les enregistrements visiteurs, réduire la dépendance au papier et préparer un suivi plus structuré, sans que ces gains aient encore été mesurés en conditions réelles.

La solution est donc prête côté applicatif. Elle a été validée techniquement, mais elle n'est pas encore utilisée à l'accueil. La mise en service dépend encore de l'installation d'un support physique pour sécuriser la tablette. Cette limite doit rester clairement indiquée.

Je ne peux pas annoncer de gain de temps mesuré, de nombre de visiteurs testés ou d'amélioration prouvée de la traçabilité. Ces éléments ne sont pas validés. Je peux seulement affirmer que la solution prépare une transition vers un registre numérique et que les fonctions attendues côté application, stockage et signature sont opérationnelles.

### 2.8 Limites et points restant à suivre

La limite principale est l'absence de mise en service réelle à l'accueil. Même si la solution est validée techniquement, elle n'est pas encore utilisée au quotidien. Le registre papier ne doit donc pas être présenté comme remplacé.

Le support physique de la tablette reste à installer par le service maintenance. Ce support doit permettre de sécuriser la tablette à l'accueil et d'éviter le vol. Tant que ce point n'est pas réglé, l'utilisation réelle ne peut pas être considérée comme finalisée.

Une autre limite concerne les tests en conditions réelles. Les tests techniques ont permis de valider l'application, le flux et la signature. En revanche, l'utilisation par l'accueil sur une période réelle pourra faire apparaître des ajustements à prévoir : ergonomie, compréhension des champs, rythme de saisie ou cas particuliers non rencontrés pendant les tests.

La confidentialité reste un point à surveiller. Un registre visiteurs contient des données personnelles. Il faut donc éviter les captures non anonymisées, les exports contenant de vrais noms ou les exemples basés sur des visiteurs réels. Si des illustrations sont ajoutées plus tard, elles devront être anonymisées ou remplacées par un schéma simplifié.

Le seuil de détection de signature doit aussi être suivi. Le seuil autour de 7000 caractères fonctionne comme solution pragmatique dans le contexte testé. Il faudra cependant rester prudent si le comportement du contrôle Power Apps évolue, si l'application est modifiée ou si un autre appareil produit des images de taille différente.

Le statut du registre papier devra également être confirmé lors de la version finale. À ce stade, je ne peux pas écrire qu'il est supprimé. Il faut rester sur une formulation prudente : la solution vise à remplacer ou réduire l'usage du registre papier, sous réserve de la mise en service réelle de la tablette.

Enfin, les moyens financiers et la période exacte restent à compléter si ces informations sont nécessaires dans la version finale. Je connais la durée approximative de la mission, environ un mois, mais pas forcément la période calendaire exacte à citer. De la même manière, je ne dispose pas d'un budget validé à intégrer dans le rapport.

### 2.9 Recul personnel sur la mission

Cette mission m'a permis de découvrir plus concrètement Power Apps et Power Automate. Avant de travailler sur ce registre visiteurs, je voyais surtout ces outils comme des moyens de créer rapidement des applications internes. Avec la mission, j'ai compris qu'il fallait aussi gérer les limites techniques, les formats de données et les erreurs entre les outils.

J'ai appris que le plus difficile n'était pas forcément de créer les champs du formulaire. La partie la plus délicate a été la signature, car une action simple pour l'utilisateur demandait en réalité plusieurs traitements techniques avant d'arriver correctement dans SharePoint.

L'historique d'exécution Power Automate m'a aussi beaucoup aidé. Il m'a appris à diagnostiquer une automatisation étape par étape. Au lieu de chercher au hasard, je pouvais vérifier ce que le flux recevait, ce qu'il transformait et à quel moment l'erreur apparaissait. Cette démarche m'a appris à avancer par vérifications successives plutôt que par essais désordonnés.

La gestion de la signature vide m'a également marqué. Au départ, on pourrait penser qu'une signature vide ne renvoie rien. En réalité, le contrôle pouvait produire une image blanche. Il fallait donc vérifier le comportement réel de l'outil et adapter la solution. Le seuil empirique autour de 7000 caractères n'est pas parfait, mais il répond au problème observé de manière simple et contrôlable.

Cette mission m'a aussi rappelé qu'une solution technique validée n'est pas forcément une solution déployée. L'application fonctionne, mais elle n'est pas encore utilisée à l'accueil tant que la tablette n'est pas sécurisée physiquement. Cela m'a permis de mieux comprendre la différence entre validation applicative, validation technique et mise en service réelle.

Sur le plan professionnel, j'ai travaillé avec une autonomie importante sur la partie opérationnelle. J'ai pu créer, tester, corriger et ajuster la solution, tout en gardant le tuteur comme point de validation. Cette manière de travailler m'a aidé à progresser, car elle m'a obligé à chercher par moi-même tout en sachant quand demander une validation.

Enfin, cette mission correspond bien au niveau CI1. Elle n'est pas une transformation complète de l'accueil ni un déploiement finalisé. C'est une contribution concrète à un besoin interne, avec une solution fonctionnelle, des limites identifiées et une mise en service encore dépendante d'un élément matériel. Cette mission m'a surtout appris à partir d'un besoin concret, à construire une solution, puis à vérifier qu'elle fonctionne vraiment.

## 3. Sécurité opérationnelle AD / Microsoft 365

### 3.1 Contexte et besoin initial

La troisième mission principale présentée dans ce rapport concerne la sécurité opérationnelle autour d'Active Directory et de Microsoft 365. Contrairement aux deux premières missions, il ne s'agit pas d'un sujet avec un début, une phase de réalisation clairement isolée, puis une fin. Cette mission correspond plutôt à une activité continue du service informatique. Elle revient au fil des incidents, des demandes utilisateurs et des vérifications quotidiennes liées aux comptes, aux connexions et aux postes de travail.

Dans le fonctionnement courant du service, certains problèmes peuvent paraître simples au premier abord. Un utilisateur signale par exemple qu'il ne peut plus se connecter, qu'un mot de passe semble ne plus fonctionner, que son compte se verrouille sans raison apparente ou qu'une connexion lui paraît inhabituelle. Pourtant, ce type de symptôme peut avoir plusieurs causes. Il peut s'agir d'une mauvaise saisie, d'un ancien mot de passe encore enregistré sur un poste ou un équipement, d'un problème de synchronisation, d'une authentification réseau liée au Wi-Fi, ou d'un comportement qui demande au contraire une vérification plus prudente.

Dans ce contexte, mon rôle n'était pas de mener un audit complet de sécurité ni de prendre seul des décisions structurantes. J'ai surtout participé à une mission continue de diagnostic. Elle m'a amené à analyser des incidents liés aux verrouillages de comptes, aux échecs d'authentification, aux connexions suspectes, aux vérifications Microsoft 365 et aux journaux Windows. Cette mission s'inscrit directement dans le fil conducteur du rapport, car elle touche à la fois à la continuité de service, à la sécurité et à la méthode de travail.

Elle répond aussi à un besoin très concret pour l'entreprise. Lorsqu'un compte reste bloqué ou qu'une authentification échoue, le problème n'est pas seulement technique. Il peut empêcher un utilisateur de travailler normalement, perturber un accès à un service ou faire perdre du temps au support. Il faut donc intervenir assez rapidement, mais sans conclure trop vite. C'est ce mélange de réactivité et de prudence qui revient le plus dans cette mission.

### 3.2 Objectifs de la mission

Le premier objectif était de comprendre l'origine probable d'un incident avant de proposer une correction. Dans cette mission, un symptôme ne suffit pas. Le fait qu'un compte soit verrouillé ne dit pas, à lui seul, pourquoi il l'est. Il fallait donc chercher des éléments de contexte, vérifier les journaux utiles et comparer plusieurs sources d'information.

Le deuxième objectif était de contribuer à limiter l'impact des incidents sur les utilisateurs. Lorsqu'un problème d'authentification revient plusieurs fois, il ne suffit pas de débloquer le compte ou de réinitialiser un mot de passe. Il faut aussi essayer de comprendre si le problème vient du poste, d'un mot de passe enregistré, d'un équipement, d'un accès Wi-Fi ou d'un autre comportement technique encore actif.

Le troisième objectif concernait la méthode. Cette mission m'a appris à avancer par hypothèses et recoupement d'informations. Je devais distinguer ce qui relevait du symptôme observé, de la piste probable, puis éventuellement de la cause confirmée. Cette distinction est importante dans un rapport comme dans le travail quotidien, car elle évite d'écrire ou de dire qu'un problème est résolu définitivement alors que les vérifications restent incomplètes.

Enfin, un autre objectif était de mieux comprendre les liens entre Active Directory, Microsoft 365, les postes utilisateurs et les journaux de sécurité. Même lorsqu'un incident commence par une plainte très simple, comme "je n'arrive plus à me connecter", il peut demander de regarder plusieurs couches du système d'information avant de formuler une explication crédible.

### 3.3 Moyens et outils utilisés

Le premier outil utilisé dans cette mission était Active Directory, en particulier pour vérifier l'état d'un compte, observer les verrouillages et contrôler certains éléments liés à l'authentification. La console Utilisateurs et ordinateurs Active Directory servait de point d'entrée pour confirmer qu'un compte était bien concerné par le problème signalé.

Selon les cas, les vérifications pouvaient aussi concerner Microsoft 365 et, lorsque l'incident touchait plus directement à l'identité ou aux connexions, Microsoft Entra. L'objectif n'était pas de faire une analyse exhaustive de l'environnement cloud, mais de vérifier si un comportement observé côté utilisateur pouvait aussi apparaître dans les contrôles liés à ces outils.

Les journaux d'événements Windows ont joué un rôle central. Je ne les cite pas comme une liste technique à apprendre, mais comme des sources d'information qui permettent d'orienter le diagnostic. Certains événements de sécurité permettaient par exemple de confirmer un verrouillage de compte ou un échec d'authentification. Dans certains cas, un code d'état pouvait aussi indiquer qu'un compte était déjà verrouillé plutôt qu'en simple échec de saisie. Ces éléments orientaient l'analyse, mais ils ne suffisaient pas à eux seuls à confirmer l'origine exacte du problème sans recoupement avec le poste utilisateur, le contexte et les autres journaux.

Lorsque le problème semblait lié à une authentification réseau, notamment sur le Wi-Fi, les journaux associés à cette authentification pouvaient aussi compléter l'analyse. Là encore, le but n'était pas de transformer la mission en documentation réseau, mais de vérifier si le refus venait réellement de ce niveau ou s'il fallait continuer les vérifications ailleurs.

Le poste utilisateur concerné constituait également un moyen d'analyse important. Une partie du travail consistait à vérifier le contexte réel d'utilisation : session ouverte ou non, présence éventuelle d'informations d'identification enregistrées, comportement d'un logiciel, ou répétition automatique d'une tentative de connexion avec un ancien mot de passe.

À cela s'ajoutaient les échanges avec l'utilisateur et la validation avec le tuteur. Les informations données par l'utilisateur permettaient souvent de mieux situer le moment du problème, le périphérique utilisé ou le changement récent qui pouvait expliquer l'incident. Le tuteur, de son côté, gardait la validation des actions importantes, notamment lorsqu'une correction dépassait la simple vérification locale.

Les moyens humains et documentaires restaient donc essentiels dans cette mission. Il ne s'agissait pas seulement de lire des journaux. Il fallait aussi relier ce qui était visible dans les outils avec ce qui se passait réellement pour l'utilisateur. À mon niveau, cette mission mobilisait surtout des ressources techniques, humaines et documentaires ; aucun moyen financier spécifique n'a été identifié.

### 3.4 Contraintes de la mission

La première contrainte était la confidentialité. Cette mission porte sur des comptes, des authentifications, des journaux et parfois des comportements inhabituels. Je ne peux donc pas intégrer dans le rapport de noms de comptes, de noms de postes, d'adresses IP internes, de noms de serveurs ou de journaux bruts. Le texte doit rester anonymisé et centré sur la méthode.

La deuxième contrainte venait de la complexité d'interprétation. Un même symptôme peut avoir plusieurs causes possibles, et plusieurs journaux peuvent montrer des éléments différents sans donner immédiatement une réponse unique. Il fallait donc rester prudent, car un verrouillage de compte ou un échec de connexion ne suffit pas à désigner un responsable, ni à confirmer une cause sans recoupement.

Une autre difficulté est liée au caractère parfois intermittent des incidents. Certains problèmes ne se reproduisent pas au moment où l'on commence l'analyse. Dans ce cas, il faut s'appuyer sur les traces disponibles, sur le contexte donné par l'utilisateur et sur des vérifications indirectes. Cela demande plus de prudence qu'un incident facilement reproductible.

La réactivité constituait aussi une contrainte importante. Lorsqu'un utilisateur ne peut plus se connecter, il faut essayer d'avancer rapidement. Mais cette rapidité ne doit pas conduire à faire une modification trop hâtive. Une action mal comprise peut masquer la cause réelle ou déplacer le problème sans le résoudre.

Enfin, mon rôle d'alternant imposait une limite claire. Je pouvais participer à l'analyse, proposer des pistes et appliquer certaines vérifications, mais les actions importantes restaient validées par le tuteur ou par l'entreprise. Cette contrainte n'était pas un frein. Au contraire, elle m'a appris à structurer mes constats avant de proposer une conclusion.

### 3.5 Démarche suivie

La démarche suivie dans cette mission était assez stable, même si chaque incident gardait ses particularités. Je commençais d'abord par comprendre le symptôme signalé. Il fallait préciser si le problème concernait un verrouillage de compte, un refus de mot de passe, une connexion inhabituelle, un accès Wi-Fi ou un comportement observé dans Microsoft 365.

Ensuite, je récupérais le contexte utile auprès de l'utilisateur ou à partir des informations déjà disponibles. L'heure approximative du problème, le poste utilisé, le changement récent de mot de passe, la présence d'un autre appareil ou d'une connexion automatique pouvaient déjà orienter le diagnostic. Cette étape était importante, car elle évitait de chercher dans les journaux sans point de départ.

Après cela, je vérifiais les informations les plus immédiates. Côté Active Directory, cela pouvait consister à confirmer qu'un compte était verrouillé ou non. Côté poste utilisateur, il fallait parfois observer si une session restait ouverte, si un logiciel continuait à tenter une connexion, ou si des informations d'identification anciennes semblaient encore utilisées.

La lecture des journaux venait ensuite appuyer ou contredire les premières hypothèses. Dans un cas de verrouillage de compte, certains événements de sécurité permettaient par exemple de confirmer qu'un verrouillage avait bien eu lieu ou qu'une tentative d'authentification échouait encore en arrière-plan. Si l'analyse concernait le Wi-Fi ou l'authentification réseau, il fallait compléter avec les journaux adaptés pour éviter d'attribuer trop vite le problème au seul compte utilisateur.

À partir de là, la méthode consistait surtout à recouper. Un cas typique pouvait être celui d'un compte qui se verrouille à nouveau peu après avoir été débloqué. Dans une situation comme celle-ci, plusieurs explications restent possibles : un ancien mot de passe enregistré sur un poste, un appareil mobile qui essaye encore de se connecter, une authentification réseau répétée, ou un logiciel qui conserve une ancienne information. Le travail ne consistait donc pas à choisir la première cause plausible, mais à vérifier les hypothèses une par une. Dans ce genre de cas, il pouvait par exemple falloir contrôler le poste, supprimer une information d'identification enregistrée, puis vérifier si le verrouillage réapparaissait ou non.

Lorsque les vérifications faisaient ressortir une cause probable, une correction pouvait être proposée ou appliquée sous validation. Cela pouvait passer par la suppression d'un mot de passe enregistré, un contrôle du poste, une vérification complémentaire côté Microsoft 365 ou Microsoft Entra, ou une action simple sur le compte lorsque cela était justifié. Même dans ce cas, le suivi restait important, car une correction n'est réellement crédible que si le problème ne réapparaît pas immédiatement.

Enfin, lorsque c'était utile, une trace était conservée dans le cadre du suivi interne. Là encore, l'idée n'était pas de constituer un journal complet dans le rapport, mais de garder une méthode de travail exploitable pour le service informatique.

### 3.6 Difficultés rencontrées

La première difficulté a été le volume d'information à trier. Les journaux Windows donnent beaucoup d'éléments, mais tous ne sont pas utiles au même moment. Au début, il peut être tentant de tout lire, alors qu'il faut surtout apprendre à repérer les événements qui orientent réellement le diagnostic.

La deuxième difficulté venait de la corrélation entre plusieurs sources. Un incident pouvait demander de regarder à la fois le contrôleur de domaine, le poste utilisateur, un contexte Microsoft 365 et, dans certains cas, l'authentification réseau. Le plus compliqué n'était donc pas seulement de trouver une ligne dans un journal, mais de comprendre le lien entre plusieurs observations.

J'ai aussi rencontré une difficulté d'interprétation. Un même symptôme peut donner l'impression d'une cause évidente, alors qu'il reste ambigu. Par exemple, un verrouillage de compte peut faire penser à une simple erreur de mot de passe, mais les vérifications peuvent ensuite montrer qu'un ancien identifiant est encore utilisé automatiquement ailleurs. À l'inverse, une connexion inhabituelle ne doit pas être présentée trop vite comme un comportement malveillant tant que les éléments restent incomplets.

Les échanges avec l'utilisateur pouvaient aussi être délicats, non pas sur le plan relationnel, mais parce que les informations remontées sont souvent partielles. Un utilisateur décrit ce qu'il voit, pas forcément ce qui a déclenché le problème. Il fallait donc reformuler, poser les bonnes questions et éviter de supposer trop vite qu'un détail était sans importance.

Enfin, la mission demandait de garder une posture prudente. Dans un sujet de sécurité opérationnelle, il faut résister à l'envie de conclure trop vite. Cette difficulté est réelle, surtout lorsqu'on veut aider rapidement. Pourtant, c'est précisément ce point qui m'a fait progresser : comprendre qu'une hypothèse bien formulée vaut mieux qu'une conclusion rapide mais fragile.

### 3.7 Résultats obtenus

Le premier résultat de cette mission est une participation réelle au traitement d'incidents quotidiens liés aux comptes, aux authentifications et aux connexions. Je ne peux pas donner de volume chiffré, mais je peux affirmer que cette activité faisait partie du fonctionnement régulier du service informatique et qu'elle m'a placé dans des situations concrètes de diagnostic.

La mission m'a aussi permis de mieux comprendre les verrouillages de comptes et les échecs d'authentification. Avant cette expérience, j'aurais eu tendance à voir ces incidents comme des problèmes isolés. Avec la pratique, j'ai compris qu'ils demandaient souvent une analyse plus large, en tenant compte du poste, du contexte d'utilisation, des accès réseau et des outils Microsoft associés.

Un autre résultat important est la capacité à utiliser plusieurs sources d'information de façon plus structurée. Je me suis davantage habitué à croiser les journaux, le contexte utilisateur et les vérifications techniques, au lieu de m'appuyer sur une seule information. Cette progression ne signifie pas que chaque incident aboutit à une certitude complète, mais elle améliore nettement la qualité du diagnostic.

Dans certains cas, cette démarche permettait d'identifier une cause probable suffisamment solide pour proposer une correction adaptée. Je reste volontairement prudent sur ce point. Je ne peux pas écrire que toutes les causes étaient confirmées de manière unique ni que tous les incidents ont été résolus définitivement. En revanche, je peux affirmer que cette mission m'a permis de contribuer à des analyses plus rigoureuses et plus utiles pour le support quotidien.

Pour le service informatique, l'apport principal tient donc surtout à la méthode. Une meilleure lecture des symptômes, un meilleur recoupement des informations et une correction plus ciblée peuvent améliorer la fiabilité du traitement des incidents courants.

### 3.8 Limites et points restant à suivre

La première limite est qu'un incident de sécurité opérationnelle n'offre pas toujours une preuve unique. Il arrive que plusieurs hypothèses restent crédibles, même après plusieurs vérifications. Dans ce cas, il faut accepter de rester sur une cause probable plutôt que d'affirmer une certitude non démontrée.

Les journaux peuvent aussi être incomplets ou difficiles à interpréter selon le moment où l'on intervient. Si un incident a déjà cessé, certaines traces peuvent être moins lisibles ou demander davantage de recoupement. Cela limite naturellement le niveau de détail que je peux présenter dans le rapport.

Une autre limite concerne la confidentialité. Comme cette mission touche à des éléments sensibles, je dois volontairement rester général sur les exemples. Le rapport ne contient donc ni cas complet détaillé, ni log brut, ni élément nominatif. Cette retenue est nécessaire, mais elle empêche aussi de montrer tout le niveau de détail réel du diagnostic.

Je ne dispose pas non plus d'indicateurs chiffrés validés sur cette activité. Je ne peux donc pas annoncer un nombre d'incidents traités, un temps moyen de résolution, ni une baisse mesurée des problèmes d'authentification. Les résultats doivent rester qualitatifs.

Enfin, plusieurs points devront encore être vérifiés pour une version finale plus précise du rapport : la formulation exacte de certains outils Microsoft associés aux identités et aux accès, la période la plus pertinente à citer pour cette mission continue, et le niveau de détail autorisé sur certains exemples anonymisés.

### 3.9 Recul personnel sur la mission

Cette mission m'a beaucoup appris sur la manière d'aborder un problème de sécurité opérationnelle. Au départ, j'aurais pu voir un verrouillage de compte ou un échec de connexion comme un incident assez simple. En pratique, j'ai découvert qu'il fallait presque toujours prendre un peu de recul, replacer le symptôme dans son contexte et accepter que la première explication ne soit pas forcément la bonne.

J'ai surtout progressé sur la méthode. Cette mission m'a appris à ne pas m'arrêter au premier indice, à comparer plusieurs sources et à distinguer clairement trois niveaux : ce que j'observe, ce que j'en déduis comme hypothèse, puis ce que je peux réellement considérer comme confirmé. Cette distinction me paraît aujourd'hui essentielle, non seulement pour la sécurité, mais pour le diagnostic informatique en général.

Elle m'a aussi montré que la sécurité opérationnelle n'est pas séparée du support utilisateur. Derrière un compte verrouillé ou une authentification refusée, il y a avant tout une personne qui ne peut plus travailler normalement. Il faut donc garder une approche technique rigoureuse, tout en restant capable d'expliquer simplement ce que l'on vérifie et pourquoi.

Cette mission m'a également appris à être plus prudent dans ma manière de conclure. En sécurité, un symptôme impressionnant n'est pas forcément grave, et un problème apparemment banal peut demander une vraie analyse. J'ai donc compris l'importance de ne pas dramatiser, mais aussi de ne pas banaliser trop vite.

Enfin, cette activité continue correspond bien à mon niveau de première année. Elle ne me présente pas comme responsable de la sécurité globale de l'entreprise. En revanche, elle montre que j'ai commencé à travailler avec une méthode d'investigation plus rigoureuse, utile au quotidien du service informatique et cohérente avec la posture attendue d'un alternant administrateur systèmes et réseaux.
