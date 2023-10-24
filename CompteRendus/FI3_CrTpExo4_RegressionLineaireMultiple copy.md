_Antonin Durand_ <br>
_FI3_

<h1 style='text-align:left; color:#fd441c'> Exercie 4 : régression linéaire multiple </h1>

L'objectif de cet exercice est d'utiliser un modèle de régression linéaire multiple pour prédire les étiquettes d'un dataset aléatoire.
Nous avons maintenant 2 features pour chaque échantillon du dataset, la représentation graphique des données se fait ainsi en 3 dimensions.


La représentation graphique du dataset et le nombre de features nous indiquent qu'il faut utiliser un modèle de régression linéaire simple, notée $f(x) = ax1 + bx2 + 1$, où a et b sont les paramètres à optimiser, et x1 et x2 sont les features de l'échantillon associé au label y.

On utilise les mêmes algo que pour une régression linéaire simple et régression polynômiale, ne modifiant seulement les matrices $X$ et $\theta$, où $\theta$ est la matrice des paramètres à optimiser de $f$.
Après, il suffit d'appliquer notre modèle en utilisant $X$ et $\theta$ optimisés, pour obtenir les prédictions.

<h2 style='text-align:left; color:#fd441c'> Conclusion </h1>

En représentant graphiquement les prédictions du modèle, on constate que ces dernières sont fidèles aux étiquettes à prédire de notre dataset.