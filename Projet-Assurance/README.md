#  Analyse des coûts d'assurance médicale (USA)

##  Présentation du projet
Ce projet analyse un dataset réel d'assurance santé pour identifier les facteurs qui influencent le montant des primes annuelles. Il s'agit d'un outil d'aide à la décision pour comprendre les risques actuariels.

##  Méthodologie Statistique
Pour ce projet, j'ai appliqué une approche rigoureuse :
- **Analyse Exploratoire (EDA) :** Visualisation des distributions (âge, IMC, charges).
- **Tests d'Hypothèses :** Utilisation de tests **t** et **ANOVA** pour valider l'impact significatif du tabagisme.
- **Modélisation :** Construction d'un modèle de **Régression Linéaire Multiple**.

##  Résultats Obtenus
- **Performance :** Le modèle explique environ **75 % de la variance** des coûts.
- **Découverte majeure :** Le tabagisme combiné à un IMC élevé multiplie drastiquement les frais médicaux.
- **Précision :** Les tests post-hoc ont permis d'affiner les segments de population les plus coûteux.

##  Outils utilisés
- **Langage :** Python
- **Librairies :** Pandas (Data), Matplotlib/Seaborn (Visualisation), Statsmodels (Statistiques).
