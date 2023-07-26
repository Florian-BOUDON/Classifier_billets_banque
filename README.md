# Classifier de billets de banque

Ce projet de Machine Learning vise à classifier des billets de banque en vrai ou faux billet en utilisant des données géométriques fournies par la banque.    
Le projet est divisé en trois parties principales dans un notebook Jupyter.

### Partie 1 : Analyse Exploratoire des Données
Dans cette première partie, nous effectuerons une analyse exploratoire des données pour mieux comprendre le jeu de données.   
Les étapes de cette analyse incluront :   

- Analyse univariée
- Analyse multivariée 
- Traitement des données manquantes
  
### Partie 2 : Analyse en Composantes Principales (ACP)
Dans cette partie, nous effectuerons une Analyse en Composantes Principales (ACP) pour représenter les données géométriques en deux dimensions (2D).    
L'ACP permettra de réduire la dimensionnalité des données tout en préservant au mieux la variance, ce qui nous permet de visualiser les deux clusters de vrais et faux billets dans un plan 2D.


### Partie 3 : Comparaison des Classifieurs - Régression Logistique vs. K-Means
Dans la dernière partie du notebook, nous comparerons deux classifieurs : la Régression Logistique et K-Means.     
Nous utiliserons les métriques ROC (Receiver Operating Characteristic) et la matrice de confusion pour évaluer les performances de chaque classifieur.    
Nous déterminons ainsi celui qui offre les meilleures prédictions pour la classification des billets de banque en vrai ou faux.

### Prérequis
Environnement utilisé :

Python 3.x     
pandas     
numpy     
scikit-learn    
matplotlib     
seaborn     

### Structure des Fichiers

├── Classifier.ipynb
├── Billets_banque.csv
├── Présentation.ppt
└── README.md

Le dossier "data" contient le fichier CSV du jeu de données géométriques sur les billets de banque.
Le fichier notebook.ipynb est un cahier Jupyter contenant tout le code et les analyses du projet.
Le fichier README.md est le présent document, fournissant une description détaillée du projet.

### Conclusion
Ce projet de Machine Learning nous permet de classer les billets de banque en vrai ou faux en utilisant des données géométriques fournies par la banque.    
Grâce à l'analyse exploratoire, l'ACP et la comparaison des classifieurs, nous pourrons choisir le modèle qui offre les meilleures performances pour cette tâche de classification binaire.


Ce projet fait partie de la formation data-analyste de Openclassrooms & ENSAEE (certificat bac+4)
