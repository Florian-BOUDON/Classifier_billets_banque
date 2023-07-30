# Classifier de billets de banque

Ce projet de machine learning vise à classer des billets de banque en vrai ou faux billet en utilisant des données géométriques fournies par la banque.    
Le projet est divisé en trois parties principales dans un notebook Jupyter.

### Partie 1 : analyse exploratoire des données
Dans cette première partie, nous effectuerons une analyse exploratoire des données pour mieux comprendre le jeu de données.   
Les étapes de cette analyse incluront :   

- Analyses univariées
- Analyses multivariées 
- Traitement des données manquantes
  
### Partie 2 : analyse en composantes principales (ACP)
Dans cette partie, nous effectuerons une aAnalyse en composantes principales (ACP) pour représenter les données géométriques en deux dimensions (2D).    
L'ACP permettra de réduire la dimensionnalité des données tout en préservant au mieux la variance, ce qui nous permet de visualiser les deux clusters de vrais et faux billets dans un plan 2D.


### Partie 3 : comparaison des classifiers - régression logistique vs. K-means
Dans la dernière partie du notebook, nous comparerons deux classifiers : la régression logistique et K-means.     
Nous utiliserons les métriques ROC (receiver operating characteristic) et la matrice de confusion pour évaluer les performances de chaque classifieur.    
Nous déterminons ainsi celui qui offre les meilleures prédictions pour le classement des billets de banque en vrai ou faux.

### Prérequis
Environnement utilisé :

Python 3.x     
pandas     
numpy     
scikit-learn    
matplotlib     
seaborn     

### Structure des fichiers

├── Classifier.ipynb     
├── Billets_banque.csv     
├── Présentation.ppt     
└── README.md      

Le dossier "data" contient le fichier CSV du jeu de données géométriques sur les billets de banque.
Le fichier notebook.ipynb est un cahier jupyter contenant tout le code et les analyses du projet.
Le fichier README.md est le présent document, fournissant une description détaillée du projet.
Le fichier présentation est un power point présentant les étapes et les résultats du modèle en 20 slides 

### Conclusion
Ce projet de machine learning nous permet de classer les billets de banque en vrai ou faux en utilisant des données géométriques fournies par la banque.    
Grâce à l'analyse exploratoire, l'ACP et la comparaison des classifieurs, nous pourrons choisir le modèle qui offre les meilleures performances pour cette tâche de classification binaire.

*******
Ce projet fait partie de la formation data-analyst de l'ENSAE Paris & Openclassrooms (certificat bac+4).
