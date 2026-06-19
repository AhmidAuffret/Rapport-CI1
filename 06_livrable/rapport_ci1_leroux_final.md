# Éléments préliminaires

Rapport confidentiel - diffusion limitée à l'IMT Nord Europe et à l'entreprise Leroux.

## Remerciements

Je tiens à remercier Loïc Humann, qui a été mon tuteur et responsable informatique au début de mon alternance, pour son accompagnement lors de mes premiers mois en entreprise et pour la confiance qu'il m'a accordée sur mes premières missions.

Je remercie également Thierry Devigne, qui a repris ce rôle par la suite, pour son suivi, ses conseils et la continuité de l'accompagnement pendant cette première année.

Je remercie aussi Quentin Despelchin, directeur administratif et financier, pour l'accueil et le cadre donné à mon alternance, ainsi qu'Éloïse Six, directrice des ressources humaines, et Ghislain Lesaffre, président-directeur général, pour leur accueil au sein de l'entreprise.

Enfin, je remercie les collaborateurs avec lesquels j'ai pu travailler au quotidien. Leurs échanges, leurs retours et leur disponibilité m'ont permis de mieux comprendre les besoins du terrain et de progresser dans mes missions.

## Résumé

Ce rapport présente ma première année d'alternance chez Leroux, une entreprise industrielle agroalimentaire spécialisée dans la transformation de la chicorée. J'y occupe le poste d'alternant administrateur systèmes et réseaux au sein du service informatique, dans une équipe de deux personnes.

Au cours de cette période, j'ai travaillé sur trois missions principales. La première concerne la gestion de tablettes Android professionnelles avec Microsoft Intune et Android Enterprise. La deuxième porte sur la création d'un registre visiteurs numérique avec Power Apps, SharePoint et Power Automate. La troisième correspond à une mission continue de sécurité opérationnelle autour d'Active Directory et de Microsoft 365, à travers l'analyse de comptes, d'authentifications et de journaux.

Ces missions m'ont permis de découvrir des outils nouveaux, de développer une méthode de travail plus progressive et de mieux comprendre le lien entre configuration technique, besoin utilisateur et contraintes d'une entreprise industrielle. Elles m'ont aussi appris à avancer avec prudence, à tester avant de valider et à distinguer clairement un résultat confirmé d'un point restant à vérifier.

Ce rapport présente donc à la fois le contexte de mon alternance, les méthodes et outils mobilisés, les difficultés rencontrées, les solutions apportées, ainsi que le bilan personnel que je retiens de cette première année et les perspectives pour la suite de mon parcours.

## Mots-clés

Alternance ; service informatique ; administration systèmes et réseaux ; Microsoft Intune ; Android Enterprise ; Power Apps ; SharePoint ; Power Automate ; Active Directory ; Microsoft 365 ; sécurité opérationnelle

## Abstract

This report presents my first year of apprenticeship at Leroux, a food industry company specialized in chicory processing. I work as a systems and network administration apprentice in the IT department, in a team of two people.

During this period, I worked on three main missions. The first one was about managing professional Android tablets with Microsoft Intune and Android Enterprise. The second one was about creating a digital visitor register with Power Apps, SharePoint and Power Automate. The third one was a continuous operational security mission around Active Directory and Microsoft 365, with account checks, authentication issues and log analysis.

These missions helped me discover new tools, improve my working method and better understand the link between technical configuration, user needs and the constraints of an industrial company. They also taught me to work carefully, to test before validating and to separate confirmed results from points that still need verification.

This report therefore presents the context of my apprenticeship, the methods and tools I used, the difficulties I met, the solutions I applied, and the personal lessons and perspectives I keep for the rest of my apprenticeship.

## Keywords

Apprenticeship ; IT department ; systems and network administration ; Microsoft Intune ; Android Enterprise ; Power Apps ; SharePoint ; Power Automate ; Active Directory ; Microsoft 365 ; operational security


---

# Introduction

Ce rapport d'activité entreprise CI1 s'inscrit dans le cadre de ma première année du cycle ingénieur à l'IMT Nord Europe, réalisée en alternance. Il a pour objectif de présenter mon activité en entreprise, mais aussi de prendre du recul sur cette première période d'apprentissage. Je ne vais donc pas seulement décrire des missions techniques. Je vais aussi expliquer le contexte dans lequel j'ai travaillé, les méthodes que j'ai découvertes, les difficultés rencontrées et ce que ces expériences m'ont permis de comprendre sur le métier d'administrateur systèmes et réseaux.

Mon alternance se déroule chez Leroux, une entreprise industrielle agroalimentaire spécialisée dans la transformation de la chicorée. L'entreprise dispose de deux sites principaux liés à son activité : l'usine principale d'Orchies et le site de Vieille-Église, où la chicorée est séchée et préparée avant d'être utilisée à Orchies. Leroux est une entreprise industrielle à taille humaine, implantée historiquement dans les Hauts-de-France, avec un effectif de l'ordre de la centaine de salariés. Les chiffres financiers et les volumes de production restent cependant à vérifier avec des sources fiables avant d'être utilisés dans le rapport.

Dans ce contexte industriel, l'informatique est directement liée au fonctionnement quotidien de l'entreprise. Le service intervient sur les outils, les comptes, les postes, les tablettes et les incidents rencontrés par les utilisateurs. Cela m'a amené à travailler sur des sujets liés à la continuité de service, à la sécurité, à la confidentialité et aux tests avant mise en production.

Je travaille au sein du service informatique, qui n'a pas de nom spécifique. Le service est composé de deux personnes : le responsable informatique et moi, en tant qu'alternant administrateur systèmes et réseaux. Le tuteur a changé pendant l'année. Au début, Loïc Humann était responsable informatique et tuteur. Après son départ, Thierry Devigne l'a remplacé dans ces deux rôles. Il n'y a donc toujours eu qu'un seul tuteur à la fois. L'organisation du service reste souple : les sujets sont répartis selon les besoins, les priorités, les projets en cours et les disponibilités.

Dans ce cadre, j'ai une autonomie importante sur la partie opérationnelle. Mon tuteur définit généralement le besoin, la mission ou le cadre de travail, puis je prends en charge l'analyse, les recherches, les tests, la configuration et les ajustements. Les choix finaux qui engagent fortement l'entreprise, notamment sur les aspects techniques ou financiers, restent toutefois validés par le tuteur ou par l'entreprise. Cette limite est importante : je participe à des missions concrètes et je progresse en autonomie, mais je ne suis pas le décideur principal du système d'information.

Le fil conducteur du rapport est le suivant : comment une première année d'alternance en administration systèmes et réseaux permet-elle de contribuer à la continuité, à la sécurité et à la modernisation du système d'information d'une entreprise industrielle ? Cette question permet de relier les missions entre elles sans les présenter comme une simple liste d'activités. Elle correspond aussi au niveau CI1, car elle met l'accent sur la compréhension du contexte, la démarche suivie, les limites rencontrées et le bilan personnel.

Les missions principales présentées dans ce rapport s'organisent autour de trois sujets. Le premier concerne Microsoft Intune et Android Enterprise. Cette mission, menée sur environ deux mois, avait pour objectif de préparer une gestion plus homogène et plus sécurisée des tablettes Android professionnelles. Elle concerne trois tablettes Samsung Galaxy Tab S10 FE+ destinées à la production, ainsi qu'une tablette distincte prévue pour le registre visiteurs. Ce sujet touche donc à la modernisation du parc mobile, à la sécurité des usages et à la continuité du travail des utilisateurs.

Le deuxième sujet porte sur le registre visiteurs numérique réalisé avec Power Apps, SharePoint et Power Automate. La mission a duré environ un mois et vise à préparer la transition d'un registre papier vers une solution utilisable sur tablette. La solution a été validée techniquement, mais elle n'est pas encore utilisée à l'accueil. Sa mise en service dépend de l'installation d'un support physique par le service maintenance, afin de sécuriser la tablette. Ce point est important, car il ne faut pas présenter cette mission comme un déploiement déjà terminé en usage réel.

Le troisième sujet concerne la sécurité opérationnelle autour d'Active Directory, de Microsoft 365 et de Microsoft Entra. Il ne s'agit pas d'un projet unique, mais d'une mission continue liée aux incidents et demandes quotidiennes du service informatique. J'ai participé à des diagnostics autour de comptes, de connexions, d'authentification et de journaux. Cette mission est liée au fil conducteur par la méthode qu'elle demande : avancer avec prudence, comparer plusieurs sources et distinguer un symptôme d'une cause réellement vérifiée.

Ces trois missions se complètent. La gestion des tablettes professionnelles s'inscrit dans une logique de modernisation et de sécurisation des usages. Le registre visiteurs numérique prépare une transition vers un outil interne plus adapté au suivi des passages, tout en gardant une attention particulière à la confidentialité. L'analyse des incidents liés aux comptes, aux connexions et aux journaux met en avant l'importance de la sécurité opérationnelle et de la méthode de diagnostic. Ensemble, elles montrent que mon rôle d'alternant ne consiste pas seulement à appliquer des procédures. Il consiste aussi à comprendre le besoin, tester les solutions, échanger avec les utilisateurs et savoir distinguer ce qui est validé de ce qui reste à vérifier.

Le rapport suivra une progression en plusieurs parties. Dans un premier temps, il présentera Leroux, son contexte industriel et le service informatique dans lequel j'évolue. Cette partie permettra de situer les missions dans leur environnement réel, avec les informations encore à compléter ou à sourcer lorsque cela sera nécessaire. Ensuite, le rapport détaillera les trois missions principales en suivant une structure commune : contexte, objectifs, contraintes, déroulement, moyens mobilisés, difficultés rencontrées, solutions apportées, résultats obtenus et recul personnel. Une partie sera également consacrée aux méthodes, aux outils et aux ressources utilisés. Enfin, le rapport se terminera par un bilan personnel sur les compétences développées, les limites rencontrées et les perspectives d'évolution pour la suite de l'alternance.

Cette introduction pose le cadre général du rapport avec les informations validées à ce stade. Plusieurs éléments devront encore être complétés ou vérifiés avant la version finale, notamment les sources publiques sur Leroux, le niveau de confidentialité demandé par l'entreprise, l'autorisation finale de citer certaines personnes, les périodes exactes des missions et les résultats réellement validés pour chaque sujet.


---

# Partie I — Présentation de Leroux et du service informatique

## 1. Présentation générale de Leroux

Leroux est l'entreprise dans laquelle je réalise mon alternance de première année CI1. Avant de présenter mes missions, il est nécessaire de situer le contexte dans lequel elles s'inscrivent. Les actions menées au sein du service informatique répondent aux besoins d'une entreprise industrielle, avec des contraintes de production, d'organisation, de support et de sécurité.

Leroux peut être présentée comme une entreprise industrielle agroalimentaire spécialisée dans la transformation de la chicorée. Cette formulation reste volontairement simple, car elle correspond aux informations disponibles pour cette rédaction. L'activité de l'entreprise est liée à un produit spécifique, la chicorée, transformée pour différents usages alimentaires. Le site officiel de Leroux présente la marque comme historiquement liée à la chicorée depuis 1858, avec le rachat de la manufacture Herbo fils & Cie par Jean-Baptiste Alphonse Leroux. Cette date peut être utilisée comme repère historique et devra être associée à la source officielle dans la bibliographie finale.

L'entreprise est principalement implantée à Orchies, dans le Nord. Cette implantation montre que mon alternance se déroule dans une entreprise industrielle ancrée localement. Leroux n'est pas seulement une marque commerciale : c'est aussi un site de production, des équipements, des utilisateurs, des flux de travail et des contraintes quotidiennes. Pour le service informatique, cela signifie que les outils numériques doivent rester disponibles et adaptés à des usages concrets.

Les chiffres disponibles doivent être utilisés avec prudence, car ils peuvent varier selon les sources et les années. Je retiens donc une formulation volontairement sobre : Leroux est une entreprise industrielle à taille humaine, implantée historiquement dans les Hauts-de-France, avec un effectif de l'ordre de la centaine de salariés. Cette prudence évite d'introduire un chiffre exact contradictoire dans le rapport.

D'autres chiffres publics donnent un ordre de grandeur de l'activité et du rayonnement de Leroux : le site officiel mentionne près de 200 planteurs, 50 pays, environ 60 000 tonnes de racines traitées par an et environ 1 300 hectares cultivés en moyenne chaque année. Ces éléments doivent encore être associés proprement aux sources utilisées. Je ne les utilise donc pas comme analyse économique détaillée, mais seulement comme éléments de contexte.

Je ne retiens pas de chiffre d'affaires, de résultat financier ou d'information stratégique interne, car ces éléments ne sont pas validés dans les fichiers de contexte. De la même manière, je ne présente pas d'organigramme complet de l'entreprise, car il n'est pas encore validé pour diffusion. Cette prudence permet de garder un rapport fiable : l'objectif de cette première partie n'est pas de produire une fiche institutionnelle exhaustive, mais de présenter l'entreprise suffisamment pour comprendre le cadre de mon alternance.

## 2. Une entreprise industrielle agroalimentaire spécialisée dans la chicorée

L'activité de Leroux repose sur la transformation de la chicorée. Pour un lecteur qui ne connaît pas ce produit, la chicorée peut être présentée simplement comme une plante dont la racine est transformée pour obtenir des produits alimentaires, notamment des boissons ou des ingrédients à base de chicorée. Le site officiel présente des produits en grains, liquides, solubles, en dosettes ou sous forme d'infusion.

La chicorée est à la fois liée à une histoire locale et à un savoir-faire industriel. Leroux transforme une matière première agricole en produits finis ou semi-finis. Cela implique plusieurs étapes, depuis la préparation de la racine jusqu'à la transformation et au conditionnement. Les étapes exactes de fabrication ne sont pas détaillées ici, car cette partie n'a pas pour objectif d'expliquer tout le processus industriel. Il suffit de comprendre que l'entreprise fonctionne dans un environnement de production, avec des équipements, des contraintes de continuité et des besoins informatiques associés.

Le lien avec l'agroalimentaire est également important. Dans ce type d'entreprise, l'informatique ne sert pas uniquement à gérer des postes de travail administratifs. Elle accompagne aussi les usages quotidiens des équipes, les outils métiers, les accès, les tablettes, les comptes utilisateurs et les moyens de communication. Même lorsque je travaille sur une configuration Microsoft Intune, un registre visiteurs ou une analyse de comptes Active Directory, je dois garder en tête que ces outils sont utilisés dans un contexte industriel réel.

Leroux dispose d'un savoir-faire historique autour de la chicorée. Le site officiel met en avant une continuité depuis 1858 et une évolution des produits au fil du temps. Pour le rapport, il n'est pas nécessaire de détailler toute la chronologie. Je retiens surtout que l'entreprise s'inscrit dans une histoire longue, avec une spécialisation forte. Cette spécialisation rend le contexte différent d'une entreprise de services purement numérique : l'informatique vient soutenir une activité de transformation, de production, d'accueil, d'administration et de support aux utilisateurs.

Cette caractéristique influence la manière de travailler au service informatique. Les demandes peuvent venir de plusieurs profils d'utilisateurs : fonctions administratives, production, accueil, maintenance ou encadrement. Cette diversité oblige le service informatique à adapter son niveau d'explication et ses interventions selon les usages. C'est aussi ce qui rend l'alternance intéressante : je ne travaille pas seulement sur des outils théoriques, mais sur des solutions qui doivent être compréhensibles et utilisables dans l'environnement de l'entreprise.

Il faut cependant rester mesuré dans la présentation. Je ne peux pas affirmer que mes missions ont transformé l'organisation industrielle de Leroux. À mon niveau d'alternant, j'ai participé à des sujets qui contribuent au fonctionnement du système d'information, mais les décisions importantes restent validées par le tuteur ou par l'entreprise. Cette distinction sera conservée dans les parties suivantes du rapport.

## 3. Implantation et organisation générale

Dans le cadre du rapport, je retiens principalement deux sites, car ils sont directement liés à l'activité de l'entreprise. Le premier est le site d'Orchies, où se situe l'usine principale de Leroux. Le second est le site de Vieille-Église, dans le Pas-de-Calais, où la chicorée est séchée et préparée avant son utilisation à Orchies.

Cette présentation reste volontairement limitée aux sites utiles pour comprendre le contexte de l'entreprise. D'autres informations juridiques ou administratives peuvent exister dans les sources publiques, mais elles ne sont pas nécessaires tant qu'elles ne servent pas directement la compréhension du rapport. L'objectif est de montrer dans quel environnement je travaille, pas de recopier toutes les informations disponibles sur l'entreprise.

Le site d'Orchies représente le point central de l'activité décrite dans ce rapport. C'est l'implantation historique et le lieu le plus directement associé à Leroux dans les sources publiques. Le site officiel mentionne l'adresse de l'usine à Orchies. Cette information étant publique, elle peut être utilisée, mais elle devra être citée proprement dans la bibliographie finale si elle apparaît dans la version définitive du rapport.

Le site de Vieille-Église est également important, car il intervient dans les premières étapes de transformation de la chicorée. Le site officiel présente ce lieu comme celui où se déroulent les premières étapes de transformation, notamment le séchage et la préparation des racines. Pour le rapport, je peux donc expliquer que l'activité industrielle de Leroux ne se limite pas à une vision administrative de l'entreprise. Elle repose sur des sites, des équipements et des étapes de production qui nécessitent une organisation concrète.

En revanche, plusieurs éléments d'organisation générale restent à compléter ou à vérifier. L'organigramme complet de l'entreprise n'est pas intégré dans ce brouillon. Les rattachements détaillés, les services précis avec lesquels j'interagis le plus souvent et les informations internes qui ne sont pas nécessaires à la compréhension doivent être validés avant diffusion. Si un schéma d'organisation est ajouté plus tard, il devra être simple, utile et anonymisé si nécessaire.

Cette implantation sur deux sites a aussi une conséquence sur la manière d'aborder l'informatique. Un système d'information dans une entreprise industrielle doit tenir compte des postes, des comptes, des outils collaboratifs, des équipements mobiles, des accès et du support aux utilisateurs. Les besoins peuvent varier selon les usages : certains sont liés à l'administration, d'autres à la production, à l'accueil ou au diagnostic d'incidents. Cette diversité explique pourquoi le service informatique doit rester polyvalent.

Pour moi, cette organisation a été un élément important de découverte. En arrivant dans l'entreprise, je n'ai pas seulement dû apprendre des outils techniques. J'ai aussi dû comprendre comment ces outils s'inscrivaient dans un cadre plus large : des utilisateurs, des priorités, des contraintes de sécurité, des besoins de terrain et des validations à obtenir avant certaines décisions.

## 4. Enjeux informatiques dans un contexte industriel

Dans une entreprise comme Leroux, l'informatique est liée au fonctionnement quotidien. Elle ne se limite pas à la maintenance de postes ou à l'installation de logiciels. Elle contribue à la continuité de service, à la disponibilité des outils, au support des utilisateurs et à la sécurité des comptes. Cette idée est importante pour comprendre mes missions : même lorsqu'un sujet paraît technique, il a toujours un lien avec un besoin utilisateur ou une contrainte d'entreprise.

La continuité de service est un premier enjeu. Les utilisateurs doivent pouvoir accéder à leurs outils, à leurs comptes, à leurs applications et aux équipements nécessaires à leur travail. Une difficulté d'authentification, un compte verrouillé, une tablette mal configurée ou un problème d'accès peut rapidement gêner une activité. À mon niveau, je ne garantis pas seul cette continuité, mais je participe à des actions qui permettent de la préserver au quotidien.

La disponibilité des outils est également essentielle. Dans le service informatique, les demandes peuvent concerner des postes de travail, des comptes, des tablettes, l'environnement Microsoft 365, Active Directory, Microsoft Entra, le Wi-Fi, le NPS ou des outils métiers internes utilisés par les services de l'entreprise. Certaines informations doivent rester générales dans le rapport, car détailler trop précisément l'environnement technique pourrait exposer des éléments internes inutiles.

La sécurité représente un autre enjeu important. Elle concerne les comptes, les accès, les équipements, les mots de passe, les connexions suspectes, les journaux et les données manipulées. Dans mes missions, cette dimension apparaît notamment avec la gestion des tablettes Android, les restrictions appliquées via Intune, la confidentialité des données visiteurs et les analyses liées à Active Directory ou Microsoft 365. Le rapport devra cependant rester prudent : il ne doit pas contenir de journaux bruts, de noms de comptes, d'adresses IP internes, de noms de postes ou de noms de serveurs.

Le support aux utilisateurs occupe aussi une place importante. Dans une petite équipe informatique, les échanges directs sont nécessaires pour comprendre les problèmes. Il ne suffit pas toujours de recevoir une demande : il faut parfois se déplacer, demander des précisions, observer le comportement d'un poste ou vérifier si la réponse apportée correspond réellement au besoin. Cette proximité avec les utilisateurs m'a permis de mieux comprendre que la technique doit rester au service de l'usage.

La confidentialité est un point transversal. Le rapport ne doit pas exposer d'informations sensibles. Les données personnelles, les journaux, les noms de comptes, les informations de sécurité et les éléments internes doivent être supprimés, résumés ou remplacés par `[REDACTED]` si nécessaire. Cette règle est d'autant plus importante que certaines missions concernent des visiteurs, des comptes utilisateurs ou des diagnostics de sécurité.

Enfin, l'informatique dans un contexte industriel demande de la réactivité, mais aussi de la prudence. Il faut corriger les problèmes lorsque c'est possible, tout en évitant de faire des modifications trop rapides sans comprendre leurs conséquences. Cette logique m'a marqué pendant l'alternance. Elle m'a appris à tester, vérifier, documenter et demander validation lorsque le sujet engage l'entreprise.

## 5. Le service informatique

Le service dans lequel je travaille est simplement appelé "service informatique". Il n'a pas de nom spécifique dans les informations validées pour le rapport. Cette précision évite d'inventer une appellation officielle qui n'existe pas.

Le service informatique est composé de deux personnes : le responsable informatique et moi, en tant qu'alternant administrateur systèmes et réseaux. Cette taille réduite donne une organisation assez souple. Les sujets sont répartis selon les besoins, les priorités, les projets en cours et les disponibilités. Le service doit pouvoir traiter des demandes quotidiennes tout en avançant sur des projets plus structurants.

Le responsable informatique est aussi mon maître d'apprentissage. Il cadre les missions, valide les choix importants, m'accompagne sur les points techniques et contrôle les décisions qui peuvent avoir un impact structurant pour l'entreprise. Pendant l'année, il y a eu un changement de tuteur : Loïc Humann était responsable informatique et tuteur au début de mon alternance, puis Thierry Devigne l'a remplacé dans ces deux rôles. Il n'y a donc toujours eu qu'un seul tuteur à la fois. Ce changement fait partie du contexte, mais l'élément principal à retenir est le rôle d'encadrement et de validation assuré par le tuteur.

Le service informatique intervient sur plusieurs types de sujets. Il contribue au support utilisateurs, à la gestion des comptes, aux postes de travail, aux tablettes, aux accès, aux outils Microsoft 365, à Active Directory, à Microsoft Entra, au Wi-Fi, au NPS et aux incidents quotidiens. Il accompagne aussi des outils métiers internes utilisés par les services de l'entreprise. Cette description reste générale pour respecter la confidentialité.

L'organisation du service repose beaucoup sur les échanges directs. Lorsqu'un utilisateur rencontre un problème, il est souvent nécessaire de comprendre le contexte avant d'intervenir. Une même demande peut avoir plusieurs causes possibles : un mot de passe expiré, un compte verrouillé, une connexion réseau instable, un poste qui conserve une ancienne information d'authentification ou un paramètre mal appliqué. Cette réalité m'a appris à ne pas conclure trop vite.

Le service doit aussi gérer des projets internes. Les missions développées dans la Partie II s'inscrivent dans cette logique : elles concernent les tablettes Android, le registre visiteurs numérique et les analyses de sécurité opérationnelle autour d'Active Directory et Microsoft 365. Elles ne remplacent pas le support quotidien, mais elles montrent comment le service informatique participe progressivement à la modernisation, à la sécurité et à la continuité du système d'information.

Dans une équipe de deux personnes, la polyvalence est indispensable. Le responsable informatique garde la responsabilité des décisions importantes, notamment lorsqu'elles ont un impact technique structurant ou financier. De mon côté, je peux prendre en charge une partie opérationnelle importante : recherches, tests, configuration, ajustements, documentation et échanges avec les utilisateurs. Cette organisation me donne de l'autonomie, tout en maintenant un cadre de validation.

Le service informatique est donc à la fois un service de proximité et un service technique. Il doit répondre aux besoins immédiats, mais aussi préparer des évolutions plus durables. Cette double dimension explique l'intérêt des missions que je développe ensuite : elles partent de besoins concrets et demandent à la fois de la méthode, de la technique et de la prudence.

## 6. Mon intégration et mon rôle dans le service

Mon rôle dans le service est celui d'un alternant administrateur systèmes et réseaux. Je suis en première année CI1, donc mon objectif n'est pas de me présenter comme un expert ou comme le responsable du système d'information. Mon rôle est plutôt de participer aux missions, de monter en compétence, de comprendre les besoins et de contribuer à des actions concrètes sous validation du tuteur ou de l'entreprise.

Au quotidien, j'ai une autonomie importante sur la partie opérationnelle. Généralement, mon tuteur définit le besoin, la mission ou le cadre de travail. Ensuite, je prends en charge l'analyse, les recherches, les tests, la configuration, les ajustements et parfois la documentation. Cette autonomie m'oblige à être rigoureux, car je dois comprendre ce que je fais avant de proposer ou d'appliquer une solution.

Cette manière de travailler m'a permis de progresser dans plusieurs domaines. J'ai appris à chercher de l'information, à comparer des possibilités, à tester une configuration avant de la considérer comme utilisable et à revenir vers le tuteur lorsque le sujet demandait une validation. Les décisions finales importantes, notamment les choix structurants ou financiers, ne relèvent pas de moi. Cette limite est normale et elle doit rester claire dans le rapport.

Mon intégration passe aussi par les échanges avec les utilisateurs. Je peux être amené à me déplacer auprès d'eux pour comprendre une demande, récupérer des détails, tester une solution ou vérifier qu'un problème est bien corrigé. Ces échanges sont importants, car ils montrent que le support informatique ne consiste pas seulement à appliquer une procédure. Il faut aussi écouter, reformuler le besoin et adapter la réponse au contexte réel.

Dans les missions principales, mon rôle suit cette même logique. J'ai travaillé sur des sujets liés à la gestion de tablettes Android avec Intune, au registre visiteurs numérique et à des diagnostics autour de comptes, de connexions, de journaux et de postes utilisateurs. Ces exemples servent ici à expliquer mon positionnement ; les actions, les difficultés et les résultats seront détaillés dans la Partie II.

Cette première année m'a aussi appris l'importance de la documentation et de la traçabilité. Dans un service informatique, une configuration ou une correction doit pouvoir être comprise plus tard. Même lorsque la documentation reste à compléter, l'objectif est de garder une trace des choix, des tests et des limites. Cela rejoint la démarche attendue dans le rapport CI1 : ne pas seulement décrire une action, mais montrer comment elle a été comprise, réalisée, vérifiée et replacée dans son contexte.

Enfin, mon rôle d'alternant m'oblige à prendre du recul. Certaines situations demandent de l'autonomie, d'autres demandent de savoir s'arrêter et demander une validation. Cette différence est importante dans un environnement informatique, car une action mal comprise peut avoir des conséquences sur des utilisateurs, des équipements ou des données. C'est pour cette raison que je présente mon expérience comme une montée en compétence progressive, et non comme une prise de responsabilité complète sur le système d'information.

## 7. Transition vers les missions réalisées

Cette présentation de Leroux et du service informatique permet de comprendre le cadre dans lequel mes missions ont été réalisées. L'entreprise évolue dans un contexte industriel agroalimentaire, avec une activité centrée sur la transformation de la chicorée et une organisation qui demande des outils fiables, disponibles et adaptés aux usages des utilisateurs.

La Partie II présentera les missions principales séparément, avec leurs objectifs, leurs contraintes, les actions menées, les difficultés rencontrées, les solutions apportées et les résultats réellement validés ou encore à vérifier. Elles répondront au même fil conducteur : comprendre comment une première année d'alternance en administration systèmes et réseaux permet de contribuer, à son niveau, à la continuité, à la sécurité et à la modernisation du système d'information d'une entreprise industrielle.


---

# Partie II — Missions réalisées

## 1. Microsoft Intune / Android Enterprise

### 1.1 Contexte et besoin initial

La première mission principale que je présente concerne la gestion des tablettes Android professionnelles avec Microsoft Intune et Android Enterprise. Elle s'inscrit dans le fonctionnement du service informatique, car ces équipements doivent rester adaptés aux usages de l'entreprise tout en étant suffisamment cadrés.

Chez Leroux, les tablettes répondent à deux besoins distincts. Le premier concerne une tablette destinée au registre visiteurs à l'accueil. Le second concerne des tablettes utilisées en production. Les usages ne sont pas les mêmes, mais l'objectif reste proche : disposer d'appareils configurés de manière cohérente, avec les applications utiles, les restrictions nécessaires et un niveau de sécurité adapté à un contexte professionnel.

La mission a représenté environ deux mois de travail. Cette durée comprend la prise en main de Microsoft Intune, la configuration de la tablette destinée au registre visiteurs et la configuration des tablettes de production. La période exacte n'est pas indispensable pour comprendre la mission et pourra être confirmée dans la version finale.

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

Les appareils concernés sont trois tablettes Samsung Galaxy Tab S10 FE+ destinées à la production, ainsi qu'une tablette distincte prévue pour le registre visiteurs à l'accueil. Cette distinction est importante, car les usages ne sont pas les mêmes même si la logique de gestion centralisée reste commune.

Pour les tablettes de production, l'enrôlement s'appuyait sur un token dédié et sur un groupe associé à cet usage. Comme ces noms correspondent à une configuration interne, je ne les détaille pas. Dans le rapport, il est suffisant de parler d'un token d'enrôlement dédié et d'un groupe de tablettes de production.

Les applications prévues ou déployées sur les tablettes comprenaient des outils bureautiques et collaboratifs comme Word, Excel, PowerPoint, OneNote, Teams et Outlook. D'autres applications utiles étaient également disponibles, comme Collabora et Adobe Reader. Ces applications correspondent à des besoins d'usage professionnel : consultation, saisie, communication ou ouverture de documents.

Des liens web utiles étaient aussi prévus sur les tablettes, notamment vers la GMAO, GLPI et d'autres outils métiers internes. GLPI est ici seulement cité comme lien ou outil disponible sur tablette. Il ne s'agit pas d'une mission principale du rapport, conformément aux règles du projet.

Les moyens humains mobilisés reposaient principalement sur le service informatique. Mon tuteur définissait le cadre et validait les décisions importantes. De mon côté, j'ai pris en charge la partie opérationnelle : recherches, configuration, tests, enrôlement, ajustements et échanges lorsque cela était nécessaire. Les choix techniques structurants et les décisions financières restaient validés par le tuteur ou par l'entreprise.

Sur le plan financier, aucune licence payante supplémentaire spécifique n'a été identifiée dans le cadre de cette mission ; le travail s'est appuyé sur les outils déjà disponibles dans l'environnement Microsoft de l'entreprise. Je me limite donc aux moyens matériels, techniques, humains et documentaires réellement connus.

La documentation a aussi été une ressource importante, même si l'existence d'une procédure formelle reste à confirmer. Pour prendre en main Intune, je me suis appuyé sur la documentation officielle Microsoft Learn, sur les recommandations Microsoft associées à Intune et à Android Enterprise, ainsi que sur les tests réalisés directement dans l'environnement.

### 1.4 Contraintes de la mission

La première contrainte était de trouver un équilibre entre sécurité et usage. Une tablette professionnelle doit être cadrée, mais elle doit aussi rester simple à utiliser pour des besoins concrets. Une restriction trop large ou mal adaptée peut gêner le travail au lieu de le sécuriser.

Il fallait aussi tenir compte des deux usages concernés. La tablette d'accueil pour le registre visiteurs et les tablettes de production ne répondent pas exactement aux mêmes contraintes, même si elles reposent sur le même cadre de gestion. La configuration devait donc rester cohérente sans devenir identique dans tous les cas.

Une autre contrainte concernait la méthode. Les réglages devaient être testés avant usage, car une restriction mal appliquée ou trop stricte pouvait poser problème sur le terrain. Le périmètre exact des résultats devait donc rester formulé avec prudence, d'autant plus qu'aucun indicateur mesuré n'est disponible à ce stade.

Enfin, la mission touche à des paramètres internes de configuration. Je reste donc volontairement général sur certains éléments, comme les noms de groupes, de tokens ou le détail complet des règles appliquées, afin de respecter la confidentialité de l'environnement.

### 1.5 Démarche suivie

Dans un premier temps, j'ai cherché à comprendre le besoin. Il ne s'agissait pas seulement de savoir quelles tablettes devaient être configurées, mais aussi de comprendre leur usage. La tablette d'accueil était liée au registre visiteurs, alors que les tablettes de production répondaient à un autre contexte d'utilisation. Cette distinction évitait d'appliquer une configuration unique sans tenir compte du terrain.

J'ai ensuite pris en main Microsoft Intune et Android Enterprise. Cette étape a demandé du temps, car l'outil comporte plusieurs notions qui se croisent : enrôlement de l'appareil, profils de configuration, restrictions, groupes, applications et affectations. Au début, le risque était de confondre ces éléments ou de ne pas comprendre exactement où devait être appliquée une règle.

Une fois le principe général compris, j'ai travaillé sur le mode Android Enterprise fully managed. L'enrôlement permettait de rattacher la tablette à la gestion Intune, puis de lui appliquer les paramètres associés au groupe prévu pour son usage.

La configuration a ensuite porté sur les restrictions d'usage et sur la sécurité d'accès. J'ai préparé des paramètres destinés à limiter certaines modifications système ou réseau, à encadrer l'ajout de comptes et à définir une règle de mot de passe compatible avec l'usage prévu. J'ai aussi prévu une plage de mise à jour hors période d'utilisation principale pour limiter l'impact sur le travail. Le détail complet de ces réglages n'est pas repris ici, car il relève de la configuration interne et doit rester présenté avec prudence.

J'ai aussi travaillé sur les applications nécessaires. L'objectif était que les tablettes disposent des outils utiles sans laisser l'utilisateur chercher ou installer lui-même les applications. Les applications bureautiques, collaboratives et de consultation de documents devaient être disponibles selon les besoins. Les liens web utiles devaient également faciliter l'accès aux outils métiers ou de support prévus.

Après la configuration, les tests ont été essentiels. Il fallait vérifier que la tablette s'enrôlait correctement, que les applications attendues apparaissaient et que les restrictions étaient bien prises en compte. Par exemple, un test non sensible consistait à contrôler qu'une tablette enrôlée affichait les applications prévues tout en restant utilisable malgré les restrictions appliquées. Les résultats précis de ces tests restent à détailler si des preuves ou validations supplémentaires sont disponibles.

Les ajustements ont fait partie de la démarche. Une configuration Intune n'est pas forcément parfaite dès le premier essai. Certains paramètres peuvent être trop stricts, mal compris ou ne pas produire immédiatement l'effet attendu. J'ai donc avancé par essais, vérifications et corrections, en gardant le tuteur comme point de validation pour les choix importants.

Cette démarche m'a montré qu'un outil d'administration centralisée ne supprime pas le besoin de méthode. Intune permet de pousser des règles, mais il faut quand même comprendre le besoin, vérifier les effets réels et garder une trace de ce qui est fait.

### 1.6 Difficultés rencontrées

La première difficulté a été la prise en main de Microsoft Intune. L'outil est complet, mais il peut être difficile à aborder au début. Plusieurs notions se ressemblent ou s'enchaînent : enrôlement, groupe, profil, restriction, application, affectation. Comprendre le rôle de chaque élément a demandé du temps.

Une autre difficulté a été de distinguer ce qui se configure dans le portail et ce qui est réellement appliqué sur la tablette. Le fait de créer une règle ne suffit pas. Il faut que l'appareil soit bien enrôlé, qu'il appartienne au bon groupe, qu'il synchronise les paramètres et que la restriction soit compatible avec le mode de gestion choisi.

La gestion des restrictions a aussi demandé de la prudence. Certaines règles paraissent logiques sur le papier, mais elles peuvent devenir gênantes si elles ne correspondent pas à l'usage réel de la tablette. Il fallait donc vérifier que le niveau de sécurité restait compatible avec le besoin.

La différence entre la tablette d'accueil et les tablettes de production a également nécessité de réfléchir aux usages. Une tablette destinée au registre visiteurs n'a pas forcément les mêmes besoins qu'une tablette utilisée en production. Même si la mission porte globalement sur Intune et Android Enterprise, il ne fallait pas oublier que les équipements correspondent à des situations différentes.

### 1.7 Résultats obtenus

Le premier résultat est la mise en place d'une configuration Intune pour les tablettes Android professionnelles concernées. Les tablettes ont été configurées avec Android Enterprise en mode fully managed, ce qui donne un cadre de gestion plus homogène qu'une configuration réalisée appareil par appareil.

Les tablettes de production sont utilisées en production. Cette information peut être présentée, car elle est validée dans les fichiers de contexte. La mission a également couvert la tablette destinée au registre visiteurs, tout en conservant la distinction entre cet usage d'accueil et l'usage en production.

La configuration contribue aussi à mieux cadrer l'usage professionnel des appareils. Les restrictions, les applications utiles et les liens prévus permettent de préparer un environnement plus cohérent pour les utilisateurs, sans avoir à présenter cela comme un résultat mesuré.

Pour le service informatique, l'apport principal est donc un cadre de gestion plus centralisé du parc mobile. Il permet de mieux préparer, suivre et ajuster les tablettes selon leur usage, tout en laissant la place à des vérifications et à des ajustements ultérieurs.

Pour moi, le résultat est également une montée en compétence sur un outil d'administration utilisé dans beaucoup d'environnements professionnels.

### 1.8 Limites et points restant à suivre

Plusieurs limites doivent être indiquées clairement pour éviter de survaloriser la mission. Le nombre exact de tablettes, la période calendaire précise et le périmètre complet du déploiement devront être confirmés dans la version finale.

Les résultats mesurables ne sont pas disponibles à ce stade. Je ne peux donc pas indiquer de gain de temps, de baisse d'incidents, de taux de conformité ou de pourcentage de déploiement. Les résultats sont donc présentés de manière qualitative.

La documentation reste également à confirmer. Si une procédure interne ou une note de configuration a été produite, elle pourra être mentionnée de manière générale, sans exposer de détails sensibles. Sinon, il faudra indiquer que la formalisation documentaire reste un axe d'amélioration.

Un autre point à suivre concerne l'usage réel des tablettes dans le temps. Une configuration peut fonctionner au moment des tests, mais elle doit encore être observée dans la durée pour vérifier qu'elle reste adaptée aux usages.

Les captures prévues en annexe permettent d'illustrer la gestion centralisée des tablettes dans Intune, notamment pour les équipements destinés à la production et les éléments liés à la configuration.

[Figure à insérer : fig01_intune_appareils_production_anonymise.png — Vue des tablettes de production dans Intune]

[Figure à insérer : fig02_intune_profil_configuration_anonymise_production.png — Profil de configuration Intune appliqué aux tablettes de production]

[Figure à insérer : fig02_intune_profil_configuration_anonymise_visiteur.png — Profil de configuration Intune lié à la tablette visiteurs]

La confidentialité doit aussi rester surveillée. Les noms exacts des tokens, groupes, appareils ou paramètres internes ne sont pas indispensables à la compréhension du rapport. Dans la version finale, il faudra conserver une formulation générale ou remplacer les éléments sensibles par `[REDACTED]` si l'entreprise le demande.

Enfin, cette mission reste dépendante de validations internes. Même si j'ai réalisé une grande partie du travail opérationnel, les décisions finales sont validées par le tuteur ou par l'entreprise.

### 1.9 Recul personnel sur la mission

Cette mission m'a permis de mieux comprendre la gestion des terminaux mobiles en entreprise. Avant de travailler sur Intune, je voyais surtout la tablette comme un appareil à configurer. Avec cette mission, j'ai compris qu'il fallait raisonner en parc, en usages, en restrictions, en applications et en suivi.

J'ai aussi appris que la sécurité ne consiste pas seulement à bloquer le plus de fonctions possible. Une restriction doit avoir un sens par rapport au besoin. Si elle protège l'appareil mais empêche l'utilisateur de travailler correctement, elle doit être revue. Cette idée m'a aidé à mieux comprendre l'équilibre entre sécurité et simplicité d'utilisation.

La prise en main d'Intune m'a demandé de la patience. Au début, il n'était pas évident de comprendre pourquoi une règle ne s'appliquait pas immédiatement ou comment les groupes, profils et applications interagissaient. En avançant étape par étape, j'ai appris à vérifier plutôt qu'à supposer. Cette méthode me sert aussi dans d'autres missions.

Cette mission m'a également montré l'importance des tests. Dans un portail d'administration, une configuration peut sembler correcte, mais seul le test sur l'appareil permet de vérifier le résultat réel. J'ai donc compris qu'il fallait toujours comparer ce qui est attendu avec ce qui se passe réellement sur la tablette.

Sur le plan professionnel, cette mission m'a donné plus d'autonomie. J'ai pu prendre en charge la recherche, la configuration, les essais et les ajustements. En même temps, j'ai gardé en tête que certaines décisions devaient être validées par le tuteur. Cette limite m'a appris à travailler de façon plus responsable : avancer seul quand c'est possible, mais demander validation quand le sujet peut avoir un impact plus large.

Au-delà de l'outil lui-même, cette mission m'a surtout appris qu'une configuration utile en entreprise doit rester cohérente, testée et adaptée à l'usage réel. C'est ce point qui m'a le plus fait progresser.

## 2. Registre visiteurs Power Apps / SharePoint / Power Automate

### 2.1 Contexte et besoin initial

J'ai aussi travaillé sur la création d'un registre visiteurs numérique avec Power Apps, SharePoint et Power Automate. Cette mission répond à un besoin concret de l'accueil : remplacer à terme le registre papier par une solution plus simple à utiliser et plus facile à suivre côté informatique.

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

La tablette d'accueil fait partie des moyens matériels mobilisés. L'historique d'exécution Power Automate a aussi été un moyen de travail important, car il m'a permis de vérifier les valeurs reçues et de comprendre les erreurs pendant les tests.

Les moyens humains reposaient principalement sur le service informatique. Mon tuteur de l'époque a exprimé le besoin initial et validé les choix importants. De mon côté, j'ai pris en charge la partie opérationnelle : compréhension du besoin, création de l'application, configuration de la liste SharePoint, préparation du flux, tests et corrections. Le service maintenance intervient aussi indirectement, car la mise en service dépend du support physique de la tablette.

Pour les moyens financiers, aucune licence payante supplémentaire spécifique n'a été identifiée ; la mission s'est appuyée sur les outils déjà disponibles dans l'environnement Microsoft de l'entreprise. Je ne détaille donc ni coût matériel ni arbitrage financier non validé.

### 2.4 Contraintes de la mission

La première contrainte était de garder une utilisation simple sur tablette, car l'outil devait rester rapide à comprendre à l'accueil. Il fallait aussi protéger la confidentialité des données visiteurs et éviter d'exposer des informations personnelles dans le rapport.

La fiabilité de l'enregistrement constituait une autre contrainte importante, en particulier pour la signature. Il ne suffisait pas que l'application fonctionne en apparence : il fallait vérifier que les données et la signature arrivaient correctement jusqu'à SharePoint.

Enfin, la mise en service restait dépendante d'un point matériel extérieur à la partie applicative : l'installation d'un support physique pour sécuriser la tablette à l'accueil.

### 2.5 Démarche suivie

Dans un premier temps, j'ai cherché à comprendre le besoin métier. Le but n'était pas seulement de remplacer un cahier par un écran. Il fallait identifier les informations nécessaires à l'accueil, réfléchir à la façon de les saisir sur tablette et prévoir le stockage dans un outil accessible au service informatique.

Le travail s'est organisé en plusieurs phases assez simples : cadrage du besoin, préparation de la liste SharePoint, création de l'application Power Apps, mise en place du flux Power Automate, puis tests et ajustements.

La première étape technique a consisté à préparer la structure SharePoint. La solution s'appuie sur une liste principale pour les enregistrements visiteurs et sur une liste complémentaire dédiée aux sociétés, ce qui permet de structurer davantage les informations saisies dans l'application. La liste principale contient les champs nécessaires au registre : nom, prénom, société, personne visitée, heure d'arrivée, heure de départ et date de passage. La date est renseignée automatiquement et les heures sont saisies via des listes déroulantes dans Power Apps, ce qui limite les erreurs de format.

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
 
Pour l'entreprise, la plus-value reste à présenter avec prudence. À ce stade, la solution apporte surtout une base exploitable pour centraliser les enregistrements visiteurs et préparer un suivi plus structuré, sans que ces gains aient encore été mesurés en conditions réelles.

La solution peut donc être considérée comme validée sur les plans applicatif et technique, mais pas encore comme déployée en usage réel à l'accueil. Je ne peux pas annoncer de gain de temps mesuré, de nombre de visiteurs testés ou d'amélioration prouvée de la traçabilité. Je peux seulement affirmer que la solution prépare une transition vers un registre numérique et que les fonctions attendues côté application, stockage et signature sont opérationnelles.

Les captures prévues en annexe présentent le formulaire Power Apps, le flux Power Automate associé, ainsi que les listes SharePoint utilisées pour les visiteurs et les sociétés. Les données visibles dans ces captures correspondent à des valeurs de test, la solution n'étant pas encore utilisée en production à l'accueil.

[Figure à insérer : fig03_powerapps_formulaire_visiteur_test.png — Formulaire Power Apps du registre visiteurs]

[Figure à insérer : fig04_powerautomate_flow_registre_visiteurs_anonymise.png — Flux Power Automate associé au registre visiteurs]

[Figure à insérer : fig05_sharepoint_liste_visiteurs_test.png — Liste SharePoint des visiteurs avec données de test]

[Figure à insérer : fig06_sharepoint_liste_societes_anonymise.png — Liste SharePoint des sociétés avec données de test]

### 2.8 Limites et points restant à suivre

La limite principale est l'absence de mise en service réelle à l'accueil. La solution est validée techniquement, mais l'utilisation quotidienne reste suspendue à l'installation par la maintenance du support physique destiné à sécuriser la tablette. Le registre papier ne doit donc pas être présenté comme remplacé.

Une autre limite concerne les tests en conditions réelles. Les tests techniques ont permis de valider l'application, le flux et la signature. En revanche, l'utilisation par l'accueil sur une période réelle pourra faire apparaître des ajustements à prévoir : ergonomie, compréhension des champs, rythme de saisie ou cas particuliers non rencontrés pendant les tests.

La confidentialité reste un point à surveiller. Un registre visiteurs contient des données personnelles. Il faut donc éviter les captures non anonymisées, les exports contenant de vrais noms ou les exemples basés sur des visiteurs réels. Si des illustrations sont ajoutées, elles devront s'appuyer uniquement sur des données de test ou sur des données anonymisées.

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

Cette mission reste à l'échelle d'une première année d'alternance. Elle ne correspond pas à une transformation complète de l'accueil ni à un déploiement finalisé. C'est une contribution concrète à un besoin interne, avec une solution fonctionnelle, des limites identifiées et une mise en service encore dépendante d'un élément matériel. Elle m'a surtout appris à partir d'un besoin concret, à construire une solution, puis à vérifier qu'elle fonctionne vraiment.

## 3. Sécurité opérationnelle AD / Microsoft 365

### 3.1 Contexte et besoin initial

J'ai également participé à une mission continue de sécurité opérationnelle autour d'Active Directory, de Microsoft 365 et de Microsoft Entra. Contrairement aux deux premières missions, il ne s'agit pas d'un sujet avec un début, une phase de réalisation clairement isolée, puis une fin. Cette activité s'est déroulée de manière continue sur l'année, au fil des incidents, des demandes utilisateurs et des vérifications quotidiennes liées aux comptes, aux connexions et aux postes de travail.

Dans le fonctionnement courant du service, certains problèmes peuvent paraître simples au premier abord. Un utilisateur signale par exemple qu'il ne peut plus se connecter, qu'un mot de passe semble ne plus fonctionner, que son compte se verrouille sans raison apparente ou qu'une connexion lui paraît inhabituelle. Pourtant, ce type de symptôme peut avoir plusieurs causes. Il peut s'agir d'une mauvaise saisie, d'un ancien mot de passe encore enregistré sur un poste ou un équipement, d'un problème de synchronisation, d'une authentification réseau liée au Wi-Fi, ou d'un comportement qui demande au contraire une vérification plus prudente.

Dans ce contexte, mon rôle n'était pas de mener un audit complet de sécurité ni de prendre seul des décisions structurantes. J'ai surtout participé à une mission continue de diagnostic. Elle m'a amené à analyser des incidents liés aux verrouillages de comptes, aux échecs d'authentification, aux connexions suspectes, aux vérifications Microsoft 365 et Microsoft Entra, ainsi qu'aux journaux Windows. Cette mission s'inscrit directement dans le fil conducteur du rapport, car elle touche à la fois à la continuité de service, à la sécurité et à la méthode de travail.

Elle répond aussi à un besoin très concret pour l'entreprise. Lorsqu'un compte reste bloqué ou qu'une authentification échoue, le problème n'est pas seulement technique. Il peut empêcher un utilisateur de travailler normalement, perturber un accès à un service ou faire perdre du temps au support. Il faut donc intervenir assez rapidement, mais sans conclure trop vite. C'est ce mélange de réactivité et de prudence qui revient le plus dans cette mission.

### 3.2 Objectifs de la mission

Le premier objectif était de comprendre l'origine probable d'un incident avant de proposer une correction. Dans cette mission, un symptôme ne suffit pas. Le fait qu'un compte soit verrouillé ne dit pas, à lui seul, pourquoi il l'est. Il fallait donc chercher des éléments de contexte, vérifier les journaux utiles et comparer plusieurs sources d'information.

Le deuxième objectif était de contribuer à limiter l'impact des incidents sur les utilisateurs. Lorsqu'un problème d'authentification revient plusieurs fois, il ne suffit pas de débloquer le compte ou de réinitialiser un mot de passe. Il faut aussi essayer de comprendre si le problème vient du poste, d'un mot de passe enregistré, d'un équipement, d'un accès Wi-Fi ou d'un autre comportement technique encore actif.

Le troisième objectif concernait la méthode. Cette mission m'a appris à avancer par hypothèses et recoupement d'informations. Je devais distinguer ce qui relevait du symptôme observé, de la piste probable, puis éventuellement de la cause confirmée. Cette distinction est importante dans un rapport comme dans le travail quotidien, car elle évite d'écrire ou de dire qu'un problème est résolu définitivement alors que les vérifications restent incomplètes.

Enfin, un autre objectif était de mieux comprendre les liens entre Active Directory, Microsoft 365, les postes utilisateurs et les journaux de sécurité. Même lorsqu'un incident commence par une plainte très simple, comme "je n'arrive plus à me connecter", il peut demander de regarder plusieurs couches du système d'information avant de formuler une explication crédible.

### 3.3 Moyens et outils utilisés

Cette mission s'appuyait d'abord sur les outils d'administration Active Directory, utilisés pour vérifier l'état d'un compte, observer un verrouillage et contrôler les premiers éléments liés à l'authentification. L'objectif n'était pas de détailler une console précise, mais d'utiliser les outils disponibles pour confirmer que le compte concerné correspondait bien au problème signalé.

Selon les cas, les vérifications pouvaient aussi concerner Microsoft 365, Microsoft Entra et les outils associés à la gestion des identités et des accès. Il ne s'agissait pas d'analyser tout l'environnement Microsoft, mais de voir si certaines connexions ou certains comportements observés côté utilisateur apparaissaient aussi dans ces contrôles.

Les journaux d'événements Windows ont ensuite joué un rôle central. Je ne les présente pas comme une liste technique à apprendre, mais comme des sources d'information qui permettent d'orienter le diagnostic. Certains événements de sécurité pouvaient, par exemple, confirmer un verrouillage de compte ou un échec d'authentification. Dans certains cas, un code d'état aidait aussi à comprendre si le compte était déjà verrouillé plutôt qu'en simple erreur de saisie. Ces éléments restaient cependant à recouper avec le contexte utilisateur et les autres vérifications.

Lorsque le problème semblait lié à une authentification réseau, notamment sur le Wi-Fi, les journaux associés à cette partie pouvaient compléter l'analyse. Le poste utilisateur concerné constituait lui aussi un moyen important, car il fallait parfois vérifier si une session restait ouverte, si des informations d'identification anciennes étaient encore enregistrées, ou si un logiciel répétait automatiquement une tentative de connexion.

Cette mission repose surtout sur des moyens techniques, humains et documentaires. Elle ne correspond pas à un achat ou à un projet budgétaire identifié, mais à une activité continue de diagnostic dans le fonctionnement du service informatique. Aucune licence payante supplémentaire spécifique n'a été identifiée ; les analyses se sont appuyées sur les outils déjà disponibles dans l'environnement de l'entreprise. Les échanges avec l'utilisateur, la validation du tuteur, l'expérience du service et la documentation disponible comptaient donc autant que la lecture des journaux eux-mêmes.

### 3.4 Contraintes de la mission

La première contrainte était la confidentialité. Cette mission porte sur des comptes, des authentifications, des journaux et parfois des comportements inhabituels. Je ne peux donc pas intégrer dans le rapport de noms de comptes, de noms de postes, d'adresses IP internes, de noms de serveurs ou de journaux bruts. Le texte doit rester anonymisé et centré sur la méthode.

La deuxième contrainte venait de la complexité d'interprétation. Un même symptôme peut avoir plusieurs causes possibles, et plusieurs journaux peuvent montrer des éléments différents sans donner immédiatement une réponse unique. Il fallait donc rester prudent, car un verrouillage de compte ou un échec de connexion ne suffit pas à désigner un responsable, ni à confirmer une cause sans recoupement.

Une autre difficulté est liée au caractère parfois intermittent des incidents. Certains problèmes ne se reproduisent pas au moment où l'on commence l'analyse. Dans ce cas, il faut s'appuyer sur les traces disponibles, sur le contexte donné par l'utilisateur et sur des vérifications indirectes. Cela demande plus de prudence qu'un incident facilement reproductible.

La réactivité constituait aussi une contrainte importante. Lorsqu'un utilisateur ne peut plus se connecter, il faut essayer d'avancer rapidement. Mais cette rapidité ne doit pas conduire à faire une modification trop hâtive. Une action mal comprise peut masquer la cause réelle ou déplacer le problème sans le résoudre.

Enfin, mon rôle d'alternant imposait une limite claire. Je pouvais participer à l'analyse, proposer des pistes et appliquer certaines vérifications, mais les actions importantes restaient validées par le tuteur ou par l'entreprise. Cette contrainte n'était pas un frein. Au contraire, elle m'a appris à structurer mes constats avant de proposer une conclusion.

### 3.5 Démarche suivie

La démarche suivie dans cette mission restait assez stable, même si chaque incident gardait ses particularités. Je partais d'abord du symptôme signalé, puis je cherchais le contexte utile : poste concerné, changement récent de mot de passe, présence d'un autre appareil, connexion automatique ou incident réseau possible. Cette première étape évitait de lire les journaux sans point de départ.

Je vérifiais ensuite les éléments les plus immédiats dans les outils d'administration Active Directory, sur le poste utilisateur et, si nécessaire, dans Microsoft 365, Microsoft Entra ou dans les outils liés aux identités et aux accès. La lecture des journaux servait alors à confirmer ou à écarter les premières hypothèses. L'idée n'était pas de trouver un événement isolé, mais de recouper plusieurs indices avant de proposer une explication probable.

Un exemple-type anonymisé illustre bien cette méthode : après le déblocage d'un compte, celui-ci pouvait se reverrouiller peu de temps après. Dans ce cas, je ne partais pas du principe que la cause était déjà connue. Je vérifiais plutôt plusieurs pistes possibles, comme un ancien mot de passe encore enregistré, un logiciel qui retentait une connexion, un autre équipement ou une authentification réseau répétée. La correction n'était proposée qu'après ce recoupement, puis suivie pour voir si le symptôme réapparaissait ou non.

Lorsque les vérifications faisaient ressortir une cause probable suffisamment solide, une action pouvait être proposée ou appliquée sous validation. Je ne parlais de cause confirmée que lorsque plusieurs traces convergeaient et que le symptôme ne réapparaissait plus après correction. Enfin, lorsque c'était utile, une trace était conservée dans le suivi interne afin de garder une méthode exploitable par le service, sans reproduire dans le rapport des éléments sensibles ou des journaux bruts.

### 3.6 Difficultés rencontrées

La première difficulté a été le volume d'information à trier. Les journaux Windows donnent beaucoup d'éléments, mais tous ne sont pas utiles au même moment. Il fallait donc apprendre à repérer les traces vraiment utiles au diagnostic.

La deuxième difficulté venait de la corrélation entre plusieurs sources. Un même incident pouvait demander de regarder à la fois les outils Active Directory, le poste utilisateur, Microsoft 365 ou les journaux liés à l'authentification réseau. Le plus difficile n'était pas seulement de trouver une information, mais de comprendre comment plusieurs indices se répondaient.

J'ai aussi dû faire attention à l'interprétation. Un symptôme peut sembler évident alors qu'il reste ambigu. Les échanges avec l'utilisateur ajoutaient parfois une autre limite, car les informations remontées sont souvent partielles. Il fallait donc reformuler, compléter le contexte et éviter de conclure trop vite.

Enfin, cette mission imposait une vraie prudence d'analyse. Dans un sujet de sécurité opérationnelle, une hypothèse bien argumentée vaut mieux qu'une conclusion rapide mais fragile. C'est probablement la difficulté qui m'a le plus fait progresser.

### 3.7 Résultats obtenus

Le premier résultat de cette mission est une participation régulière à des diagnostics liés aux comptes, aux authentifications et aux connexions. Je ne peux pas donner de volume chiffré, mais cette activité faisait bien partie du fonctionnement courant du service informatique.

Cette mission m'a surtout permis de structurer davantage ma démarche de diagnostic. J'ai appris à mieux distinguer le symptôme initial, les hypothèses possibles, puis les éléments réellement confirmés après vérification. Cela m'a aussi aidé à mieux comprendre les verrouillages de comptes et les échecs d'authentification dans un contexte plus large que le simple message vu par l'utilisateur.

Le recours à plusieurs sources d'information a également contribué à rendre mes analyses plus méthodiques. Au lieu de m'appuyer sur une seule trace, j'ai davantage croisé les journaux, le contexte utilisateur et les vérifications techniques. Dans certains cas, cette démarche a aidé à mieux cibler une piste, par exemple un ancien mot de passe encore mémorisé ou une authentification répétée, sans que cela constitue un indicateur chiffré de performance.

Pour le service informatique, l'apport principal de cette mission reste donc lié à la méthode de traitement. Elle a permis de mieux structurer l'ordre des vérifications sur certains incidents quotidiens, sans qu'il s'agisse pour autant d'un bilan mesuré de performance.

### 3.8 Limites et points restant à suivre

La première limite est qu'un incident de sécurité opérationnelle n'offre pas toujours une preuve unique. Il arrive que plusieurs hypothèses restent crédibles, même après plusieurs vérifications. Dans ce cas, il faut accepter de rester sur une cause probable plutôt que d'affirmer une certitude non démontrée.

Les journaux peuvent aussi être incomplets ou difficiles à interpréter selon le moment où l'on intervient. Si un incident a déjà cessé, certaines traces peuvent être moins lisibles ou demander davantage de recoupement. Cela limite naturellement le niveau de détail que je peux présenter dans le rapport.

Une autre limite concerne la confidentialité. Comme cette mission touche à des éléments sensibles, je dois volontairement rester général sur les exemples. Le rapport ne contient donc ni cas complet détaillé, ni log brut, ni élément nominatif. Cette retenue est nécessaire, mais elle empêche aussi de montrer tout le niveau de détail réel du diagnostic.

Je ne dispose pas non plus d'indicateurs chiffrés validés sur cette activité. Je ne peux donc pas annoncer un nombre d'incidents traités, un temps moyen de résolution, ni une baisse mesurée des problèmes d'authentification. Les résultats doivent rester qualitatifs.

Enfin, cette mission doit rester présentée avec un niveau de détail compatible avec la confidentialité. Pour la partie sécurité, un schéma méthodologique anonymisé est préférable à une capture de logs ou de comptes réels.

### 3.9 Recul personnel sur la mission

Cette mission m'a beaucoup appris sur la manière d'aborder un problème de sécurité opérationnelle. Au départ, j'aurais pu voir un verrouillage de compte ou un échec de connexion comme un incident assez simple. En pratique, j'ai découvert qu'il fallait presque toujours prendre un peu de recul, replacer le symptôme dans son contexte et accepter que la première explication ne soit pas forcément la bonne.

J'ai surtout progressé sur la méthode. Cette mission m'a appris à ne pas m'arrêter au premier indice, à comparer plusieurs sources et à distinguer clairement trois niveaux : ce que j'observe, ce que j'en déduis comme hypothèse, puis ce que je peux réellement considérer comme confirmé. Cette distinction me paraît aujourd'hui essentielle, non seulement pour la sécurité, mais pour le diagnostic informatique en général.

Elle m'a aussi montré que la sécurité opérationnelle n'est pas séparée du support utilisateur. Derrière un compte verrouillé ou une authentification refusée, il y a d'abord une personne qui ne peut plus travailler normalement. Il faut donc rester rigoureux sur le plan technique, tout en expliquant simplement ce que l'on vérifie et pourquoi.

Enfin, cette activité continue correspond bien à mon niveau de première année. Elle ne me présente pas comme responsable de la sécurité globale de l'entreprise, mais elle montre que j'ai commencé à construire une méthode d'investigation plus rigoureuse. Le point le plus important que j'en retiens est la nécessité de distinguer clairement ce qui est observé, ce qui est supposé et ce qui est réellement confirmé.


---

# Partie III — Méthodes, outils et ressources mobilisés

Cette partie ne reprend pas en détail les missions de la Partie II. Mon objectif est plutôt d'expliquer comment j'ai travaillé pendant cette première année d'alternance, avec quels outils, avec quelles ressources et avec quelles limites. Même si les sujets étaient différents, j'ai retrouvé une logique assez constante : partir d'un besoin concret, le reformuler, tester progressivement et rester prudent tant qu'un résultat n'était pas vraiment validé.

## 3.1 Démarche de travail et traitement d’un besoin

Dans le service informatique, les besoins n'arrivent pas toujours sous la forme d'une demande très cadrée. Souvent, le point de départ est plus simple : un usage à améliorer, un problème signalé par un utilisateur, un équipement à préparer ou un comportement technique à comprendre. Ma première étape consistait donc généralement à clarifier le besoin réel avec le tuteur ou avec les personnes concernées.

Cette phase de compréhension était importante, car le besoin exprimé ne correspondait pas toujours exactement au besoin réel. Il fallait souvent reformuler avant de chercher une solution. Pour une tablette gérée avec Intune, par exemple, la question n'était pas seulement de la configurer, mais de vérifier à quel usage elle était destinée et jusqu'où la sécurité pouvait rester compatible avec la simplicité d'utilisation. Pour le registre visiteurs, un formulaire qui fonctionne techniquement ne suffit pas si son usage reste peu pratique pour l'accueil. Sur les sujets de sécurité, un verrouillage de compte ne devait pas non plus être interprété trop vite sans recouper plusieurs éléments.

Une fois le besoin mieux défini, je passais par une phase de recherche. Cela pouvait être de la documentation, des vérifications dans l'outil, des échanges avec le tuteur ou le recoupement de plusieurs indices. J'ai beaucoup fonctionné comme cela sur les sujets que je découvrais, notamment Intune, mais aussi sur les analyses liées aux comptes et aux authentifications où il fallait comparer plusieurs hypothèses avant d'avancer.

L'organisation du travail restait assez souple. Le tuteur définissait généralement la priorité ou le cadre, puis je prenais en charge l'analyse, les recherches, les tests et les ajustements. En pratique, il fallait aussi composer avec les urgences du support quotidien. Cela m'a appris à faire la différence entre un sujet qui pouvait avancer progressivement et un autre qui demandait une vérification plus rapide avant de bloquer un utilisateur plus longtemps.

Je n'ai donc pas travaillé avec une logique de solution immédiate. J'avançais plutôt par étapes : comprendre la demande, vérifier le besoin réel, tester une piste, puis voir si elle répondait vraiment à l'usage. Un paramètre peut sembler correct dans l'outil et se comporter autrement sur l'équipement réel. De la même manière, en sécurité opérationnelle, un symptôme peut faire penser à une cause évidente alors qu'il faut encore recouper plusieurs éléments.

Avant de considérer une solution comme acceptable, une validation restait nécessaire. Selon les cas, il fallait distinguer la piste testée, la solution techniquement valable et la réponse réellement adaptée au besoin. Avec le recul, c'est sans doute ce que je retiens le plus de ma méthode de travail : comprendre le besoin, avancer par étapes et distinguer ce qui est encore une hypothèse de ce qui est réellement validé.

## 3.2 Outils techniques mobilisés

Les outils que j'ai utilisés pendant l'alternance sont variés, mais ils ont tous été mobilisés dans un environnement déjà en place chez Leroux. Je ne les présente donc pas comme une simple liste. Je les vois plutôt comme des moyens techniques cohérents avec le système d'information existant.

Un premier ensemble d'outils concerne la gestion des équipements mobiles. Dans ce cadre, Microsoft Intune et Android Enterprise étaient cohérents pour gérer des tablettes professionnelles de manière plus homogène et éviter une configuration trop manuelle appareil par appareil. Ils permettaient de centraliser les réglages, les applications et certaines restrictions dans un cadre déjà utilisé par l'entreprise.

Un deuxième ensemble concerne la création d'une solution interne simple à utiliser. Pour cela, j'ai mobilisé Power Apps, SharePoint et Power Automate. Cet ensemble était cohérent pour créer une application interne sans développement lourd, stocker les données dans un outil déjà utilisé dans l'environnement Microsoft et automatiser l'enregistrement de manière plus fiable.

Un troisième ensemble regroupe les outils liés aux comptes, aux identités, aux accès et au diagnostic. On y retrouve Active Directory, Microsoft 365, Microsoft Entra et les journaux Windows. Cet ensemble était cohérent avec l'environnement existant pour comprendre un verrouillage de compte, un échec d'authentification ou une connexion à vérifier. Dans cette famille d'outils, ce qui comptait le plus n'était pas de connaître une seule console, mais de croiser plusieurs sources d'information.

Si ces outils ont été mobilisés, c'est aussi parce qu'ils étaient déjà cohérents avec l'existant. Je n'étais pas dans une logique de choix libre entre plusieurs solutions. Le plus souvent, il fallait utiliser ce qui était déjà présent dans l'entreprise, ce qui s'intégrait bien au reste du système d'information et ce qui répondait au besoin sans ajouter de complexité inutile.

Cette partie m'a aussi appris qu'un outil ne résout rien à lui seul. Intune ne remplace pas les tests, Power Apps ne remplace pas la réflexion sur l'usage réel, et les journaux Windows ne remplacent pas l'analyse. Les outils donnent des moyens d'action, mais ils ne remplacent ni la méthode ni la vérification.

## 3.3 Ressources humaines, matérielles et documentaires

Au-delà des outils, j'ai travaillé avec plusieurs types de ressources. La première a été la ressource humaine. Dans une équipe informatique de deux personnes, le tuteur a un rôle important : il cadre le besoin, aide à prioriser les sujets et valide les décisions qui engagent davantage l'entreprise. Même lorsque j'étais autonome sur l'analyse ou les tests, je ne travaillais donc pas seul.

Les échanges avec les utilisateurs ont aussi compté. Dans plusieurs situations, comprendre la demande ou confirmer un comportement réel demandait d'aller voir directement la personne concernée, de reformuler le problème ou de vérifier si la solution proposée correspondait bien à l'usage. Cela m'a appris qu'un besoin informatique n'est pas toujours complètement visible depuis l'outil.

Certaines missions dépendaient aussi d'autres interlocuteurs internes. Le service maintenance en est un bon exemple, car la mise en service du registre visiteurs ne dépend pas seulement de la partie applicative. Cela m'a montré qu'une solution peut être prête sur le plan technique tout en restant liée à une contrainte matérielle ou interservices.

Les ressources matérielles ont eu leur importance : postes de travail, tablettes Android professionnelles, environnement de test et tablette destinée à l'accueil. Sans équipement réel, plusieurs validations auraient été beaucoup plus théoriques que pratiques.

Les ressources documentaires ont aussi été utiles. La documentation officielle Microsoft Learn et les recommandations Microsoft associées aux outils utilisés m'ont servi à comprendre certains comportements ou certaines possibilités d'Intune, d'Android Enterprise, de Power Apps, de Power Automate, de SharePoint, de Microsoft 365 et de Microsoft Entra. L'historique d'exécution de Power Automate m'a aidé à diagnostiquer plus précisément ce qui se passait dans le flux. Sur les sujets de sécurité, les recherches techniques, les journaux consultés, les échanges avec le tuteur, les retours des utilisateurs et les observations directes pendant les tests m'ont surtout aidé à mieux interpréter les événements observés.

Aucun coût, arbitrage budgétaire ou licence payante supplémentaire spécifique n'a été identifié dans les éléments dont je dispose. Les missions se sont appuyées sur les outils déjà disponibles dans l'environnement Microsoft de l'entreprise.

## 3.4 Tests, validations et gestion des limites

Pendant l'alternance, j'ai vite compris qu'une solution technique n'a pas beaucoup de valeur si elle n'est pas testée dans des conditions proches de son usage réel. Les tests ont donc pris une place importante dans ma manière de travailler. Je ne pouvais pas me contenter de voir qu'un paramètre existait dans un outil ou qu'une solution semblait correcte sur le papier.

Cette logique m'a surtout appris à comparer ce qui était attendu avec ce qui se passait réellement. Un test technique permettait d'abord de vérifier qu'une configuration, un flux ou une piste de diagnostic fonctionnait bien. Une validation d'usage allait plus loin : elle servait à vérifier que la solution correspondait réellement au besoin de départ. Par exemple, une tablette peut être bien configurée sans être encore assez adaptée à son usage, et une application peut fonctionner sans être encore prête à être utilisée dans les conditions réelles de l'accueil.

J'ai aussi mieux compris la différence entre une validation technique et une mise en service réelle. Cette dernière dépend parfois d'autres conditions, comme un support physique, un contexte utilisateur, un délai de maintenance ou une validation interne supplémentaire. C'est un point qui m'a marqué pendant l'année, parce qu'il montre qu'une solution techniquement valable ne suffit pas toujours à clore une mission.

La gestion des limites fait également partie de cette démarche. Je suis en première année d'alternance, donc certaines situations demandaient du recul, un échange avec le tuteur ou une validation avant d'aller plus loin. Cette posture m'a aidé à rester plus rigoureux et à ne pas annoncer trop vite qu'un sujet était terminé.

Plus largement, j'ai retenu qu'il fallait garder une trace claire de ce qui était validé et de ce qui restait à vérifier. Dans le travail quotidien comme dans le rapport, cette distinction évite de mélanger objectif, essai concluant et résultat final.

## 3.5 Confidentialité, anonymisation et posture professionnelle

La confidentialité a été une contrainte transversale dans l'ensemble de mes missions. Même lorsque le sujet paraissait surtout technique, il impliquait souvent des informations qu'il n'était pas utile, ni prudent, de diffuser telles quelles dans un rapport : noms de comptes, noms de postes, noms de serveurs, détails de configuration interne, données visiteurs ou extraits de journaux.

Concrètement, cela m'a obligé à rester général sur certains points. Dans les sujets de sécurité opérationnelle, je ne peux pas reprendre de journaux bruts, de noms d'utilisateurs ou d'adresses internes. Pour le registre visiteurs, les données personnelles doivent rester absentes du rapport. Pour Intune, il n'est pas nécessaire de publier des éléments internes trop précis dès lors qu'ils n'apportent rien à la compréhension de la démarche.

Cette contrainte ne m'a pas empêché d'expliquer ce que j'ai fait. Elle m'a surtout appris à trouver un équilibre entre précision technique, responsabilité de communication et protection de l'information. Dans un rapport d'alternance, il faut pouvoir expliquer une méthode de travail sans transformer l'expérience en documentation interne complète.

Cette logique rejoint aussi la posture professionnelle attendue d'un alternant. Savoir faire une action technique ne suffit pas. Il faut aussi savoir ce qu'on peut écrire, ce qu'on doit anonymiser et ce qui doit rester interne. J'ai pu gagner en autonomie sur la partie opérationnelle, mais j'ai aussi compris qu'il fallait savoir quoi communiquer, comment le formuler et à quel moment une validation restait nécessaire. Avec le recul, cette prudence fait partie de ce que cette première année m'a appris.


---

# Partie IV — Bilan personnel et compétences développées

Cette première année d'alternance m'a surtout permis de passer d'une logique de découverte à une logique de contribution plus structurée. En arrivant chez Leroux, je savais que j'allais travailler sur des sujets systèmes et réseaux, mais je n'avais pas encore une vision complète de ce que cela représentait dans une entreprise industrielle. Au fil des missions, j'ai mieux compris que le rôle ne consiste pas seulement à configurer des outils ou à résoudre un incident. Il demande aussi de comprendre le besoin réel, de mesurer les contraintes du terrain et de proposer une réponse utilisable par les personnes concernées.

## 4.1 Une progression réelle pendant l'année

Au début de l'alternance, j'étais surtout dans une phase d'observation et de prise en main. Je devais découvrir l'environnement de l'entreprise, les outils déjà en place, l'organisation du service informatique et la manière dont les demandes arrivaient. Cette étape était importante, car elle m'a évité de voir mes missions comme une suite d'actions isolées. J'ai progressivement compris que chaque sujet s'inscrivait dans un cadre plus large : continuité de service, sécurité, support aux utilisateurs et prudence sur les changements.

Cette progression s'est faite de manière concrète. Sur la mission Intune, j'ai dû prendre en main un outil que je ne maîtrisais pas encore et apprendre à distinguer les profils, les groupes, les restrictions, les applications et les tests. Sur le registre visiteurs, j'ai découvert qu'une solution qui semble simple côté utilisateur peut demander plusieurs étapes techniques pour fonctionner correctement. Sur la partie sécurité opérationnelle, j'ai appris à ne pas confondre un symptôme avec une cause et à avancer avec davantage de méthode.

Avec le recul, je constate que j'ai gagné en assurance, mais surtout en rigueur. Je me sens plus à l'aise pour analyser une demande, chercher des informations utiles, tester une configuration et expliquer ce que j'ai compris. Cette progression reste celle d'un étudiant de première année d'alternance : elle est réelle, mais elle ne signifie pas que je maîtrise déjà tous les sujets ou que je peux agir seul dans toutes les situations.

## 4.2 Montée en autonomie et posture professionnelle

L'un des points marquants de cette année est la montée en autonomie sur la partie opérationnelle. Dans le service informatique, mon tuteur définissait généralement le besoin, le cadre ou la priorité, puis je prenais en charge une partie importante du travail : recherches, tests, configuration, vérifications et ajustements. Cette autonomie m'a obligé à être plus organisé et à ne pas me contenter d'appliquer une suite d'actions sans les comprendre.

En même temps, cette autonomie a toujours eu des limites claires. Les décisions qui pouvaient engager l'entreprise sur un plan structurant, technique ou financier restaient validées par le tuteur ou par l'entreprise. Cette distinction m'a beaucoup appris. Elle m'a montré qu'être autonome ne signifie pas décider seul de tout, mais savoir avancer sérieusement sur son périmètre, documenter ce qui a été fait, identifier ses doutes et demander une validation au bon moment.

Sur le plan de la posture professionnelle, j'ai aussi mieux compris l'importance de la prudence. Dans un environnement informatique, aller trop vite peut faire perdre du temps ou créer d'autres problèmes. Cette année m'a donc appris à ralentir quand c'était nécessaire, à vérifier avant d'affirmer et à distinguer ce qui est fonctionnel en test de ce qui est réellement prêt à être utilisé. Cette manière de travailler me paraît importante pour le niveau CI1, car elle montre une progression vers une démarche plus responsable.

## 4.3 Difficultés rencontrées et manière de les gérer

Les difficultés rencontrées pendant l'année ont été utiles, car elles m'ont obligé à progresser. La première difficulté a souvent été la prise en main d'outils ou de situations que je connaissais peu. Intune, par exemple, m'a demandé un temps d'adaptation, car l'outil comporte plusieurs niveaux de configuration qui peuvent être confondus au début. De la même manière, la logique Power Apps / SharePoint / Power Automate m'a demandé de bien comprendre ce qui se passait à chaque étape du traitement de la donnée.

Une autre difficulté a été d'accepter qu'un problème ne se résout pas toujours immédiatement. Sur le registre visiteurs, la gestion de la signature m'a montré qu'un comportement utilisateur très simple pouvait cacher une difficulté technique plus précise. Sur les sujets de sécurité opérationnelle, j'ai aussi compris que plusieurs causes pouvaient rester possibles tant que toutes les vérifications n'étaient pas faites. Cela m'a appris à être plus patient et à avancer par étapes plutôt qu'à chercher une réponse trop rapide.

J'ai également dû apprendre à mieux gérer l'incertitude. Dans certaines situations, je ne pouvais pas conclure tout de suite. Il fallait garder une hypothèse ouverte, continuer à observer ou revenir vers le tuteur pour confronter mon analyse. Cette difficulté a été formatrice, car elle m'a appris qu'un bon diagnostic ne consiste pas à avoir une réponse immédiate, mais à construire une explication suffisamment solide pour être crédible.

## 4.4 Apprentissages techniques et méthodologiques

Sur le plan technique, cette année m'a permis de progresser sur plusieurs familles d'outils. J'ai développé une première expérience plus concrète de la gestion de terminaux mobiles avec Microsoft Intune et Android Enterprise. J'ai aussi mieux compris la logique de la Power Platform, en particulier le lien entre Power Apps, SharePoint et Power Automate pour construire une solution interne simple mais fiable. Enfin, les analyses autour d'Active Directory, de Microsoft 365 et des journaux m'ont apporté une base plus solide en diagnostic et en sécurité opérationnelle.

Ces apprentissages techniques ont surtout été utiles parce qu'ils étaient reliés à des besoins réels. Je n'ai pas seulement découvert des outils ; j'ai appris à les mobiliser dans un contexte d'entreprise, avec des contraintes d'usage, de sécurité et de confidentialité. Cela change la manière de les comprendre, car un paramètre ou une automatisation n'a de valeur que s'il répond à un besoin concret.

Sur le plan méthodologique, j'ai appris à mieux structurer mon travail. Cette progression passe par plusieurs réflexes que j'ai davantage développés pendant l'année : clarifier le besoin de départ, tester avant de considérer qu'une solution est correcte, croiser plusieurs sources d'information lorsqu'un diagnostic reste incertain, et conserver une distinction nette entre ce qui est observé, ce qui est supposé et ce qui est validé. Cette méthode m'a particulièrement servi sur la mission sécurité, mais elle s'applique en réalité à l'ensemble de mes missions.

## 4.5 Relation avec les utilisateurs et compréhension du métier

Les échanges avec les utilisateurs ont aussi joué un rôle important dans mon évolution. En début d'année, il est facile de voir un sujet surtout sous son angle technique. Avec l'expérience, j'ai mieux compris qu'une demande informatique doit être replacée dans son usage réel. Un utilisateur n'attend pas seulement qu'un paramètre soit correct. Il attend que la solution lui permette de travailler dans de bonnes conditions.

Cette idée m'a aidé à mieux comprendre le rôle d'un administrateur systèmes et réseaux. Ce métier ne consiste pas uniquement à faire fonctionner des outils. Il consiste aussi à rendre ces outils utilisables, compréhensibles et suffisamment fiables pour qu'ils s'intègrent au travail quotidien. La différence entre "faire fonctionner techniquement" et "livrer une solution réellement utilisable" m'a particulièrement marqué avec le registre visiteurs. La partie applicative peut être terminée, mais tant que l'usage réel n'est pas possible à l'accueil, la mission ne peut pas être présentée comme totalement aboutie.

J'ai retrouvé cette même idée dans les autres missions. Une tablette peut être bien configurée dans Intune, mais elle doit aussi rester adaptée à son usage réel. Un diagnostic de sécurité peut être techniquement intéressant, mais il doit surtout aider à comprendre un problème concret pour un utilisateur ou pour le service. Cette prise de recul me paraît importante, car elle relie la technique au service rendu.

## 4.6 Lien avec le niveau CI1 et axes de progrès

Ce bilan correspond bien, selon moi, au niveau attendu en CI1. Je ne présente pas une expertise complète ni une maîtrise totale des sujets. En revanche, je peux montrer une progression réelle dans ma manière de travailler, dans ma compréhension du contexte d'entreprise et dans ma capacité à participer à des missions concrètes avec davantage d'autonomie et de recul.

Cette première année m'a appris à mieux comprendre le cadre dans lequel j'évolue, à prendre ma place dans une petite équipe informatique et à construire une méthode plus rigoureuse. Elle m'a aussi montré les points que je dois encore approfondir. Je dois continuer à progresser sur la formalisation de la documentation, sur l'analyse plus rapide de certains incidents, sur la maîtrise des environnements Microsoft et sur la capacité à relier encore plus efficacement le besoin utilisateur, la contrainte technique et la solution proposée.

En résumé, cette année ne m'a pas seulement apporté de nouvelles connaissances techniques. Elle m'a surtout appris à travailler de manière plus professionnelle, plus prudente et plus utile dans un contexte réel. C'est cette évolution que je retiens comme le principal apport de ma première année d'alternance chez Leroux.


---

# Partie V — Perspectives d’évolution

Cette partie ne vise pas à annoncer une feuille de route officielle de l'entreprise. Mon objectif est plutôt de présenter les suites qui me paraissent cohérentes à partir des missions réalisées, ainsi que les axes sur lesquels je peux continuer à progresser pendant la suite de mon alternance. Les perspectives présentées ici doivent donc être comprises comme des pistes réalistes, et non comme des décisions déjà actées dans tous les cas.

## 5.1 Suites possibles des missions réalisées

La première perspective concerne la mission Microsoft Intune / Android Enterprise. Le travail réalisé a permis de mettre en place une base de configuration pour les tablettes professionnelles, mais ce type de sujet demande un suivi dans le temps. Une configuration qui fonctionne au moment des tests doit encore être observée dans l'usage, car certains ajustements peuvent apparaître après plusieurs semaines ou selon les retours des utilisateurs. La suite logique est donc de continuer à vérifier le comportement réel des tablettes, d'adapter certains paramètres si nécessaire et de mieux formaliser la configuration retenue pour qu'elle soit plus simple à reprendre ou à faire évoluer.

Une autre perspective liée à Intune concerne la documentation. Même si une configuration est comprise au moment où elle est mise en place, elle gagne à être décrite de façon plus claire pour faciliter le suivi du parc, les futurs ajustements et la transmission d'information dans le service informatique. Cet aspect me paraît important, car il permet de transformer un travail opérationnel en base plus durable.

Pour le registre visiteurs numérique, la suite la plus évidente concerne la mise en service réelle de la solution. La partie applicative est terminée et validée techniquement, mais son usage à l'accueil dépend encore de l'installation du support physique de la tablette par le service maintenance. Tant que cette étape n'est pas réalisée, il faut rester prudent sur l'état final du projet. La perspective réaliste n'est donc pas de présenter un déploiement déjà terminé, mais de préparer une mise en service dans de bonnes conditions une fois le support installé.

Après cette installation, des tests en conditions réelles seront probablement utiles. Une solution peut être correcte sur le plan technique tout en demandant encore quelques ajustements lorsqu'elle est utilisée dans le cadre quotidien de l'accueil. Les suites possibles concernent donc la validation pratique du parcours utilisateur, la vérification de la simplicité de saisie et, si besoin, la correction de points mineurs repérés après les premiers usages.

La mission de sécurité opérationnelle autour d'Active Directory et de Microsoft 365 appelle elle aussi une continuité, mais sous une autre forme. Comme il s'agit d'une activité liée aux incidents et aux demandes quotidiennes, la perspective la plus cohérente est de poursuivre la même logique de diagnostic : avancer avec prudence, croiser les sources d'information et mieux documenter les cas rencontrés lorsqu'ils peuvent servir de référence interne. L'enjeu n'est pas de promettre la disparition des incidents, mais de consolider une méthode de traitement plus claire et plus réutilisable.

Dans cette mission, une autre perspective importante concerne la documentation interne et la capitalisation. Lorsqu'un cas de verrouillage, d'authentification ou de connexion suspecte a été analysé correctement, garder une trace de la méthode suivie peut aider à gagner du temps sur des situations proches. Cette capitalisation doit cependant rester prudente et compatible avec la confidentialité des données manipulées.

## 5.2 Perspectives sur les méthodes et les outils

Au-delà de chaque mission, une perspective plus générale concerne la formalisation progressive des méthodes de travail. Pendant cette première année, j'ai surtout appris à avancer par tests, par vérifications et par échanges avec le tuteur ou les utilisateurs. Pour la suite, il serait utile de rendre cette méthode plus visible à travers une documentation plus régulière, des procédures plus faciles à relire et une meilleure conservation des points de vigilance rencontrés.

Cette formalisation peut aussi aider à mieux capitaliser sur les outils déjà utilisés. Intune, Power Apps, SharePoint, Power Automate, Active Directory et les outils de diagnostic ne sont pas seulement des solutions techniques ponctuelles. Ils peuvent devenir des supports de travail plus stables si leur usage, leurs limites et les bonnes pratiques associées sont mieux rédigés et mieux partagés dans le service.

Je vois donc une perspective double : continuer à progresser techniquement sur ces outils, mais aussi mieux structurer la manière de les utiliser. Cette évolution me paraît importante, car elle correspond à une différence nette entre exécuter une tâche et construire une manière de travailler plus durable.

## 5.3 Perspectives personnelles pour la suite de l'alternance

Sur le plan personnel, je souhaite continuer à progresser en autonomie, mais dans le même esprit que cette première année. L'objectif n'est pas de me présenter comme totalement autonome sur tous les sujets, mais d'être capable de prendre en charge davantage d'analyse, de préparation, de tests et de documentation, tout en sachant quand une validation reste nécessaire. Cette progression me semble plus réaliste et plus utile qu'une autonomie affichée de manière trop large.

Je souhaite aussi approfondir mes compétences sur plusieurs points techniques déjà rencontrés pendant l'année. La gestion des environnements Microsoft, la sécurité opérationnelle, le diagnostic d'incidents et la compréhension des mécanismes d'authentification sont des domaines sur lesquels je peux encore progresser. La suite de l'alternance peut me permettre de renforcer ces bases avec plus d'expérience et avec des cas concrets supplémentaires.

Un autre axe de progression personnel concerne la documentation. Cette année m'a montré qu'une solution bien comprise au moment où elle est réalisée n'est pas forcément simple à reprendre plusieurs semaines plus tard si elle n'a pas été suffisamment formalisée. Je veux donc améliorer cet aspect, que ce soit pour mes propres sujets ou pour faciliter le suivi dans le service.

Je veux également continuer à progresser sur la relation entre technique et usage. Les missions de cette année m'ont appris qu'une solution n'est réellement utile que si elle répond à une situation concrète et si elle reste compréhensible pour les utilisateurs. Pour la suite, je souhaite donc être encore plus attentif à cette dimension, notamment dans la manière de recueillir un besoin, de tester une solution et de vérifier qu'elle correspond bien à l'usage réel.

Enfin, cette première année m'a donné envie de mieux développer une logique de gestion de projet à petite échelle : mieux cadrer un besoin, suivre les étapes, identifier les dépendances, noter les points de blocage et anticiper les validations nécessaires. Même sur des sujets techniques, cette organisation me paraît utile pour gagner en clarté et en efficacité.

## 5.4 Limites et prudence sur ces perspectives

Ces perspectives doivent cependant rester mesurées. Certaines dépendent de décisions de l'entreprise, de priorités internes, du temps disponible dans le service informatique ou d'éléments matériels extérieurs, comme le support de la tablette d'accueil. D'autres dépendent simplement des situations que je rencontrerai pendant la suite de l'alternance. Il ne serait donc pas rigoureux de transformer ces pistes en engagements fermes.

La limite principale est la même que dans le reste du rapport : je peux identifier des suites cohérentes et des axes de progrès, mais je ne dois pas annoncer des déploiements, des résultats ou des projets non confirmés. Cette prudence est importante, car elle permet de rester fidèle à ce qui a été réellement observé pendant cette première année.

En résumé, les perspectives les plus crédibles me semblent être la poursuite du suivi des tablettes gérées avec Intune, la mise en service puis l'ajustement du registre visiteurs lorsque le support physique sera installé, la continuité de la méthode de diagnostic sur les sujets de sécurité, ainsi que ma progression personnelle sur l'autonomie, la documentation, la sécurité, le diagnostic et l'organisation du travail. Ce sont des prolongements réalistes des missions déjà réalisées, sans aller au-delà de ce qui est aujourd'hui confirmé.


---

# Conclusion

Cette première année d'alternance chez Leroux m'a permis de découvrir de manière concrète le fonctionnement d'un service informatique dans une entreprise industrielle agroalimentaire. En rejoignant une équipe de deux personnes, j'ai dû apprendre à situer mes missions dans un cadre plus large que la seule technique : continuité de service, sécurité, accompagnement des utilisateurs, tests avant mise en service et prudence dans les changements. Ce contexte m'a aidé à mieux comprendre le rôle d'un administrateur systèmes et réseaux dans un environnement où les outils informatiques doivent rester fiables, utiles et adaptés aux usages quotidiens.

Les trois missions principales présentées dans ce rapport illustrent bien cette progression. La gestion des tablettes Android avec Microsoft Intune et Android Enterprise m'a fait découvrir une logique d'administration plus centralisée, avec un équilibre à trouver entre sécurité et simplicité d'utilisation. Le registre visiteurs numérique m'a permis de travailler sur une solution concrète, de la saisie dans Power Apps jusqu'au traitement de la signature dans SharePoint et Power Automate, tout en gardant une distinction claire entre validation technique et mise en service réelle. La mission continue de sécurité opérationnelle autour d'Active Directory, de Microsoft 365 et de Microsoft Entra m'a appris à avancer avec plus de méthode dans les diagnostics, à recouper les informations et à distinguer un symptôme d'une cause réellement confirmée.

Au-delà des outils, cette année m'a surtout fait progresser dans ma manière de travailler. J'ai gagné en autonomie sur la partie opérationnelle, mais j'ai aussi compris que cette autonomie doit rester accompagnée de vérifications, de tests et de validations adaptées. J'ai appris à mieux reformuler un besoin, à prendre du recul face à un problème technique et à relier davantage mes actions à leur usage réel dans l'entreprise. Cette évolution me paraît importante, car elle correspond à l'esprit du rapport CI1 : montrer non seulement ce qui a été fait, mais aussi ce que cette expérience m'a appris sur le métier, sur ma posture et sur ma progression.

Cette alternance m'a également permis de faire un lien concret avec ma formation à l'IMT Nord Europe. Les connaissances techniques vues en cours prennent davantage de sens lorsqu'elles sont confrontées à des besoins réels, à des contraintes d'entreprise et à des situations qui demandent de la méthode. À l'inverse, l'expérience en entreprise nourrit aussi ma formation, car elle me pousse à mieux comprendre les outils, à poser les bonnes questions et à développer une démarche plus rigoureuse.

Pour la suite de mon alternance, je souhaite continuer à approfondir les sujets déjà rencontrés, notamment autour des environnements Microsoft, de la sécurité opérationnelle, de la documentation et du diagnostic. Je souhaite aussi poursuivre ma progression en autonomie, tout en gardant la prudence nécessaire dans un environnement professionnel. Cette première année ne représente donc pas un aboutissement, mais une base solide pour continuer à apprendre, à contribuer plus efficacement au service informatique et à construire progressivement ma posture d'ingénieur en alternance.


---

# Annexe — Usage de l'IA

## Outils utilisés

Les outils d'intelligence artificielle utilisés dans le cadre de ce rapport sont ChatGPT et Codex.

## Usages réalisés

Ces outils ont été utilisés comme aide à la structuration du rapport, à la rédaction de certains passages, à la reformulation, à la relecture et au contrôle qualité. Ils ont aussi été utilisés pour préparer des prompts de travail dans Codex, vérifier la cohérence entre les parties du rapport et signaler les points qui restaient à compléter ou à vérifier.

## Niveau d'intervention

L'IA n'a pas réalisé seule le rapport. Elle a servi d'outil d'assistance pour proposer des formulations, organiser les idées, améliorer la clarté du texte et repérer certaines incohérences ou répétitions.

## Parties concernées

L'usage de l'IA a concerné principalement la structuration générale du rapport, la reformulation de passages rédigés, la préparation de certaines sections, l'annexe IA elle-même et les vérifications de cohérence entre le plan, les missions, le bilan personnel, la conclusion et les sources.

## Validation humaine

L'étudiant reste entièrement responsable du contenu final du rapport. Les propositions générées par l'IA ont été relues, triées, corrigées et validées humainement avant intégration. Les informations internes, sensibles ou incomplètes ont été anonymisées, retirées ou signalées comme restant à confirmer lorsqu'une validation manquait.

## Limites d'usage

L'IA peut proposer des formulations utiles, mais elle peut aussi produire des erreurs, des approximations ou des tournures trop générales. Pour cette raison, chaque passage généré ou reformulé doit être vérifié avant d'être conservé. L'IA ne remplace ni l'expérience réelle de l'étudiant, ni la validation des faits, ni le recul personnel attendu dans un rapport d'alternance.

## Impact environnemental

L'utilisation de l'IA a été faite de manière raisonnée. Cet usage a été limité aux besoins utiles pour structurer, relire ou améliorer le rapport, afin d'éviter les générations inutiles. Même sans disposer ici d'une mesure carbone précise, il reste important de garder à l'esprit que ces outils ont un impact environnemental et qu'ils doivent être utilisés avec sobriété.


---

# Bibliographie Zotero

## Sources à importer

- Sources publiques officielles de Leroux : pages institutionnelles et pages publiques sur l'entreprise, la fabrication, la filière et les produits.
- Documentation officielle Microsoft Learn et documentation Microsoft associée : pages générales utilisées pour vérifier la terminologie et les bonnes pratiques autour de Microsoft Intune, Android Enterprise, Power Apps, SharePoint, Power Automate, Active Directory, Microsoft 365 et Microsoft Entra.
- Consignes IMT Nord Europe : `00_contexte_source/01_consignes_imt.md`.
- Grille d'évaluation IMT Nord Europe : `00_contexte_source/02_grille_evaluation.md`.
- Source interne anonymisée : échanges et éléments de contexte internes utilisés pour décrire le service informatique, les missions et leur état réel, sans reprise de données sensibles.

Les sources retenues regroupent les pages publiques officielles de Leroux, la documentation officielle Microsoft Learn, les documents pédagogiques IMT et des sources internes anonymisées.

## Règles

- Ne pas ajouter de source non vérifiée.
- Vérifier la date, l'auteur et l'éditeur.
- Conserver les liens consultés uniquement s'ils sont utiles et validés.
- Distinguer clairement les sources publiques, la documentation technique et les sources internes anonymisées.
