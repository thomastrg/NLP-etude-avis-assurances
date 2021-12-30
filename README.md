# NLP : étude d'un dataset d'avis d'assurances

Le dataset sur lequel nous sommes amenés à travailler dans ce projet contient 24 105 lignes et 6 colonnes. Chaque ligne représente un avis d'un assuré rédigé suite à un sinistre impliquant l'intervention d'une assurance. Parmi les colonnes retrouvées nous avons :
    - date : c'est la date de publication de l'avis et la période de la rédaction de l'avis  
    - note : nombre d'étoiles données par l'assuré (à prédire pour une tâche supervisée)  
    - auteur : l'id de l'assuré  
    - avis : l'avis de l'assuré  
    - assureur : le nom de l'assurance  
    - produit : type du bien assuré  


Ce projet est composé de 3 parties autour desquelles s'articulent l'avancement de l'étude de cette base de données.

Nous distinguons plusieurs grandes étapes pour mener à bien ce projet, tout d'abord un travail de \textbf{data cleaning et de data  processing} qui sera le travail le plus complexe et conséquent étant donné que la data est désordonnée notamment au niveau de la date et des avis. 

Puis nous devrons proposer des approches de \textbf{modélisation} non supervisée notamment en clustering des avis selon toutes les informations de chaque avis que nous avons à notre disposition. 

Enfin nous devrons proposer une approche de prédiction supervisée dans le but de prédire le nombre d'étoiles d'un avis en entraînant sur le dataset d'entraînement selon les autres features. 


Vous pourrez retrouver le dataset train sur le lien suivant : [https://raw.githubusercontent.com/thomastrg/NLP_insurance_project/main/avisassurance_train.csv](https://raw.githubusercontent.com/thomastrg/NLP_insurance_project/main/avisassurance_train.csv)
<br>


## Le projet rassemble les tâches de :  
* Exploration et visualisation des données : affichez les corrélations entre les données et la cible sur le Jupyter Notebook
* Traitement des données avec sélection de l'importance des features
* Modélisation et mise au point d'algorithmes d'apprentissage automatique et non supervisé gra^ce au word embedding sur Jupyter Notebook
 
## You will find in this repositery :   
* A [LaTeX report of the study]()
* The [Jupyter Notebook]()

<br> 

## Conclusion : 

