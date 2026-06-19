# Partie III — Méthodes, outils et ressources mobilisés

Cette partie ne reprend pas en détail les missions de la Partie II. Mon objectif est plutôt d'expliquer comment j'ai travaillé pendant cette première année d'alternance, avec quels outils, avec quelles ressources et avec quelles limites. Même si les sujets étaient différents, j'ai retrouvé une logique assez constante : partir d'un besoin concret, le reformuler, tester progressivement et rester prudent tant qu'un résultat n'était pas vraiment validé.

## 3.1 Démarche de travail et traitement d’un besoin

Dans le service informatique, les besoins n'arrivent pas toujours sous la forme d'une demande très cadrée. Souvent, le point de départ est plus simple : un usage à améliorer, un problème signalé par un utilisateur, un équipement à préparer ou un comportement technique à comprendre. Ma première étape consistait donc généralement à clarifier le besoin réel avec le tuteur ou avec les personnes concernées.

Cette phase de compréhension était importante, car la demande de départ ne disait pas toujours exactement ce qu'il fallait traiter. Il fallait souvent reformuler. Pour une tablette gérée avec Intune, par exemple, la vraie question n'était pas seulement de la configurer, mais de comprendre pour quel usage elle était prévue et jusqu'où la sécurité pouvait rester compatible avec la simplicité d'utilisation. Pour le registre visiteurs, j'ai aussi dû partir d'un usage concret à l'accueil avant de penser à la solution technique.

Une fois le besoin mieux défini, je passais par une phase de recherche. Cela pouvait être de la documentation, des vérifications dans l'outil, des échanges avec le tuteur ou le recoupement de plusieurs indices. J'ai beaucoup fonctionné comme cela sur les sujets que je découvrais, notamment Intune, mais aussi sur les analyses liées aux comptes et aux authentifications où il fallait comparer plusieurs hypothèses avant d'avancer.

L'organisation du travail restait assez souple. Le tuteur définissait généralement la priorité ou le cadre, puis je prenais en charge l'analyse, les recherches, les tests et les ajustements. En pratique, il fallait aussi composer avec les urgences du support quotidien. Cela m'a appris à faire la différence entre un sujet qui pouvait avancer progressivement et un autre qui demandait une vérification plus rapide avant de bloquer un utilisateur plus longtemps.

Je n'ai donc pas travaillé avec une logique de solution immédiate. J'avançais plutôt par essais progressifs : tester, observer, corriger, puis retester. C'est une méthode que j'ai retrouvée presque partout pendant l'année. Elle m'a aussi appris à ne pas conclure trop vite. Un paramètre peut sembler correct dans l'outil et se comporter autrement sur l'équipement réel. De la même manière, en sécurité opérationnelle, un symptôme peut faire penser à une cause évidente alors qu'il faut encore recouper plusieurs éléments.

Avant de considérer une solution comme acceptable, une validation restait nécessaire. Selon les cas, elle pouvait être technique, par test direct, ou passer par un échange avec le tuteur. Avec le recul, c'est sans doute ce que je retiens le plus de ma méthode de travail : comprendre le besoin, avancer par étapes et distinguer ce qui est encore une hypothèse de ce qui est réellement validé.

## 3.2 Outils techniques mobilisés

Les outils que j'ai utilisés pendant l'alternance sont variés, mais ils ont tous été mobilisés dans un environnement déjà en place chez Leroux. Je ne les présente donc pas comme une simple liste. Je les vois plutôt comme des moyens techniques cohérents avec le système d'information existant.

Un premier ensemble d'outils concerne la gestion des équipements mobiles. Dans ce cadre, Microsoft Intune et Android Enterprise m'ont surtout servi à préparer des tablettes de manière plus homogène, à encadrer certains usages et à éviter une configuration trop manuelle appareil par appareil. Ce sont donc des outils de gestion et de centralisation plus que des outils à décrire en détail.

Un deuxième ensemble concerne la création d'une solution interne simple à utiliser. Pour cela, j'ai mobilisé Power Apps, SharePoint et Power Automate. J'ai trouvé intéressant de travailler avec des outils déjà présents dans l'environnement Microsoft de l'entreprise, parce qu'ils permettaient de construire une réponse adaptée au besoin sans partir sur un développement plus lourd.

Un troisième ensemble regroupe les outils liés aux comptes, aux identités, aux accès et au diagnostic. On y retrouve Active Directory, Microsoft 365, les outils Microsoft liés aux identités et aux accès, ainsi que les journaux Windows et les outils d'administration utiles pour comprendre un verrouillage de compte ou une authentification échouée. Dans cette famille d'outils, ce qui comptait le plus n'était pas de connaître une seule console, mais de croiser plusieurs sources d'information.

Si ces outils ont été mobilisés, c'est aussi parce qu'ils étaient déjà cohérents avec l'existant. Je n'étais pas dans une logique de choix libre entre plusieurs solutions. Le plus souvent, il fallait utiliser ce qui était déjà présent dans l'entreprise, ce qui s'intégrait bien au reste du système d'information et ce qui répondait au besoin sans ajouter de complexité inutile.

Cette partie m'a aussi appris qu'un outil ne résout rien à lui seul. Intune ne remplace pas les tests, Power Apps ne remplace pas la réflexion sur l'usage réel, et les journaux Windows ne remplacent pas l'analyse. Les outils donnent des moyens d'action, mais ils ne remplacent ni la méthode ni la vérification.

## 3.3 Ressources humaines, matérielles et documentaires

Au-delà des outils, j'ai travaillé avec plusieurs types de ressources. La première a été la ressource humaine. Dans une équipe informatique de deux personnes, le tuteur a un rôle important : il cadre le besoin, aide à prioriser les sujets et valide les décisions qui engagent davantage l'entreprise. Même lorsque j'étais autonome sur l'analyse ou les tests, je ne travaillais donc pas seul.

Les échanges avec les utilisateurs ont aussi compté. Dans plusieurs situations, comprendre la demande ou confirmer un comportement réel demandait d'aller voir directement la personne concernée, de reformuler le problème ou de vérifier si la solution proposée correspondait bien à l'usage. Cela m'a appris qu'un besoin informatique n'est pas toujours complètement visible depuis l'outil.

Certaines missions dépendaient aussi d'autres interlocuteurs internes. Le service maintenance en est un bon exemple, car la mise en service du registre visiteurs ne dépend pas seulement de la partie applicative. Cela m'a montré qu'une solution peut être prête sur le plan technique tout en restant liée à une contrainte matérielle ou interservices.

Les ressources matérielles ont eu leur importance : postes de travail, tablettes Android professionnelles, environnement de test et tablette destinée à l'accueil. Sans équipement réel, plusieurs validations auraient été beaucoup plus théoriques que pratiques.

Les ressources documentaires ont aussi été utiles. La documentation Microsoft m'a servi à comprendre certains comportements ou certaines possibilités des outils. L'historique d'exécution de Power Automate m'a aidé à diagnostiquer plus précisément ce qui se passait dans le flux. Sur les sujets de sécurité, les recherches techniques et l'expérience du tuteur m'ont surtout aidé à mieux interpréter les événements observés.

[À compléter] Les coûts, licences ou arbitrages budgétaires précis n'ont pas été documentés à ce stade. Je préfère donc ne pas développer un volet financier qui ne serait pas assez fiable.

## 3.4 Tests, validations et gestion des limites

Pendant l'alternance, j'ai vite compris qu'une solution technique n'a pas beaucoup de valeur si elle n'est pas testée dans des conditions proches de son usage réel. Les tests ont donc pris une place importante dans ma manière de travailler. Je ne pouvais pas me contenter de voir qu'un paramètre existait dans un outil ou qu'une solution semblait correcte sur le papier.

Cette logique m'a surtout appris à comparer ce qui était attendu avec ce qui se passait réellement. Dans certains cas, la validation était surtout technique, par exemple sur un équipement ou dans un flux. Dans d'autres, elle était plus prudente, comme en sécurité opérationnelle, où il fallait distinguer une cause probable d'une cause réellement confirmée.

J'ai aussi mieux compris la différence entre un résultat techniquement valable et une mise en service réelle. C'est un point qui m'a marqué pendant l'année, parce qu'il montre qu'une mission ne se termine pas forcément au moment où la partie technique fonctionne.

La gestion des limites fait également partie de cette démarche. Je suis en première année d'alternance, donc certaines situations demandaient du recul, un échange avec le tuteur ou une validation avant d'aller plus loin. Cette posture m'a aidé à rester plus rigoureux et à ne pas annoncer trop vite qu'un sujet était terminé.

Plus largement, j'ai retenu qu'il fallait garder une trace claire de ce qui était validé et de ce qui restait à vérifier. Dans le travail quotidien comme dans le rapport, cette distinction évite de mélanger objectif, essai concluant et résultat final.

## 3.5 Confidentialité, anonymisation et posture professionnelle

La confidentialité a été une contrainte transversale dans l'ensemble de mes missions. Même lorsque le sujet paraissait surtout technique, il impliquait souvent des informations qu'il n'était pas utile, ni prudent, de diffuser telles quelles dans un rapport : noms de comptes, noms de postes, noms de serveurs, détails de configuration interne, données visiteurs ou extraits de journaux.

Concrètement, cela m'a obligé à rester général sur certains points. Dans les sujets de sécurité opérationnelle, je ne peux pas reprendre de journaux bruts, de noms d'utilisateurs ou d'adresses internes. Pour le registre visiteurs, les données personnelles doivent rester absentes du rapport. Pour Intune, il n'est pas nécessaire de publier des éléments internes trop précis dès lors qu'ils n'apportent rien à la compréhension de la démarche.

Cette contrainte ne m'a pas empêché d'expliquer ce que j'ai fait. Elle m'a surtout appris à trouver un équilibre entre précision technique et protection de l'information. Dans un rapport d'alternance, il faut pouvoir expliquer une méthode de travail sans transformer l'expérience en documentation interne complète.

Cette logique rejoint aussi la posture professionnelle attendue d'un alternant. J'ai pu gagner en autonomie sur la partie opérationnelle, mais j'ai aussi compris qu'il fallait savoir quoi communiquer, comment le formuler et à quel moment une validation restait nécessaire. Avec le recul, cette prudence fait partie de ce que cette première année m'a appris.
