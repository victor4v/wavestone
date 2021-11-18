## Présentation

Ce site a pour but de montrer quelques outils permettant d'exploiter des données provenant de l'INSEE et décrivant mobilité France.

  * Manipulation de données (csv, xlsx) avec Pandas.
  * Extraction de données avec Requests et Selenium depuis le site de l'INSEE.
  * Construction d'indicateurs et Macros.
  * Développement d'ouils de visualisation.
  
Lien vers [le code et les données](https://github.com/victor4v/wavestone.git).

## Liens
[Integrate interactive Python plot on a website](https://www.freecodecamp.org/news/how-to-embed-interactive-python-visualizations-on-your-website-with-python-and-matplotlib/)

## Quelques Macros..

On s'applique à représenter quelques données. Par exemple dans les communes à faible densité, la distribution du nombre de voitures ou celle du mode de transport. 

![La distribution du nombre de voitures](./images/low%20density/('VOITs'%2C%20False).jpg)
![La distribution du mode de transport](./images/low%20density/('TRANSs'%2C%20False).jpg)

Ou bien les même données au regard de l'indice de densité (de 1 à 4, du fort au faible).

![La distribution du nombre de voitures par indice de densité](./images/by_density/12v34('VOIT'%2C%20False).jpg)
![La distribution du  mode de transport par indice de densité](./images/by_density/12v34('TRANS'%2C%20False).jpg)

