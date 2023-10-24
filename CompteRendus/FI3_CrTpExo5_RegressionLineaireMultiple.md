_Antonin Durand_ <br>
_FI3_

<h1 style='text-align:left; color:#fd441c'> Exercie 5 : régression linéaire multiple </h1>

L'objectif de cet exercice est d'utiliser un modèle de régression linéaire multiple pour prédire la qualité de vins en utilisant ses caractéristiques physiques et chimiques. 

Chaque échantillon, i.e chaque vin possède 11 features, par conséquent, le modèle à utiliser pour prédire la qualité du vin.

On utilise les mêmes algo que dans l'exercie précédent, ne modifiant seulement les matrices $X$ et $\theta$, où $\theta$ est la matrice des paramètres à optimiser de $f$.
Après, il suffit d'appliquer notre modèle en utilisant $X$ et $\theta$ optimisés, pour obtenir les prédictions.

On constate que le modèle ne prédit pas très bien la qualité du vin d'après les features. En effet, on constate que les labels appartiennent à un ensemble fini de valeurs, à savoir [3,4,5,6,7,8,9,10]. Pour améliorer l'efficacité de la prédiction de la qualité d'un vin, on pourrait imaginer utiliser un modèle de classification au lieu d'un modèle de régression.
J'ai ainsi utilisé l'algorithme des KNN (K-nearest neighbors). Cela a pour conséquence d'améliorer le modèle qui passe à 45% d'exactitudes.

<h2 style='text-align:left; color:#fd441c'> Conclusion </h1>

Dans cette exercice, le modèle de régression linéaire multiple n'était pas le plus approprié car les labels appartenaient plus à un ensemble discret, plutôt qu'à un ensemble réel.