# Partie II — Missions réalisées

Statut : Version brouillon en cours

## 1. Microsoft Intune / Android Enterprise

### 1.1 Contexte et besoin initial

La première mission principale que je présente concerne la gestion des tablettes Android professionnelles avec Microsoft Intune et Android Enterprise. Elle s'inscrit dans le fonctionnement du service informatique, car les tablettes font partie des équipements utilisés dans l'entreprise et doivent rester adaptées aux usages des utilisateurs.

Chez Leroux, les tablettes Android professionnelles répondent à deux besoins différents. Le premier concerne une tablette destinée au registre visiteurs à l'accueil. Le second concerne des tablettes utilisées en production. Ces deux usages ne sont pas identiques, mais ils ont un point commun : les appareils doivent être configurés de manière cohérente, avec les bonnes applications, les restrictions nécessaires et un niveau de sécurité adapté à un usage professionnel.

Avant cette mission, l'enjeu n'était pas seulement de préparer une tablette isolée. Il fallait surtout comprendre comment administrer ces équipements avec une logique plus centralisée. Dans un contexte industriel, une tablette mal configurée peut poser plusieurs problèmes : accès à des fonctions non souhaitées, difficulté à maintenir une configuration homogène, installation d'applications non prévues, modification de paramètres réseau ou perte de maîtrise sur l'appareil. L'objectif était donc de rendre l'utilisation plus simple pour les utilisateurs, tout en gardant un cadre plus sûr pour le service informatique.

La mission a représenté environ deux mois de travail au total. Cette durée comprend la prise en main de Microsoft Intune, la configuration de la tablette destinée au registre visiteurs et la configuration des tablettes de production. La période calendaire exacte reste à préciser : `[À vérifier]`. Je ne peux donc pas indiquer de dates précises dans ce brouillon sans validation.

Microsoft Intune est l'outil qui permet d'administrer les appareils depuis un portail centralisé. Dans cette mission, il a été utilisé avec Android Enterprise, en mode fully managed. Ce mode correspond à un appareil entièrement géré par l'entreprise. Cela signifie que la tablette n'est pas pensée comme un appareil personnel auquel on ajoute quelques règles, mais comme un équipement professionnel configuré pour un usage défini.

Pour moi, cette mission a aussi été une découverte. Je connaissais déjà certains principes de gestion de comptes, de postes ou d'outils Microsoft, mais la gestion d'appareils mobiles avec Intune demande une logique différente. Il faut comprendre le lien entre les profils, les groupes, les applications, les restrictions, l'enrôlement et les tests réalisés sur l'appareil. C'est cette démarche progressive qui a structuré mon travail.

### 1.2 Objectifs de la mission

Le premier objectif était de standardiser la configuration des tablettes professionnelles. L'idée était d'éviter que chaque tablette soit configurée manuellement de manière différente. Une configuration homogène permet au service informatique de mieux savoir ce qui est appliqué sur les appareils et de limiter les écarts entre les tablettes.

Le deuxième objectif concernait la sécurité. Les tablettes étant utilisées dans un cadre professionnel, certaines fonctions devaient être limitées. Il ne s'agissait pas de bloquer l'utilisateur pour le principe, mais de réduire les risques liés à un appareil mobile : réinitialisation non autorisée par l'utilisateur, ajout de comptes personnels, partage de connexion, modification du Wi-Fi ou usage non prévu de supports externes.

Le troisième objectif était de simplifier l'usage pour les utilisateurs. Une tablette professionnelle doit être assez cadrée pour éviter les erreurs, mais elle doit rester utilisable. Si la configuration est trop restrictive ou mal adaptée, elle peut gêner le travail au lieu de l'aider. Il fallait donc rechercher un équilibre entre sécurité, simplicité et contraintes réelles du terrain.

Un autre objectif était de préparer une gestion plus centralisée du parc mobile. Grâce à Intune, le service informatique peut retrouver les appareils enrôlés, appliquer des configurations, déployer des applications et suivre plus facilement l'état général des tablettes. Cela ne remplace pas les vérifications humaines, mais cela donne un cadre plus propre qu'une configuration uniquement manuelle.

Enfin, la mission devait permettre de tester les configurations avant de les considérer comme utilisables. Dans un environnement professionnel, il n'est pas suffisant de créer une règle dans un portail d'administration. Il faut vérifier son comportement réel sur la tablette. Certaines restrictions peuvent être visibles immédiatement, d'autres nécessitent un délai de synchronisation ou un test précis. Cette partie de vérification a été importante dans mon apprentissage.

### 1.3 Moyens et outils utilisés

Les principaux outils utilisés ont été Microsoft Intune et Android Enterprise. Intune a servi à créer et appliquer les configurations. Android Enterprise a fourni le cadre de gestion des tablettes Android professionnelles, avec un mode fully managed adapté à des appareils appartenant à l'entreprise.

Les appareils concernés sont des tablettes Samsung Galaxy Tab S10 FE+ sous Android 15. Le nombre exact de tablettes concernées ne doit pas être inventé et reste à confirmer : `[À vérifier]`. Dans cette section, je parle donc des tablettes de manière générale, sans indiquer de volume précis.

L'enrôlement des tablettes s'appuyait sur un token et sur un groupe associés à l'usage production. Comme ces noms correspondent à une configuration interne, je ne les détaille pas dans la rédaction finale de la mission. Dans le rapport, il est plus prudent de parler d'un token d'enrôlement dédié et d'un groupe de tablettes de production. Cela évite d'exposer inutilement des noms internes.

Les applications prévues ou déployées sur les tablettes comprenaient des outils bureautiques et collaboratifs comme Word, Excel, PowerPoint, OneNote, Teams et Outlook. D'autres applications utiles étaient également disponibles, comme Collabora et Adobe Reader. Ces applications correspondent à des besoins d'usage professionnel : consultation, saisie, communication ou ouverture de documents.

Des liens web utiles étaient aussi prévus sur les tablettes, notamment vers la GMAO, Fastilog et GLPI. GLPI est ici seulement cité comme lien ou outil disponible sur tablette. Il ne s'agit pas d'une mission principale du rapport, conformément aux règles du projet.

Les moyens humains mobilisés reposaient principalement sur le service informatique. Mon tuteur définissait le cadre et validait les décisions importantes. De mon côté, j'ai pris en charge la partie opérationnelle : recherches, configuration, tests, enrôlement, ajustements et échanges lorsque cela était nécessaire. Les choix techniques structurants et les décisions financières restaient validés par le tuteur ou par l'entreprise.

Les moyens financiers ne sont pas détaillés dans ce brouillon, car je ne dispose pas d'information validée sur un budget, un coût d'achat ou un arbitrage financier lié aux tablettes et aux licences : `[À compléter]`. Je me limite donc aux moyens matériels, techniques, humains et documentaires réellement connus.

La documentation a aussi été une ressource importante, même si la procédure formelle éventuellement produite reste à confirmer : `[À compléter]`. Pour prendre en main Intune, il a fallu s'appuyer sur les informations disponibles, tester directement dans l'environnement et vérifier le résultat sur les tablettes.

### 1.4 Démarche suivie

Dans un premier temps, j'ai cherché à comprendre le besoin. Il ne s'agissait pas seulement de savoir quelles tablettes devaient être configurées, mais aussi de comprendre leur usage. La tablette d'accueil devait être liée au registre visiteurs, alors que les tablettes de production répondaient à un autre contexte d'utilisation. Cette distinction était importante pour éviter d'appliquer une configuration identique sans réfléchir aux usages réels.

J'ai ensuite pris en main Microsoft Intune et Android Enterprise. Cette étape a demandé du temps, car l'outil comporte plusieurs notions qui se croisent. Il faut différencier l'enrôlement de l'appareil, les profils de configuration, les restrictions, les groupes et les applications. Au début, le risque était de confondre ces éléments ou de ne pas comprendre exactement où devait être appliquée une règle.

Une fois le principe général compris, j'ai travaillé sur le mode Android Enterprise fully managed. Ce mode permet de préparer une tablette entièrement gérée par l'entreprise. L'enrôlement passe par un token dédié, qui rattache l'appareil à la gestion Intune. L'appareil peut ensuite recevoir les paramètres associés au groupe prévu pour les tablettes concernées.

La configuration a ensuite porté sur les restrictions d'usage. Plusieurs paramètres ont été appliqués ou préparés pour cadrer l'utilisation professionnelle. Parmi les restrictions connues, on retrouve le blocage de la réinitialisation non autorisée par l'utilisateur, la restriction de certains usages USB ou de supports externes, le blocage du partage de connexion, le blocage des modifications Wi-Fi et le blocage de l'ajout de comptes Google. Ces choix permettent de limiter les manipulations qui pourraient sortir la tablette de son usage prévu. Le détail exact de certains paramètres dépend toutefois de ce qui est réellement disponible dans Intune, du mode Android Enterprise utilisé et de la version Android de l'appareil : `[À vérifier]`.

La sécurité de l'accès à l'appareil a également été prise en compte. Un mot de passe de 8 caractères a été défini, avec un effacement de l'appareil après 10 échecs. Cette règle doit être présentée avec prudence : elle renforce la protection de l'appareil, mais elle demande aussi d'être expliquée aux utilisateurs concernés pour éviter les mauvaises manipulations.

La gestion des mises à jour faisait aussi partie de la configuration. Une plage horaire de 03:00 à 05:00 a été retenue pour les mises à jour. L'intérêt est de limiter l'impact sur l'utilisation de la tablette pendant les périodes de travail. Ce réglage montre qu'une configuration technique doit tenir compte du moment où l'appareil est réellement utilisé.

J'ai aussi travaillé sur les applications nécessaires. L'objectif était que les tablettes disposent des outils utiles sans laisser l'utilisateur chercher ou installer lui-même les applications. Les applications bureautiques, collaboratives et de consultation de documents devaient être disponibles selon les besoins. Les liens web utiles devaient également faciliter l'accès aux outils métiers ou de support prévus.

Après la configuration, les tests ont été essentiels. Il fallait vérifier que la tablette s'enrôlait correctement, qu'elle rejoignait le bon périmètre de gestion, que les applications apparaissaient, que les restrictions étaient bien prises en compte et que l'utilisation restait possible. Les résultats précis des tests restent à détailler avec plus de preuves ou d'exemples : `[À compléter]`.

Les ajustements ont fait partie de la démarche. Une configuration Intune n'est pas forcément parfaite dès le premier essai. Certains paramètres peuvent être trop stricts, mal compris ou ne pas produire immédiatement l'effet attendu. J'ai donc avancé par essais, vérifications et corrections, en gardant le tuteur comme point de validation pour les choix importants.

Cette démarche m'a montré qu'un outil d'administration centralisée ne supprime pas le besoin de méthode. Intune permet de pousser des règles, mais il faut quand même comprendre le besoin, vérifier les effets réels et garder une trace de ce qui est fait. C'est ce qui distingue une simple manipulation technique d'une démarche plus professionnelle.

### 1.5 Difficultés rencontrées

La première difficulté a été la prise en main de Microsoft Intune. L'outil est complet, mais il peut être difficile à aborder au début. Plusieurs notions se ressemblent ou s'enchaînent : enrôlement, groupe, profil, restriction, application, affectation. Comprendre le rôle de chaque élément a demandé du temps.

Une autre difficulté a été de distinguer ce qui se configure dans le portail et ce qui est réellement appliqué sur la tablette. Le fait de créer une règle ne suffit pas. Il faut que l'appareil soit bien enrôlé, qu'il appartienne au bon groupe, qu'il synchronise les paramètres et que la restriction soit compatible avec le mode de gestion choisi. Cette vérification est importante, car elle évite de croire qu'une configuration est effective alors qu'elle ne l'est pas encore.

La gestion des restrictions a aussi demandé de la prudence. Certaines restrictions semblent évidentes sur le papier, mais elles peuvent avoir un impact sur l'usage réel. Par exemple, bloquer les modifications Wi-Fi peut être pertinent pour éviter des changements non maîtrisés, mais cela suppose que la configuration réseau prévue soit correcte. De la même manière, limiter les supports externes ou l'ajout de comptes Google renforce le cadre professionnel, mais il faut vérifier que cela ne bloque pas un besoin légitime.

La différence entre la tablette d'accueil et les tablettes de production a également nécessité de réfléchir aux usages. Une tablette destinée au registre visiteurs n'a pas forcément les mêmes besoins qu'une tablette utilisée en production. Même si la mission porte globalement sur Intune et Android Enterprise, il ne fallait pas oublier que les équipements correspondent à des situations différentes.

Le manque de données mesurées constitue une limite pour la rédaction. Je peux affirmer que les tablettes ont été configurées via Intune et qu'elles sont utilisées en production, car ces éléments sont validés dans le contexte. En revanche, je ne peux pas inventer un nombre exact de tablettes, un gain de temps, une baisse d'incidents ou un indicateur chiffré. Ces éléments devront être complétés seulement s'ils sont confirmés.

Enfin, cette mission demandait de rester à ma place d'alternant. J'ai géré le processus de bout en bout sur la partie opérationnelle, mais cela ne signifie pas que j'ai décidé seul des orientations importantes. Les choix finaux, surtout lorsqu'ils engagent l'entreprise, restent validés par le tuteur ou par l'entreprise. Cette limite est normale et elle rend la présentation plus juste.

### 1.6 Résultats obtenus

Le premier résultat est la mise en place d'une configuration Intune pour les tablettes Android professionnelles concernées. Les tablettes ont été configurées avec Android Enterprise en mode fully managed, ce qui permet une gestion plus cadrée que des appareils configurés individuellement.

Les tablettes de production sont utilisées en production. Cette information peut être présentée, car elle est validée dans les fichiers de contexte. Il faut toutefois rester prudent sur le périmètre exact : le nombre de tablettes, les dates précises et l'étendue complète du déploiement restent à confirmer : `[À vérifier]`.

La configuration a permis d'appliquer des restrictions de sécurité adaptées à un usage professionnel. Les restrictions comme le blocage de la réinitialisation non autorisée par l'utilisateur, du partage de connexion, de l'ajout de comptes Google ou de certaines modifications système contribuent à mieux maîtriser les appareils. Le mot de passe et l'effacement après plusieurs échecs ajoutent aussi une protection supplémentaire.

Les applications nécessaires ont été rendues disponibles sur les tablettes, avec des outils comme Word, Excel, PowerPoint, OneNote, Teams, Outlook, Collabora et Adobe Reader. Les liens web utiles, notamment vers la GMAO, Fastilog et GLPI, permettent aussi de rapprocher la tablette de ses usages concrets. Là encore, GLPI reste uniquement cité comme lien ou outil disponible, pas comme sujet principal.

Un autre résultat est l'amélioration de l'homogénéité de la configuration. Grâce à Intune, les tablettes peuvent recevoir une configuration commune selon leur groupe et leur usage. Cela facilite le suivi par le service informatique et limite les écarts entre appareils. Je formule ce point comme une amélioration de maîtrise, pas comme un gain mesuré, car aucun indicateur chiffré n'est disponible à ce stade.

La mission a aussi permis de mieux structurer la gestion du parc mobile. Le service informatique dispose d'un cadre plus centralisé pour suivre et configurer les tablettes. Cela ne veut pas dire que tout est terminé ou que plus aucun ajustement ne sera nécessaire. Les usages réels doivent continuer à être observés, surtout dans un environnement où les besoins peuvent évoluer.

Pour l'entreprise, l'apport principal est donc une gestion plus homogène et plus sécurisée des tablettes professionnelles. Pour moi, le résultat est aussi une montée en compétence sur un outil d'administration moderne, utilisé dans beaucoup d'environnements professionnels.

### 1.7 Limites et points restant à suivre

Plusieurs limites doivent être indiquées clairement pour éviter de survaloriser la mission. La première concerne le nombre exact de tablettes. Il n'est pas confirmé dans les fichiers de contexte et ne doit donc pas être ajouté sans validation : `[À vérifier]`.

La période exacte de la mission doit aussi être précisée. La durée globale d'environ deux mois est validée, mais les dates calendaires ne le sont pas encore : `[À compléter]`. Cette information sera utile pour situer la mission dans l'année d'alternance.

Les résultats mesurables ne sont pas disponibles à ce stade. Je ne peux donc pas indiquer de gain de temps, de baisse d'incidents, de taux de conformité ou de pourcentage de déploiement. Si ces indicateurs existent, ils devront être fournis ou validés avant la version finale. Sinon, il faudra rester sur une analyse qualitative.

La documentation reste également à confirmer. Si une procédure interne ou une note de configuration a été produite, elle pourra être mentionnée de manière générale, sans exposer de détails sensibles. Si elle n'a pas été formalisée, il faudra indiquer que la documentation reste un axe d'amélioration : `[À compléter]`.

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

[À rédiger dans une prochaine étape]

## 3. Sécurité opérationnelle AD / Microsoft 365

[À rédiger dans une prochaine étape]
