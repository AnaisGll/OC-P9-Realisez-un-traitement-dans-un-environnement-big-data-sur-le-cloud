# OC-P9-Realisez-un-traitement-dans-un-environnement-big-data-sur-le-cloud

Une très jeune start-up de l'AgriTech, nommée "Fruits!", cherche à proposer des solutions innovantes pour la récolte des fruits.
La volonté de l’entreprise est de préserver la biodiversité des fruits en permettant des traitements spécifiques pour chaque espèce de fruits en développant des robots cueilleurs intelligents.
La start-up souhaite dans un premier temps se faire connaître en mettant à disposition du grand public une application mobile qui permettrait aux utilisateurs de prendre en photo un fruit et d'obtenir des informations sur ce fruit.

Pour la start-up, cette application permettrait de sensibiliser le grand public à la biodiversité des fruits et de mettre en place une première version du moteur de classification des images de fruits.
De plus, le développement de l’application mobile permettra de construire une première version de l'architecture Big Data nécessaire.
Votre collègue Paul vous indique l’existence d’un document, formalisé par un alternant qui vient de quitter l’entreprise. Il a testé une première approche dans un environnement Big Data AWS EMR, à partir d’un jeu de données constitué des images de fruits et des labels associés (en téléchargement direct à ce lien). Le notebook réalisé par l’alternant servira de point de départ pour construire une partie de la chaîne de traitement des données.

# Missions 

1) Préparer la chaîne de traitement Pyspark en local
2) Migrer la chaîne de traitement dans le cloud AWS :
      - Prenez connaissance des services AWS et identifiez les services pertinents pour migrer chaque étape de votre chaîne de traitement en local.
      - Mettez en place le cluster EMR pour distribuer les calculs dans le cloud et connectez-y votre notebook Cloud pour réaliser la chaîne de traitement jusqu’à la réduction de dimensions.

# Le jeu de données

Le jeu de données se compose de 90483 images correspondant réparties dans 131 dossiers correspondant chacun à un label de fruit

# Compétences évaluées

- Modéliser des données dans un environnement Big Data et en utilisant les outils du Cloud
- Réaliser des calculs distribués sur des données massives en utilisant les outils adaptés
- Sélectionner les outils du Cloud permettant de traiter et stocker des données Big Data

# Livrables
- Un notebook sur le cloud contenant les scripts en Pyspark exécutables (le preprocessing et une étape de réduction de dimension de type PCA).
- Un support de présentation pour la soutenance, présentant :
    - Les différentes briques d'architecture choisies sur le cloud ;
    - Leur rôle dans l’architecture Big Data ;
    - La démarche de mise en oeuvre de l’environnement Big Data (EMR ou Databricks) ;
    - Les étapes de la chaîne de traitement PySpark.
