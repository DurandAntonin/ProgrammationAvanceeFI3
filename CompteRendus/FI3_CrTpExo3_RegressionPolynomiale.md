_Antonin Durand_ <br>
_FI3_

<h1 style='text-align:left; color:#fd441c'> Exercie 3 : régression polynômiale </h1>

L'objectif de cet exercice est d'utiliser un modèle de régression polynômiale pour prédire les étiquettes d'un dataset aléatoire.

La représentation graphique du dataset nous indique qu'il faut mieux utiliser un modèle de régression polynômiale, notée $f(x) = ax^2 + bx + c$, comme dans l'exercice précédent.

On utilise les mêmes algo que pour une régression linéaire simple, ne modifiant seulement les matrices $X$ et $\theta$, où $\theta$ est la matrice des paramètres à optimiser de $f$.
Après, il suffit d'appliquer notre modèle en utilisant $X$ et $\theta$ optimisés, pour obtenir les prédictions.

<h2 style='text-align:left; color:#fd441c'> Conclusion </h1>

En représentant graphiquement les prédictions du modèle, on constate que ces dernières sont fidèles aux étiquettes à prédire de notre dataset.
Pour conclure, on constate que le modèle de régression polynômiale est un bon modèle pour prédir ce type de données avec 1 seule feature.
On peut aussi souligner le fait qu'il soit facile de passer d'un modèle à un autre, car on garder les mêmes algorithmes utilisés dans un modèle d'apprentissage supervisé.