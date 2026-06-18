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

La deuxième mission principale que je présente concerne la création d'un registre visiteurs numérique avec Power Apps, SharePoint et Power Automate. Cette mission s'inscrit dans la continuité des besoins du service informatique : moderniser progressivement certains usages internes, tout en gardant une solution simple pour les utilisateurs.

À l'accueil, l'entreprise utilisait un registre papier pour noter les passages des visiteurs. Ce fonctionnement peut être suffisant dans beaucoup de situations, mais il présente aussi des limites. Les informations restent sur un support physique, la consultation n'est pas centralisée et la conservation dépend du registre lui-même. L'objectif de la mission était donc de préparer une transition vers une solution numérique, utilisable sur une tablette à l'accueil.

La demande initiale est venue de Loïc Humman, qui était alors responsable informatique et mon tuteur. Le besoin était de créer une application permettant d'enregistrer les visiteurs, de conserver les informations dans SharePoint et d'ajouter une signature réalisée sur tablette. La mission a duré environ un mois. Elle ne correspond pas à un simple formulaire : il fallait aussi gérer le stockage des données, l'automatisation de la création de l'enregistrement et la signature sous forme de pièce jointe.

Il est important de préciser l'état réel de la solution. La partie applicative a été terminée et validée techniquement. Les données peuvent être enregistrées dans SharePoint et la signature est bien ajoutée en pièce jointe PNG. En revanche, la solution n'est pas encore utilisée à l'accueil. Sa mise en service dépend encore de l'installation d'un support physique par le service maintenance, afin de sécuriser la tablette et d'éviter le vol. Je ne peux donc pas écrire que le registre papier a été remplacé ou que le déploiement est terminé.

Cette mission répond au fil conducteur du rapport par son lien avec la modernisation et la continuité des usages. Elle vise à remplacer ou réduire l'usage du papier, tout en gardant un fonctionnement compréhensible pour l'accueil. Elle demande aussi une attention particulière à la confidentialité, car un registre visiteurs contient des données personnelles.

### 2.2 Objectifs de la mission

Le premier objectif était de créer une application simple à utiliser sur tablette. L'accueil devait pouvoir saisir les informations nécessaires sans avoir à manipuler directement une liste SharePoint ou un outil technique. L'application devait donc présenter les champs utiles de manière claire et limiter les actions inutiles.

Le deuxième objectif était de centraliser les informations dans SharePoint. La liste SharePoint joue le rôle de registre de données. Elle permet de conserver les passages avec les champs principaux : nom, prénom, société, personne visitée, heure d'arrivée, heure de départ et date de passage. La date est renseignée automatiquement, ce qui limite la saisie manuelle de cette information.

Le troisième objectif concernait la signature. Dans un registre visiteurs, la signature fait partie des éléments attendus. La difficulté était de récupérer une signature faite sur l'écran de la tablette, puis de l'enregistrer correctement dans SharePoint. La solution retenue consiste à stocker la signature comme pièce jointe PNG sur l'élément SharePoint créé.

Un autre objectif était de fiabiliser l'enregistrement. Au lieu de laisser Power Apps écrire directement toutes les données sans traitement complémentaire, un flux Power Automate a été utilisé. Ce flux reçoit les informations transmises par l'application, crée l'élément SharePoint, traite la signature et l'ajoute en pièce jointe. Cette séparation permet de mieux gérer les étapes techniques, surtout pour la signature.

La mission devait aussi respecter la confidentialité des données visiteurs. Le rapport ne doit pas contenir de vrais noms de visiteurs, de sociétés visitées ou de signatures. Les champs peuvent être décrits de manière générale, mais aucune donnée réelle ne doit être exposée. Cette règle est importante, car la numérisation d'un registre ne doit pas conduire à diffuser plus largement des informations personnelles.

Enfin, l'objectif n'était pas de produire une documentation technique complète sur Power Apps ou Power Automate. Le but était de construire une solution fonctionnelle pour un besoin terrain, puis d'expliquer la démarche, les difficultés et les limites dans un rapport de première année CI1.

### 2.3 Moyens et outils utilisés

La solution repose sur trois outils principaux de l'environnement Microsoft : Power Apps, SharePoint et Power Automate. Chaque outil a un rôle distinct dans la mission.

Power Apps a servi à créer l'interface de saisie. C'est l'application que l'utilisateur voit sur la tablette. Elle contient les champs nécessaires au registre visiteurs et un contrôle de signature. L'intérêt de Power Apps est de pouvoir créer une application interne sans développer une application classique complète. Pour cette mission, cela permettait de partir d'un besoin concret et de construire rapidement une interface adaptée.

SharePoint a servi de base de stockage. Une liste SharePoint dédiée au registre visiteurs contient les informations saisies. Les colonnes principales sont le nom, le prénom, la société, la personne visitée, l'heure d'arrivée, l'heure de départ et la date de passage. Les pièces jointes sont activées afin de stocker la signature au format PNG. Cette organisation évite de mélanger la signature avec les champs texte du registre.

Power Automate a été utilisé pour automatiser la création de l'enregistrement. Le flux est déclenché depuis Power Apps. Il reçoit les valeurs saisies, crée l'élément dans la liste SharePoint, nettoie la donnée de signature, vérifie qu'elle correspond bien à une image, puis ajoute la signature en pièce jointe. Le nom exact du flux existe dans le contexte de travail, mais il n'est pas indispensable de l'exposer dans le rapport si cela n'apporte rien à la compréhension.

La tablette d'accueil fait aussi partie des moyens matériels. Elle est destinée à être utilisée à l'entrée de l'entreprise pour saisir les passages. Le modèle exact de la tablette reste à vérifier avant la version finale. Dans cette section, je parle donc d'une tablette destinée à l'accueil, sans détailler de caractéristique inutile.

Les moyens humains mobilisés reposaient principalement sur le service informatique. Loïc Humman a exprimé le besoin initial et a validé les choix importants. De mon côté, j'ai participé à la conception et à la mise en oeuvre opérationnelle : compréhension du besoin, création de l'application, configuration de la liste SharePoint, création du flux, tests, débogage et ajustements. Les décisions finales restent toutefois validées par le tuteur ou par l'entreprise.

Le service maintenance intervient aussi dans la suite de la mission, mais sur un point différent : l'installation du support physique de la tablette. Tant que ce support n'est pas installé, la solution applicative ne peut pas être présentée comme réellement en service à l'accueil.

Les moyens financiers ne sont pas détaillés, car je ne dispose pas d'information validée sur un budget ou un coût associé à cette mission. Je ne peux donc pas inventer de coût matériel, de coût de licence ou d'arbitrage financier. Budget associé : `[À vérifier]`. Je me limite aux ressources techniques, matérielles et humaines connues.

### 2.4 Démarche suivie

Dans un premier temps, j'ai cherché à comprendre le besoin métier. Le but n'était pas seulement de remplacer un cahier par un écran. Il fallait identifier les informations nécessaires à l'accueil, réfléchir à la façon de les saisir sur tablette et prévoir le stockage dans un outil accessible au service informatique.

La première étape technique a consisté à préparer la liste SharePoint. Cette liste devait contenir les champs nécessaires au registre. Les informations principales sont des champs simples : nom, prénom, société et personne visitée. La date de passage est automatique et le champ est prévu en date uniquement. Les heures d'arrivée et de départ sont stockées au format texte `HH:MM`, car elles sont saisies via des listes déroulantes dans Power Apps.

Le choix des listes déroulantes pour les heures répondait à un besoin de simplicité. Au lieu de laisser une saisie libre, l'utilisateur choisit une heure et des minutes. Les minutes sont proposées par pas de cinq. Cela limite les erreurs de format et rend l'interface plus adaptée à une tablette. Ce choix reste simple, mais il montre qu'une application doit être pensée pour son usage réel.

J'ai ensuite travaillé sur l'application Power Apps. L'objectif était de créer un formulaire clair, avec les champs nécessaires et une zone de signature. La signature est réalisée avec un contrôle de type Pen Input. Ce contrôle permet à l'utilisateur de signer directement sur l'écran de la tablette.

La difficulté principale est apparue au moment de récupérer cette signature. Une signature dans Power Apps n'est pas seulement un texte ou une valeur simple. Il faut convertir l'image en données exploitables pour pouvoir l'envoyer au flux Power Automate. La solution utilisée consiste à convertir l'image de signature en JSON avec inclusion des données binaires côté Power Apps, puis à transmettre cette donnée au flux.

Le flux Power Automate prend ensuite le relais. Il reçoit les informations envoyées par Power Apps, crée l'élément SharePoint, puis traite la signature. La signature est transmise sous forme de Data URI, c'est-à-dire une chaîne contenant le type de donnée et le contenu encodé de l'image. Le flux doit nettoyer cette chaîne, vérifier qu'elle commence bien par `data:image/`, puis convertir le contenu en binaire pour créer la pièce jointe PNG.

Les tests ont pris une place importante dans la démarche. J'ai utilisé l'historique d'exécution Power Automate pour vérifier les valeurs reçues par le flux. Cela permettait de voir si les champs étaient transmis correctement, si la signature arrivait bien, si la condition de vérification passait et si la pièce jointe était créée. Sans cet historique, il aurait été beaucoup plus difficile de comprendre les erreurs.

J'ai aussi testé plusieurs cas autour de la signature. Une vraie signature devait produire un fichier PNG exploitable. Une signature vide devait être détectée pour éviter d'enregistrer une image blanche comme si elle était valide. Ces tests ont montré que le contrôle de signature pouvait renvoyer une image même lorsqu'aucune vraie signature n'était faite.

À partir de ces essais, un seuil empirique a été retenu. Une signature vide retournait une image blanche d'environ 5165 caractères. Un seuil autour de 7000 caractères a donc été utilisé : en dessous, la signature est considérée comme absente ; au-dessus ou à partir de ce seuil, elle est considérée comme valide. Ce seuil n'est pas une règle universelle. C'est une solution pragmatique issue des tests réalisés sur cette application.

Une fois les erreurs principales corrigées, la solution a été validée techniquement avec le tuteur. L'application permet de saisir les informations, le flux crée l'élément dans SharePoint et la signature est ajoutée en pièce jointe PNG. La partie applicative peut donc être considérée comme prête côté technique, mais la mise en service réelle reste dépendante du support physique de la tablette.

### 2.5 Difficultés rencontrées

La première difficulté a été la gestion de la signature. Au départ, la signature PNG obtenue n'était pas toujours exploitable. Le fichier pouvait être cassé ou ne pas correspondre à une vraie image utilisable. Cette difficulté venait surtout de la manière dont la donnée était transmise entre Power Apps et Power Automate.

La conversion entre base64, Data URI et fichier binaire a été un point technique important. Une image de signature doit être transformée en chaîne de caractères, transmise au flux, puis reconvertie en fichier. Si une partie de cette chaîne est mal nettoyée ou mal interprétée, le fichier final peut être inutilisable.

Une autre difficulté concernait l'utilisation de `JSONFormat.IncludeBinaryData`. Cette option devait être utilisée au bon endroit dans Power Apps. Elle n'a pas le même comportement selon le contexte d'utilisation. Il fallait donc l'utiliser dans une expression comportementale adaptée, afin que la signature soit bien envoyée avec les données binaires.

Lors de certains tests, le paramètre de signature arrivait à `null` dans Power Automate. Cela compliquait le diagnostic, car le flux ne pouvait pas traiter une signature absente. Il fallait alors vérifier si le problème venait de Power Apps, de l'appel du flux, du paramètre attendu ou de la manière dont l'expression était écrite.

Power Automate a aussi présenté une difficulté liée à la différence entre texte et expression. Dans certains champs, une valeur peut être interprétée comme une chaîne de caractères simple alors qu'on attend une expression. Cette confusion peut produire des conditions fausses ou des traitements qui ne s'exécutent pas comme prévu.

La condition vérifiant la signature pouvait également échouer si la chaîne n'était pas nettoyée correctement ou si elle était nulle. Une condition qui semble correcte peut donc être fausse simplement parce que la donnée reçue n'a pas exactement le format attendu. Cela m'a obligé à contrôler le contenu réel reçu par le flux au lieu de supposer que la signature était transmise correctement.

Enfin, la signature vide a été une difficulté particulière. Le contrôle de signature renvoyait quand même une image blanche. Il ne suffisait donc pas de vérifier que la signature existait techniquement. Il fallait aussi distinguer une image blanche d'une vraie signature. C'est ce point qui a conduit à la mise en place du seuil empirique autour de 7000 caractères.

### 2.6 Résultats obtenus

Le premier résultat est une application Power Apps fonctionnelle pour le registre visiteurs. Elle permet de saisir les informations nécessaires et de réaliser une signature sur la tablette. L'interface reste pensée pour un usage simple, sans demander à l'utilisateur de manipuler directement SharePoint ou Power Automate.

Les données saisies sont enregistrées dans une liste SharePoint. Cette liste joue le rôle de registre numérique. Elle contient les informations principales du passage : nom, prénom, société, personne visitée, heure d'arrivée, heure de départ et date de passage. La date est automatique, ce qui limite la saisie manuelle de cette information.

Les heures sont saisies via des listes déroulantes. Ce choix permet d'obtenir un format plus homogène que si l'utilisateur écrivait librement l'heure. Les heures sont ensuite conservées au format texte `HH:MM`. Ce fonctionnement correspond au besoin connu de la mission.

La signature est correctement enregistrée en pièce jointe PNG sur l'élément SharePoint créé. C'était le point le plus délicat de la mission, car il fallait transformer une signature dessinée dans Power Apps en fichier exploitable dans SharePoint. Les tests ont permis d'obtenir un fichier `signature.png` valide.

Le flux Power Automate est fonctionnel. Il crée l'élément SharePoint, traite la signature et ajoute la pièce jointe. L'historique d'exécution a permis de vérifier les étapes et de corriger les erreurs rencontrées pendant les tests. Ce résultat montre que l'automatisation répond au besoin technique prévu.

La solution est donc prête côté applicatif. Elle a été validée techniquement, mais elle n'est pas encore utilisée à l'accueil. La mise en service dépend encore de l'installation d'un support physique pour sécuriser la tablette. Cette limite doit rester clairement indiquée, car elle change la manière de présenter le résultat.

Je ne peux pas annoncer de gain de temps mesuré, de nombre de visiteurs testés ou d'amélioration prouvée de la traçabilité. Ces éléments ne sont pas validés. Je peux seulement affirmer que la solution prépare une transition vers un registre numérique et que les fonctions attendues côté application, stockage et signature sont opérationnelles.

### 2.7 Limites et points restant à suivre

La limite principale est l'absence de mise en service réelle à l'accueil. Même si la solution est validée techniquement, elle n'est pas encore utilisée au quotidien. Le registre papier ne doit donc pas être présenté comme remplacé. La solution vise à préparer cette transition, mais celle-ci dépend encore d'un élément matériel.

Le support physique de la tablette reste à installer par le service maintenance. Ce support doit permettre de sécuriser la tablette à l'accueil et d'éviter le vol. Tant que ce point n'est pas réglé, l'utilisation réelle ne peut pas être considérée comme finalisée.

Une autre limite concerne les tests en conditions réelles. Les tests techniques ont permis de valider l'application, le flux et la signature. En revanche, l'utilisation par l'accueil sur une période réelle pourra faire apparaître des ajustements à prévoir : ergonomie, compréhension des champs, rythme de saisie ou cas particuliers non rencontrés pendant les tests.

La confidentialité reste un point à surveiller. Un registre visiteurs contient des données personnelles. Il faut donc éviter les captures non anonymisées, les exports contenant de vrais noms ou les exemples basés sur des visiteurs réels. Si des illustrations sont ajoutées plus tard, elles devront être anonymisées ou remplacées par un schéma simplifié.

Le seuil de détection de signature doit aussi être suivi. Le seuil autour de 7000 caractères fonctionne comme solution pragmatique dans le contexte testé. Il faudra cependant rester prudent si le comportement du contrôle Power Apps évolue, si l'application est modifiée ou si un autre appareil produit des images de taille différente.

Le statut du registre papier devra également être confirmé lors de la version finale. À ce stade, je ne peux pas écrire qu'il est supprimé. Il faut rester sur une formulation prudente : la solution vise à remplacer ou réduire l'usage du registre papier, sous réserve de la mise en service réelle de la tablette.

Enfin, les moyens financiers et la période exacte restent à compléter si ces informations sont nécessaires dans la version finale. Je connais la durée approximative de la mission, environ un mois, mais pas forcément la période calendaire exacte à citer. De la même manière, je ne dispose pas d'un budget validé à intégrer dans le rapport.

### 2.8 Recul personnel sur la mission

Cette mission m'a permis de découvrir plus concrètement Power Apps et Power Automate. Avant de travailler sur ce registre visiteurs, je voyais surtout ces outils comme des moyens de créer rapidement des applications internes. Avec la mission, j'ai compris qu'il fallait aussi gérer les limites techniques, les formats de données et les erreurs entre les outils.

J'ai appris que le plus difficile n'était pas forcément de créer les champs du formulaire. La partie la plus délicate a été la signature, car elle passait par plusieurs transformations : image dans Power Apps, conversion en JSON avec données binaires, transmission au flux, nettoyage de la Data URI, conversion en binaire et ajout dans SharePoint. Cette chaîne m'a montré qu'une donnée simple pour l'utilisateur peut demander plusieurs traitements techniques.

L'historique d'exécution Power Automate m'a aussi beaucoup aidé. Il m'a appris à diagnostiquer une automatisation étape par étape. Au lieu de chercher au hasard, je pouvais vérifier ce que le flux recevait, ce qu'il transformait et à quel moment l'erreur apparaissait. Cette méthode est utile au-delà de cette mission, car elle s'applique à beaucoup de situations de diagnostic.

La gestion de la signature vide m'a également marqué. Au départ, on pourrait penser qu'une signature vide ne renvoie rien. En réalité, le contrôle pouvait produire une image blanche. Il fallait donc vérifier le comportement réel de l'outil et adapter la solution. Le seuil empirique autour de 7000 caractères n'est pas parfait, mais il répond au problème observé de manière simple et contrôlable.

Cette mission m'a aussi rappelé qu'une solution technique validée n'est pas forcément une solution déployée. L'application fonctionne, mais elle n'est pas encore utilisée à l'accueil tant que la tablette n'est pas sécurisée physiquement. Cela m'a permis de mieux comprendre la différence entre validation applicative, validation technique et mise en service réelle.

Sur le plan professionnel, j'ai travaillé avec une autonomie importante sur la partie opérationnelle. J'ai pu créer, tester, corriger et ajuster la solution, tout en gardant le tuteur comme point de validation. Cette manière de travailler m'a aidé à progresser, car elle m'a obligé à chercher par moi-même tout en sachant quand demander une validation.

Enfin, cette mission correspond bien au niveau CI1. Elle n'est pas une transformation complète de l'accueil ni un déploiement finalisé. C'est une contribution concrète à un besoin interne, avec une solution fonctionnelle, des limites identifiées et une mise en service encore dépendante d'un élément matériel. Elle m'a surtout appris à relier un besoin utilisateur, une solution technique et une démarche de vérification.

## 3. Sécurité opérationnelle AD / Microsoft 365

[À rédiger dans une prochaine étape]
