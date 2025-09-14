#  Bootcamp Data Science + IA : Projet Phase 1
Preparé et presenter par SAINT GERMAIN Emode

# Analyse-accidents-aeriens
![ Analyse-accidents-aeriens](https://github.com/Germode/Analyse-accidents-aeriens/blob/main/Images/Analyse-accidents-aeriens.png)
# Aperçu
Ce projet de science des données analyse les données d'accidents d'aviation de 1962 à 2023 afin d'éclairer la prise de décision stratégique dans le secteur aéronautique. Grâce au nettoyage, à l'exploration et à la visualisation des données, l'objectif est d'identifier les modèles d'avions à faible risque et de générer des informations exploitables pour les acteurs économiques envisageant d'investir dans l'aviation.

# Problème Commercial
![aviation](https://github.com/Germode/Analyse-accidents-aeriens/blob/main/Images/aviation.png)
Pour orienter une entreprise fictive dans ses décisions d’investissement dans le secteur aéronautique, ce projet propose une analyse approfondie des tendances historiques en matière d’accidents aériens. L’objectif principal est d’identifier les modèles d’avions présentant les meilleurs niveaux de fiabilité afin de réduire les risques liés à l’acquisition et à l’exploitation d’appareils, qu’ils soient commerciaux ou privés.

L’étude s’appuie sur les données d’accidents recueillies par le National Transportation Safety Board entre 1962 et 2023. Ces informations permettront d’examiner les causes récurrentes d’incidents, de détecter les facteurs contextuels à haut risque — tels que les conditions météorologiques, la maintenance ou les erreurs humaines — et de dégager des tendances solides sur plus de six décennies.

Grâce à cette approche, l’entreprise bénéficiera de recommandations concrètes pour optimiser l’allocation de ses ressources, sécuriser ses investissements et renforcer la sécurité de ses opérations. En identifiant les appareils les plus sûrs et les contextes les plus critiques, elle pourra non seulement améliorer la fiabilité de sa flotte mais aussi contenir les coûts de maintenance et de formation. Cette analyse servira donc de base stratégique pour planifier les futures opérations, soutenir la croissance durable de l’activité aéronautique et inspirer la confiance des partenaires financiers et des clients.

# Données
Le dataset contient un du National Transportation Safety Board qui comprend des données sur les accidents d'aviation de 1962 à 2023 concernant les accidents de l'aviation civile et des incidents sélectionnés aux États-Unis et dans les eaux internationales [source des données sur les accidents aériens](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses/data)], 

Identifiant unique de l'accident <br> Date et heure de l'accident <br> Type d'avion impliqué <br> Causes présumées <br> Nombre de victimes <br>
# Méthodes
Ce projet repose sur une analyse descriptive approfondie visant à mettre en évidence les tendances évolutives des accidents aériens sur plus de soixante ans. L’approche consiste à examiner la fréquence des incidents, leur répartition géographique et temporelle, ainsi que la gravité des conséquences. En segmentant les données par variables clés — telles que le type d’aéronef, la phase de vol, les conditions météorologiques, la région du monde, ou encore les causes probables (erreur humaine, défaillance mécanique, facteurs environnementaux) — l’étude permet de dégager des schémas précis et de suivre leur évolution dans le temps.

Cette exploration statistique offre ainsi une vision claire des types d’accidents les plus courants, des facteurs de risque récurrents et de leurs interactions potentielles. Les résultats fournissent une base solide pour identifier les appareils et contextes les plus vulnérables, tout en mettant en lumière les périodes ou conditions qui exigent une vigilance particulière. En somme, l’analyse descriptive ne se limite pas à dresser un état des lieux : elle constitue un outil essentiel pour orienter les futures stratégies de prévention, guider les investissements en sécurité aérienne et améliorer la prise de décision à long terme dans l’industrie.

# Résultats
La majorité des accidents enregistrés impliquent des avions de type [Airplain], ce qui en fait la catégorie d’appareils la plus touchée sur l’ensemble de la période étudiée. Par ailleurs, le nombre d’incidents atteint un pic marqué dans les années [1980], révélant une concentration inhabituelle d’événements critiques. Cette tendance met en évidence l’importance d’une vigilance accrue durant cette décennie, qu’il s’agisse de l’application de normes de sécurité, de la maintenance des appareils ou du renforcement des procédures opérationnelles.

Cette observation souligne également la nécessité d’examiner les facteurs contextuels propres à cette période — tels que l’évolution des technologies aéronautiques, la croissance du trafic, ou les pratiques de régulation — afin de mieux comprendre les causes de cette augmentation et d’en tirer des enseignements pour les politiques de prévention actuelles et futures.

# Visualisations
Voici une visualisation des accidents par type d'avion

!['Nombre d\'Accidents par Type d\'Avion'](https://github.com/Germode/Analyse-accidents-aeriens/blob/main/Images/t%C3%A9l%C3%A9chargement%20(1).png)

Voici une visualisation des Accidents au Fil des Ans

![Accidents au Fil des Ans](https://github.com/Germode/Analyse-accidents-aeriens/blob/main/Images/t%C3%A9l%C3%A9chargement%20(2).png)
# Tableau de bord interacti
Voici le  Tableau de bord interactif
[Tableau de bord interactif](https://github.com/Germode/Analyse-accidents-aeriens/blob/main/Tableau%20de%20bord%20interactif%20Projet%20Phase1.pbix)

![Tableau de bord interactif](https://github.com/Germode/Analyse-accidents-aeriens/blob/main/Images/Tableau%20de%20bord%20interactif%20Projet%20Phase1_page-0001.jpg)

# Conclusions
Cette analyse conduit à plusieurs recommandations pour améliorer la sécurité aérienne :

Campagnes de sensibilisation : Mener des campagnes de sensibilisation ciblées pour les types d'avions à haut risque. <br> Optimisation des ressources : Adapter les ressources humaines et matérielles selon les périodes de pic d'accidents. <br> Investissement technologique : Promouvoir l'innovation dans les technologies de sécurité pour prévenir les accidents.<br>
# Prochaines Étapes
Des analyses supplémentaires pourraient fournir des informations pour améliorer davantage la sécurité aérienne :

Modélisation des risques : Utiliser des données historiques pour prédire les accidents potentiels en fonction de divers facteurs.
Analyse des causes : Identifier les causes sous-jacentes des accidents pour mieux cibler les interventions.
# Pour Plus d'Informations
Consultez l'analyse complète dans le Jupyter Notebook ou consultez cette présentation.

# Structure du Référentiel
├── Données <br> ├── images <br> ├── README.md <br> ├── Présenté par Saint Germain Emode.pdf <br> └──Bloc-notes Jupyter Python et Markdown.ipynb <br> ├── Analyseur de données.ipynb <br> 
