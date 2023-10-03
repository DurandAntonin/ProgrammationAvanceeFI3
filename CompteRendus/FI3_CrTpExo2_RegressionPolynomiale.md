_Antonin Durand_ <br>
_FI3_

<h1 style='text-align:left; color:#fd441c'> Exercie 2 : régression linéaire et polynômiale </h1>

L'objectif de cet exercice est de montrer qu'il n'est pas toujours viable d'utilier un modèle de régression linéaire pour tous les dataset.

Nous avons un dataset, contenant 1 colonne contenant le **taux DDT**, et une autre contenant **l'âge des Brochets**.
L'objectif est de prédir l'âge des Brochets en fonction du taux DDT.

Si on représente graphiquement ces données à l'aide d'un nuage de points, nous nous apercevons que les données ne décrivent pas une droite, mais plutôt une partie d'une parabole.

Si on utilise un modèle de **régression linéaire**, d'équation $f(x) = ax + b$, on constate que la droite affine symbolisant notre modèle, n'est pas très approprié pour ce cas-ci.

Ainsi, il faudrait un modèle, qui puisse mieux prédire l'âge des Brochets. Pour cela, nous utilisons un modèle de régression polynômiale, d'équation $f(x) = ax^2 + bx + c$. <br>
Pour pouvoir utiliser ce modèle, il suffit seulement d'ajouter dans la matrice $X$, une colonne pour les $x^2$, et un nouveau paramètre $c$ dans la matrice $\theta$, matrice des paramètres de $f$ à optimiser. <br>
Du côté de l'algorithmie, on peut utiliser les mêmes fonction **cout** et **Descente de gradients**, d'une régression linéaire. <br>
Après avoir optimisé les paramètres de $f$, et prédit les étiquettes du modèle, on constate que ces prédictions sont plus fidèles à la réalité, que celles d'un modèle linéaire.

<h2 style='text-align:left; color:#fd441c'> Conclusion </h1>

Pour conclure, il faut bien choisir le modèle de machine learning pour qu'il puisse prédire au mieux les étiquettes de notre dataset.<br>
Pour l'instant, si notre dataset contient 1 seule feature et si la représentation graphique de ce dernier symbolise une droite, on peut utiliser un modèle de régression linéaire simple. <br>
Sinon, il faut utiliser un modèle de régression polynômiale si la représentation graphique du dataset est plutôt une parabole.