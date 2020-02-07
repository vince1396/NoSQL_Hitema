# NoSQL_H3

## Sommaire 

<!-- TOC START min:2 max:4 link:true asterisk:true update:true -->
* [Introduction](#introduction)
  * [Qu’est ce que le NoSQL ?](#nosql-kesako)
  * [Pourquoi faire du NoSQL?](#pourquoi-nosql)
  * [Les outils](#pourquoi-bd)
  	* [Python](#python) 
  	* [Virtualenv](#virtualenv)
  	* [Jupyter](#jupyter)
  	* [Cloud Google](#gcp)
  	* [Docker](#docker)
* [Python et la science de données](#python-ds)
	* [Pourquoi python?](#pourquoi-python)
	* [Ce qu'il faut savoir](#kesako-python)  
		* [La puissance des librairies](#librairies)
		* [La POO](#poo) 
		* [Le web et les api](#web-api)
* [Révision bases de données relationnelles](#révision-bdd)
  * [Les bases de données relationnelles](#bdd)
    * [Définition](#définition-1)
    * [Le modèle entité-association](#ea-model)
* [Les bases de données non relationnelles](#bdd-non-relationnelle)
    * [Définition](#définition-2)
    * [Les différents frameworks](#frameworks)
    	* [Définition](#définition-3) 
    	* [Spark](#spark)
    	* [Elaticsearch](#elastic)
* [Projets](#projets)
<!-- TOC END -->


# Introduction 
## [Qu’est ce que le NoSQL ?](#nosql-kesako)


Les bases relationnelles ont été « inventées » par Edgar F. Codd en 1970. A l’époque, ce fut une approche révolutionnaire (modèle relationnel des données, algèbre de relations, sélections, projections, jointures, etc…). Oracle fut la première société à commercialiser un produit conforme à ce concept, dès 1977, avec le succès que l’on connait. Ces dernières années, plusieurs avis nuancés ont été émis concernant le modèle relationnel :

* Difficultés pour sauver et récupérer des grappes d’objets avec des programmes écrits en Java ou C#... (on parle de « mismatch d’impédance).
* Difficultés pour satisfaire les besoins des applications Web à grande échelle (nouveaux besoins métiers, nouvelles contraintes techniques).


Voici les 4 aspects qui ont motivé la nouvelle vague de bases NoSQL (Not Only SQL..) :
* Le VOLUME des données créées double tous les 2 ans. IDC estime qu’en 2020 le volume atteindra 44 Zettabytes (1 ZB = 1 milliards de terabytes).
* La VARIÉTÉ des types de données créées (Smartphones)
* La VÉLOCITÉ avec laquelle les données changent est également très importante (Internet of Things).
* La VÉRACITÉ des données et prédictions associées. 


## [Pourquoi faire du NoSQL?](#pourquoi-nosql)
La principale problématique qui a conduit à inventer NoSQL a été de solutionner le fait qu’une même base de données sur un site Web, pouvait être utilisée en même temps dans le monde entier par des millions d’utilisateurs ; la problématique  typique d’un Amazon… Ce que l’on cherche donc à réaliser avec NoSQL, c’est à réduire la complexité du langage de requêtes, à simplifier l’architecture de la base de données, et à trouver un moyen de stocker la base sur un maximum d’ordinateurs peu couteux en fonction des besoins. Ainsi, une base NoSQL est une base de données distribuée pour répartir la charge de calcul et de données dynamiquement, non relationnelle, préférant la gestion d’une table gigantesque à celle de nombreuses tables interdépendantes.


## [Les outils](#outils)

Durant ce cours nous allons utiliser plusieurs outils. Vous êtes en Master vous devez savoir installer des softs 😇

### [Python](#python)

Installer python3 & pip3 

### [Virtualenv](#virtualenv)

Installer virtualenv et expliquer pourquoi c'est bien de travailler en environement virtuel? 

### [Jupyter](#jupyter)

Installer jupyter et expliquer son utilité? 
 
#### Configuration 

```bash
jupyter notebook --generate-config
``` 

### [Google Cloud Plateforme](#gcp)

Inspirer vous du tuto ci-dessous afin de créer votre machine dans le cloud google. Par ailleurs, nous n'allons pas faire de deep learning dans ce cours vous n'avez donc pas vraiment besoin de GPU.  

[Cf tuto DL in GCP](https://medium.com/france-school-of-ai/installer-sa-première-machine-avec-gpu-dans-le-cloud-98798fdc4406)


### [Docker](#docker) 

Installer Docker et expliquer son utilité? 




