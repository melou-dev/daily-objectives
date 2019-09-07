# Objectifs journaliers

## Mercredi 28/08/2019


* [x] Javascript :
  * [x] Comprendre le fonctionnement des boucles `while` et `for` (https://javascript.info/while-for)
    * [x] Faire les 7 exercices
sauf le dernier exercise sur les nombres premiers (pas compris la solution non plus)

* [ ] Algo : 
  * [x] Ecrire en pseudocode le Merge Sort (création pure)
  * [ ] Faire valider son code par un "élève" qui joue le rôle de l'ordinateur

REGARDE cette liste de x nombres.
DIVISE en 2 bloques cette liste de nombres pour que les bloques A et B ait la même quantité de nombres,
SAUF si x n'est pas divible par 2, alors les 2 bloques auront une différence de 1 x et 1 x seulement.
PUIS répéter la DIVISION par 2 pour chaque nouveau bloque  JUSQU'A quil n'y ait qu'1 nombre par bloque.
ALORS
De gauche à droite, MERGE deux bloques en 1 pour former des bloques de 2 nombres.
COMPARE Les 2 nombres à l'intérieur de ces bloques, 
ET,
SWAPP les 2 nombres du couple,
SI le nombre de droite est plus petit que le nombre de gauche.
PUIS    
De Gauche à droite, FORME DES COUPLES DE BLOQUES.
Pour chaque couple,
REGARDE le 1er nombre, le plus à gauche, du 1er bloque et le 1er nombre, le plus à gauche, du 2eme bloque.
PUIS COMPARE les 2 nombres.
Le plus petit des 2 nombres QUITTE le bloque pour un nouveau nommé "bloque de classement", il se placera à droite des autres nombres déjà classés SI il y a un nombre SINON il est sans aucun doute le plus petit des nombres du couple de bloque.
REPETE l'action du 2eme REGARDE, jusqu'à ce qu'il n'y ait plus de nombre dans le couple de bloques et que tous les bloques à comparer soient vide.
ALORS REGARDE les nouveaux "bloques de classement" créés
PUIS
RECOMMENCE l'operation depuis FORME DES COUPLES DE BLOQUES" jusqu'à ce qu'il ne reste qu'un bloque, contenant tout les nombres classés du plus petit au plus grand.

  

* [x] CSS : 
  * [x] Découvrir l'approche `BEM` en CSS (https://en.bem.info/methodology/quick-start/)
    * [x] Comprendre l'intérêt de cette convention
