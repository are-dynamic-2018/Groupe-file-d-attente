# Groupe file d'attente
Membres du groupe :
- Frichet Pierre
- Druesne Vincent
- Carvalho Lorenzo
- Riwan d'Hervais


Notre objectif est de modéliser l'évolution de 2 files d'attente différentes selon le modèle représenté sur l'image ci-dessous.


### Les 2 modèles de file d'attente
![file](https://jpdconseil.com/wp-content/uploads/2014/11/jean-pierre-dube-file-dattente.png)
  
  
  
  
**1er bilan** : Aujourd'hui nous avons commencé le [notebook](https://github.com/are-dynamic-2018/Groupe-file-d-attente/blob/master/files-s%C3%A9par%C3%A9es.ipynb) (1er type de file d'attente et ses paramètres) et préciser la [problematique](https://github.com/are-dynamic-2018/Groupe-file-d-attente/blob/master/ARE%20DYNAMIC%20FILE%20D'ATTENTE.ipynb). Nous cherchons donc désormais à déterminer les paramètres optimaux afin de faire passer un maximum de client en minimum de temps. Nous commençerons donc par étudier les files d'attente unique à caisse multiple.
Nous prévoyons le codage d'un premier modèle simple simulant une simple file d'attente lors de la prochaine séance ainsi que la recherche sur internet de jeu de donnée.

**2e bilan** : Aujourd'hui nous avons commencé à essayer de représenter notre file d'attente à l'aide d'une [matrice](https://github.com/are-dynamic-2018/Groupe-file-d-attente/blob/65dd41a545de1b773d8a229dbb78a7d11c16bba7/ARE%20DYNAMIC%20code%201F_MC.ipynb). Pour la semaine prochaine nous voulons faire une première fonction sur l'évolution d'une file d'attente qui permettrait d'animer notre matrice.

**3e bilan** : Nous avons décidé d'abandonner pour l'instant la représentation matricielle et de consacrer cette séance à coder des fonctions qui représentent l'évolution des files d'attente selon deux modèles. Le premier est un modèle [périodique](https://github.com/are-dynamic-2018/Groupe-file-d-attente/blob/65cdaa6c2feaf38b54d40faff6ef9dc38ec48fab/ARE%201%20file%20caisse%20multiple%20.ipynb) tandis que le deuxième suit [la loi de Poisson](https://github.com/are-dynamic-2018/Groupe-file-d-attente/blob/2fd970d332f9dbaf3c2459b366ce35e004b8e0f1/poisson.ipynb). Nous avons également modélisé l'évolution en utilisant des graphiques selon différents paramètres d'entrée. Nous chercherons la semaine prochaine à améliorer ces premières versions de code.

**4e bilan** : Aujourd'hui nous décidons de partir de la fonction de poisson pour créer une [fonction](https://github.com/are-dynamic-2018/Groupe-file-d-attente/blob/05c0a5b87b46fe9e94e946501ad57a30839027f7/poisson%202.ipynb) avec des temps d'arrivée et des temps de départ qui ne dépendent pas des temps précédents. L'objectif pour la semaine prochaine sera de corriger les problèmes de cette fonction qui ne fonctionne pas correctement pour le moment.

**5e bilan** : Nous avons réussi à corriger les problèmes de la fonction précédente, qui nous retourne désormais les résultats attendus, nous en avons profiter pour ajouter [une représentation graphique](https://github.com/are-dynamic-2018/Groupe-file-d-attente/blob/f26a8153fafdfd22fb2f1c13c1112924536d58cf/poisson%202.ipynb). L'objectif de la prochaine séance sera de coder une fonction dans un cas différent, avec une seule file et plusieurs caisses.

**6e bilan** : Nous avons coder une [fonction](https://github.com/are-dynamic-2018/Groupe-file-d-attente/blob/cf8d6f4ecac15e335f024755532455e5702ba529/File%20unique%20.ipynb) s'inspirant de la précedente, à la différence que cette dernière a une seule file d'attente pour plusieurs caisses. Nous avons également modifié l'ancienne [fonction](https://github.com/are-dynamic-2018/Groupe-file-d-attente/blob/16864f75467c415df314d366f18db397dd412a7a/DATA.ipynb).



## Notebooks
- [présentation](https://github.com/are-dynamic-2018/Groupe-file-d-attente/blob/master/ARE%20DYNAMIC%20FILE%20D'ATTENTE.ipynb)
- [évolution périodique](https://github.com/are-dynamic-2018/Groupe-file-d-attente/blob/master/ARE%201%20file%20caisse%20multiple%20.ipynb)
- [première version de poisson, une caisse et une file](https://github.com/are-dynamic-2018/Groupe-file-d-attente/blob/master/poisson.ipynb)
- [deuxième version de poisson, plusieurs caisses et plusieurs files](https://github.com/are-dynamic-2018/Groupe-file-d-attente/blob/16864f75467c415df314d366f18db397dd412a7a/DATA.ipynb)
- [troisième version de poisson, plusieurs caisses et une file](https://github.com/are-dynamic-2018/Groupe-file-d-attente/blob/master/File%20unique%20.ipynb)

## Liens utiles
- [Théorie des files d'attente en pdf](https://www.gerad.ca/Sebastien.Le.Digabel/MTH2302D/14_files_attente.pdf)
- [Loi de Poisson](https://fr.wikipedia.org/wiki/Loi_de_Poisson)

