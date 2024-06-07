# Planification de projets IA dans les GLAM

*Cette ressource est une traduction du ["Artificial Intelligence Planning Framework"](https://blogs.loc.gov/thesignal/2023/11/introducing-the-lc-labs-artificial-intelligence-planning-framework/) proposé par le LC Labs de la Bibliothèque du Congrès (Abigail Potter, 2023).
Elle inclut une présentation du framework ainsi que des documents implémentant la méthode.*

---

Depuis son lancement en 2016, LC Labs explore la manière d'utiliser les technologies émergentes pour étendre l'utilisation des documents numériques. Nous avons rapidement vu l'apprentissage automatique (ML), une branche de l'intelligence artificielle (IA), comme un moyen potentiel de fournir plus de métadonnées et de connexions entre les éléments de la collection et les utilisateurs. Des expériences et des recherches ont montré que les risques et les avantages de l'utilisation de l'IA dans les bibliothèques, les archives et les musées (LAM) sont à la fois importants et encore largement hypothétiques. En bref :
- Les collections des bibliothèques sont incroyablement diversifiées et il est particulièrement difficile pour les outils actuels d'apprentissage automatique et d'IA de les traiter de manière prévisible.
- De nouveaux outils d'IA aux prétentions impressionnantes sont rapidement mis sur le marché. Nous avons tout à gagner à tester ces outils ouvertement, à collaborer et à apprendre des autres.
- Il convient d'élaborer et de communiquer aux partenaires et aux fournisseurs des normes et des politiques de qualité spécifiques à l'IA qui s'inscrivent dans notre contexte de fourniture au public de ressources faisant autorité sur le long terme.
- Bien que la mise en œuvre à grande échelle de l'IA responsable dans les LAM ne soit pas encore pour demain, le moment est venu d'intensifier l'expérimentation et la collaboration au sein de notre organisation et dans l'ensemble du secteur.

Pour tenir compte de ces défis et réalités, LC Labs a développé un cadre de planification pour soutenir l'exploration responsable et l'adoption potentielle de l'IA à la bibliothèque. Au niveau élevé, le cadre comprend trois phases de planification :  1) Comprendre, 2) Expérimenter et 3) Mettre en œuvre, chacune soutenant l'évaluation de trois éléments de l'intelligence artificielle : 1) les données, 2) les modèles et 3) les personnes. Nous avons élaboré un ensemble de fiches de travail, de questionnaires et d'ateliers afin d'impliquer les parties prenantes et le personnel et d'identifier les priorités pour les améliorations et les services futurs en matière d'IA. Les mécanismes, outils, collaborations et artefacts forment ensemble le cadre de planification de l'IA. En partageant le cadre et les outils associés dans cette version initiale, nous espérons encourager d'autres personnes à l'essayer et solliciter un retour d'information supplémentaire. Nous continuerons à mettre à jour et à affiner le cadre au fur et à mesure que nous en apprendrons davantage sur les éléments et les phases de la planification de l'intelligence artificielle.

## Données, modèles, personnes
Lors de la planification et de la réalisation d'expérimentations d'IA et de ML à la Bibliothèque du Congrès, nous avons simplifié les processus de ML en trois éléments principaux :  les données, les modèles et les personnes. La façon dont ces éléments sont combinés nous aide à comprendre si une application de cette technologie est utile, éthique et efficace.

![Éléments principaux du ML](https://blogs.loc.gov/thesignal/files/2023/11/AIframework-1.jpg)

### Données

Le terme « données » est omniprésent dans tous les aspects du ML. Les données servent à l'entraînement, à l'entrée et à la sortie du modèle. Les données contiennent les motifs (ou étiquettes) que les modèles reconnaissent et prédisent, et les données permettent de valider si les prédictions sont correctes. À la Bibliothèque du Congrès, nos données sont souvent des données de collections, des données historiques sur les droits d'auteur ou des données législatives. Les données de la Bibliothèque du Congrès comprennent tous les formats numériques et ne sont souvent disponibles nulle part ailleurs. Ces ensembles de données du monde réel n'ont pas été créés pour être traités par l'IA. Leur désordre inhérent, leur déséquilibre, leur incomplétude et leur contenu historique perturbent les modèles, ce qui entraîne des résultats indésirable ou erronés. Les mesures publiées sur l'état de l'art des performances des modèles ou des outils sont souvent basées sur les résultats du traitement de données contemporaines ou d'ensembles de données bien connus dans le cadre de la recherche.

### Modèles

Le terme « modèle » désigne un ensemble complexe de technologies et d'outils qui soutiennent l'entraînement, le traitement et la prédiction de l'algorithme de ML. La capacité du programme de ML à apprendre des modèles à partir de données sans qu'on lui dise explicitement ce qu'il doit traiter distingue le ML des autres programmes informatiques. La manière dont les modèles sont entraînés, ce sur quoi ils sont entraînés, la manière dont les données sont traitées et transmises aux utilisateurs ou à d'autres systèmes sont autant d'éléments qui déterminent l'efficacité du modèle pour une tâche spécifique.  Les modèles de traitement de la parole et du texte, souvent appelés traitement du langage naturel (NLP), sont développés par les informaticiens depuis plus de 20 ans.  Les progrès dans les méthodes d'entraînement des modèles, les architectures cloud sur lesquelles les modèles peuvent traiter des données et la disponibilité de très grands ensembles de données sur l'internet pour l'entraînement sont des développements plus récents. Un nombre croissant de fournisseurs proposent des services d'IA dans lesquels les modèles sont pré-entraînés, affinés et regroupés dans des flux de travail qui sont la propriété du propriétaire du service.

### Personnes

Bien que le ML soit un processus technique et axé sur les données, les humains sont essentiels au ML et sont liées aux données et modèles. Les personnes créent et sont représentées dans les données, et leur vie privée ainsi que d'autres droits sont protégés par des réglementations et des lois.  Les personnes conçoivent et programment des outils d'IA pour atteindre des objectifs spécifiques, certains scientifiques et d'autres commerciaux. L'expertise et les fonctions du personnel sont représentées dans les cas d'utilisation potentiels de la ML. S'il n'existe pas de données d'entraînement pour un cas d'utilisation, il est probable que des personnes devront étiqueter des ensembles de données, ce qui ajoute une autre tâche à gérer. Les systèmes de ML peuvent avoir un impact positif ou négatif sur les personnes. Les personnes et les organisations qu'elles représentent sont responsables de la qualité de leurs systèmes d'IA. En fin de compte, ce sont eux qui déterminent quand et comment mettre en œuvre l'IA et s'ils le font de manière responsable.

## Phases de la planification 
La prise en compte des données, des modèles et des personnes impliqués dans un système d'IA est intégrée dans notre cadre de planification. Les étapes *Comprendre, Expérimenter* et *Mettre en œuvre* comprennent des activités de collaboration et aboutissent à une documentation qui participe au développement de pratiques et de politiques pour une IA responsable.

![Phases de la planification](https://blogs.loc.gov/thesignal/files/2023/11/AIframework-2.jpg)

### Comprendre

La première série d'activités consiste à comprendre l'utilisation proposée de l'IA et la manière dont le cas d'usage s'inscrit dans le cadre d'une tâche, d'un système ou d'une organisation. Commencez par recueillir différents points de vue et réfléchissez spécifiquement aux fonctions et aux services assurés par votre équipe.  En gardant à l'esprit les cas d'usage particuliers, formulez en collaboration des principes directeurs, évaluez les risques et les avantages, identifiez les besoins, les priorités et l'expertise, et renseignez-vous sur l'état de préparation des données. Lorsque nous avons recueilli des cas d'usage de l'IA dans l'ensemble de la Bibliothèque, il nous a été utile d'être très précis sur les personnes, les modèles et les données impliqués dans un cas d'usage donné. Nous avons donc développé les outils et les conseils suivants pour aider les organisations à affiner les cas d'usage et à évaluer leur faisabilité.

- Les valeurs, principes et politiques énoncés pour la mise en œuvre de l'IA éclairent les décisions complexes. Consulter les [principes](https://www.federalregister.gov/documents/2020/12/08/2020-27065/promoting-the-use-of-trustworthy-artificial-intelligence-in-the-federal-government?loclr=blogsig) proposés par la Maison Blanche des États-Unis pour l'utilisation de l'IA dans l'administration est un excellent point de départ.
  
- Nous avons créé un [modèle pour l'évaluation des cas d'usage]() afin de présenter au personnel les circonstances qui peuvent réduire ou augmenter les risques pour un cas d'utilisation donné. Une deuxième [phase d'évaluation]() permet d'articuler les risques et les avantages pour différents groupes et de documenter les critères de réussite pour un cas d'utilisation donné.
  
- Le manque de données de formation et d'évaluation disponibles pour les modèles est un obstacle courant pour les cas d'utilisation de l'IA. Les données LAM sont également déséquilibrées par nature, ce qui affectera la qualité des résultats de l'IA. Nous avons élaboré un [modèle]() pour comprendre et documenter l'état de préparation des données en vue de leur utilisation dans les systèmes d'IA.
  
- Un atelier sur le profil des domaines est en cours d'élaboration pour guider le regroupement et la mise en correspondance de plusieurs cas d'utilisation afin de clarifier les priorités en fonction des niveaux d'expertise, des risques ou des fonctions.

Les ressources et les compétences nécessaires pour soutenir le travail d'IA ne sont souvent pas abondantes dans les LAM. En général, les cas d'utilisation présentant des niveaux de risque plus élevés nécessiteront plus de ressources et de temps pour être mis en œuvre. Les laboratoires ont développé les outils de compréhension pour aider le personnel à appliquer leur expertise et à évaluer où l'IA pourrait être appliquée de la manière la plus productive. Dans les cas d'utilisation où les avantages et les risques sont bien compris et pris en compte, où les données sont disponibles pour l'entraînement et l'évaluation des modèles, et où l'expertise et les ressources ont été identifiées, l'étape suivante consiste à déterminer ou à confirmer qu'une solution d'IA fonctionne.

### Expérimenter

De nouveaux produits IA sont fréquemment mis sur le marché, chacun avec son propre mélange d'outils et d'affirmations marketing. Des expériences permettent de tester des cas d'utilisation spécifiques, avec des modèles et des données, avec le personnel et les utilisateurs afin de documenter les performances et d'établir des comparaisons et des références en termes de qualité. Il s'agit d'une étape nécessaire avant toute mise en œuvre, car les mesures de performance publiées, qui peuvent atteindre une précision de 95 à 99 % pour certaines tâches de traitement du langage naturel, ne peuvent souvent pas être atteintes lors du traitement des données GLAM. Des références minimales de qualité doivent être établies pour la plupart des cas d'utilisation de l'IA dans les GLAM.

Les références de qualité sont créées en testant et en documentant une série d'approches susceptibles de prendre en charge un cas d'utilisation et en analysant les résultats en détail. Outre les tests de performance approfondis, des processus d'examen de la qualité doivent être mis en place. Les résultats de l'IA doivent être examinés par le personnel et les utilisateurs afin de déterminer s'ils sont suffisamment bons pour être utilisés par les GLAM. Il convient également de confirmer que les conséquences de l'automatisation continuent à soutenir les principes et les objectifs de l'organisation.  Le processus de test de cas d'utilisation spécifiques avec le personnel et les utilisateurs permettra de recueillir un retour d'information important. Il permettra également de développer une expertise en matière d'évaluation des données générées par l'IA. Nous utilisons les outils et mécanismes suivants pour les expériences :

 - Le contrat _Digital Innovation Indefinite Delivery Indefinite Quantity_ (IDIQ) est un mécanisme de contrat pluriannuel que nous pouvons utiliser pour réaliser des expériences d'IA à la Bibliothèque du Congrès ; il inclut des spécifications qui peuvent être utiles à la communauté dans son ensemble.

- Le  _Data Processing Plan_ (plan de traitement des données, [trad. FR]()) documente les transformations de données et les performances prévues et réelles du modèle d'IA pour des tâches spécifiques. Il combine des éléments d'une carte de modèle, d'une feuille de couverture de données et documente la provenance des données. Les fournisseurs sont tenus de le remplir dans le cadre du Digital Innovation IDIQ.

- _En cours de développement_ : Guide d'évaluation des fournisseurs de NLP et recommandations pour l'examen de la qualité.
- _En cours de recommandation_ : Ensembles de données équilibrés pour l'évaluation comparative des modèles et outils d'IA nouvellement disponibles.




### Mettre en œuvre

