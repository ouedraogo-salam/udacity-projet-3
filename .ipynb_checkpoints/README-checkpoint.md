# **<center><span style="color:#fd7b12;">Part I - Prosper Loan Data Exploration</span></center>**
## by OUEDRAOGO Salam

## Dataset

>Prosper est une société basée à San Francisco, en Californie, dans le secteur des prêts à des particuliers en ligne. Cet ensemble de données est extrais des données de Prosper. Il est constitué d’environ 113,937 prêts et 81 variables, y compris le montant du prêt, le taux de l'emprunteur (ou taux d'intérêt), le statut actuel du prêt, le revenu de l'emprunteur, et bien d'autres. Les données sont téléchargeable en utilisant le [lien](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv). La [documentation](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) du dataset permet de mieux comprendre chacun de ses variables.


## Summary of Findings

> L’analyse de l’ensemble de données sur le prêt m’a permis de comprendre beaucoup de chose dans le domaine de prêts. En effet, durant l’analyse j’ai découvert qu’il existe une importante relation entre la variable statut de prêts et les variables traitant des sources de revenus, la ville d’habitation, la durée du prêt (12, 36 et 60 mois), le statuts d’emploie ainsi que bien d’autre. Suite aux reformes de 2009 avec l’ajout du score de prosper, le nombre de dettes non payés à considérablement baisser car maintenant, les investisseurs ont des outils leurs permettant d’évaluer la solvabilité d’un emprunteur avant le financement du prêt. Également, si le montant du prêt est important, il est nécessaire de prendre un prêt de longue durée car cela réduira la somme à rembourser chaque mois jusqu’au payement complet du prêts.  
En dehors de la variable cible, l’exploration des relations entre les différentes variables nous apprends que la plupart des personnes qui ont une source de revenues important gagne une importante somme d’argent pour le financement de son prêt. La plupart des personnes qui n’ont pas de document justificatif sont dans l’auto emploie. Plus les gens qui possède une maison en leur nom ont généralement une source de revenue assez consistant.



## Key Insights for Presentation

> Pour la présentation, je vais beaucoup m’appesantir sur l’effet des sources de revenue sur la capacité de remboursement du prêt. Pour ce faire, je vais d’abord introduire les différentes sources de revenue avec des visualisation.  
> 
> Puis Je vais utiliser les diagrammes en barres pour montrer la relation entre la source de revenues et le paiement des prêts ainsi que la durée de remboursement. 