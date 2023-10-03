
# Prédiction du diabète
Ce travail d’étude traite le sujet de la prédiction du diabète. 

Le diabète est une maladie chronique qui affecte la façon dont le corps humain régule sa glycémie (sucre dans le sang).

Dans le cadre de ce projet, l'objectif principal était de classifier si une personne est atteinte de diabète ou non en utilisant un ensemble de données médicales. Le jeu de données qu'on a utilisé se compose de plusieurs variables médicales indépendantes et d'une variable de résultat dépendante. Les variables indépendantes comprennent des informations telles que le nombre de grossesses, la glycémie, la pression artérielle, l'épaisseur de la peau, l'insuline, l'indice de masse corporelle (IMC), le facteur de pédigrée du diabète et l'âge. La variable de résultat prend des valeurs de 1 ou 0, indiquant si une personne est atteinte de diabète (1) ou non (0).

Les algorithmes utilisés dans ce projet sont: L'algorithme KNN (K plus proches voisins, Support vector machine, Decision tree et un réseau de neurone). La technique de GridSearch qui permet de regler les hyperparamètres des modèles a été utilisé, cette technique utilise différentes combinaisons de tous les hyperparamètres spécifiés et de leurs valeurs, calcule les performances pour chaque combinaison et sélectionne la meilleure valeur pour les hyperparamètres.

## 1. Prérequis
Ce projet nécessite les packages suivants pour fonctionner :
* [Python 3](https://www.python.org/)
* [Pandas](https://pandas.pydata.org/)
* [NumPy](https://numpy.org/)
* [MatPlotLib](https://matplotlib.org/)
* [Sklearn](https://scikit-learn.org/stable/)
* [Opencv](https://opencv.org/)
* [Keras](https://keras.io/)
* [Seaborn](https://seaborn.pydata.org/)

## 2. Fichiers
Ce projet est composé des fichiers suivants:
* **Diabetes Prediction.ipynb ->** Fichier principal qui contient le code.
* Le jeu de données contenu dans le fichier **diabetes.csv** comprend 768 enregistrements et est composé de 9 colonnes.

## 3. Execution du projet
1. Pour mettre en marche ce projet, téléchargez la base de données **Diabetes.csv**
2. Importez et executez le fichier **Diabetes Prediction.ipynb** dans Google Colab. Cela vous permettra de l'exécuter en utilisant le processeur graphique de colab, réduisant ainsi les temps d'apprentissage. 

## 4. Références
* Mujumdar, A., & Vaidehi, V. (2019). Diabetes prediction using machine learning algorithms. Procedia Computer Science, 165, 292-299.

* Hasan, M. K., Alam, M. A., Das, D., Hossain, E., & Hasan, M. (2020). Diabetes prediction using ensembling of different machine learning classifiers. IEEE Access, 8, 76516-76531.

* https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database




