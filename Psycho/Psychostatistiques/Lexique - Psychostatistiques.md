
# Chapitre 1

**Unité d'observation**
	Une unité d'observation est l'élément du réel sur lequel porte l'observation. Selon la discipline scientifique, l'unité peut être des sujets humains, des plantes, des évènements, des objets, des sociétés ou toute autre chose pouvant être observée. ^69228e

**Etude de cas**
	Etude ne comportant qu'une seule unité d'observation. ^bdfd27

**Variable**
	Une variable est une propriété d'une unité d'observation (d'un sujet) qui peut prendre différentes valeurs. Il ne s'agit pas nécessairement de valeurs chiffrées.
	**Exemples:** 
	- gaucher, droitier, ambidextre
	- la timidité, l'âge, le QI, le genre, score de dépression etc. 
	- Habituellement dénommées par une majuscule - âge du troisième sujet - 25 ans ($A_3 = 25$)
<pre></pre>
	**Valeurs d'une variable:**
	Lorsque les variables sont des catégories ou des étiquettes, on les appellera les modalités.
		Exemple: gauche, droite, ambidextre sont les ***modalités*** de la variable.
	Lorsque les variables sont chiffrées, on parlera du ***score*** du sujet sur cette variable.
	Un seul score ou modalité peut être associé à une variable. Ceci peut mener à redéfinir une question pour évite qu'elle n'accepte plusieurs valeurs: 
	> "~Quel est votre métier?~"  => "Quel est votre métier principal?"
	^372bde

**Variables nominales**
	Variable désignant des catégories. Ce sont des étiquettes que l'on assigne aux unités d'observations (ie. personnes) et que ne prennent pas de valeurs numériques (sauf si l'on a associé l'étiquette à une valeur par besoin de simplification, celà ne changeant pas que c'est une étiquette).
	$\text{}$
	Exemples:
	- groupe contrôle, groupe expérimental
	- genre
	- diagnostic psychiatrique (schizophrène, ...) 
	$\text{}$
	**Attention** à ne pas confondre avec la variable ordinale qui présente une gradation entre les différentes valeurs de la variable.
	Exemple: classe sociale inférieure, classe moyenne, classe supérieure
	^c86465

**Variables ordinales**
	Les variables ordinales permettent de comparer deux valeurs entre elles et de les classer dans un ordre précis. Cependant, aucun information n'est donnée par ces étiquettes quant à une différence entre deux scores particuliers. "A quel point une valeur est plus grande, plus petite que la précédente/la suivante".
	$\text{}$
	Exemples: 
	- classe sociale inférieure, classe moyenne, classe supérieure
	- insatisfaisant, satisfaisant, distinction, grande distinction ^322114

**Variables métriques**
	Les variables métriques associent une mesure numérique à une unité d'observation. Elles permettent une gradation précise entre ces unités et donc de savoir précisément quel écart existe entre deux valeurs.
	$\text{}$
	Exemples:
	- taille d'un individu
	- temps de réalisation d'une tâche

**Variabilité d'échantillonnage**
	La moyenne variera d'un échantillon à l'autre.
	A-t-on suffisamment de preuves que pour tirer des conclusions au niveau d'une population plus grande?

**Statistiques inférentielles**
	Evaluer la probabilité que des données tirées sur quelques personnes au hasard représente une population.

**Ecart type ($S_X$)**
	

**Ecart moyen**
	

**Ecart absolu moyen**
	X = 7, 12, 5, 9 ....
	Moyenne = 9
	Ecarts = -2, 3, 
	Ecarts absolus = 2, 3
	La moyenne des écarts est: $\dfrac{7, 12, 5, 9, ...}{12}=\dfrac{40}{12} = 3,33$

**Variance**
	Ecarts que je mets au carré dont je fais la moyenne. "Ecart quadratique moyen" .Je prends un ensemble de données, pour chaque donnée je compare l'écart à la moyenne, Je mets les écarts au carré et j'en fais la moyenne.
	$\text{ }$
	**Variance de la population**: 
	$\sigma = \dfrac{\sum_{i=1}^N(X_i - \mu)^2}{N}$
	$\text{ }$
	$o^2 = \dfrac{\sum_{N}^{i=1}}{N}$


Mesure de tendance centrale +/- variabilité
Le temps moyen était de 590,90 +/- 11,5 (moyenne +/- écart-type)

**Covariance**
	Est-ce que les variables varient ensemble ? Reflète le degré auquel deux variables varient ensemble.
	Si on avait une relation, si on a un score élevé sur la première, on devrait s'attendre à trouver un score élevé sur la deuxième? Mais comment savoir ce qui est un score élevé? On compare à la moyenne.
	Une covariance égale à 0 indique qu'il n'y a pas de tendance entre les deux variables
	Une covariance négative, quand on est au dessus de la moyenne pour une des deux variables, on est en dessous de la moyenne pour l'autre (car on a fait $- fois +$.
	Exemple: X = 0,67
	Moyenne de tous les X = 0,65
	X est très près de la moyenne car $0,67 - 0,65 = 0,02$
	$COV_{XY} = \dfrac{\sum{XY} - \dfrac{\sum{X}\sum{Y}}{N}}{N-1}$
	$\text{}$
	
	$\text{}$
	**Coefficient de [[#^a76b07|corrélation]]**: 
	mesure de degré de relation entre deux variables.
	$r= \dfrac{cov_{XY}}{S_XS_Y}$
	$\text{}$
	où $S$ représente les écarts types pour X et Y.
	$\text{}$
	Problème: interpréter la covariance est compliqué car on ne sait pas ce que représente la valeur. Pour mieux savoir ce que ça représente, on transforme la covariance en **coefficient de corrélation (de Pearson)**. 

**La corrélation ($r$)**
	**Corrélation est tjrs entre -1 et +1**. Elle représente le degré de relation entre deux variables. Le signe de la corrélation indique le sens de la relation "corrélation positive/négative".
	Plus on s'approche de 1 ou -1 plus on a une corrélation entre deux variables. 1 ou -1 représente une relation parfaite entre 2 variables. Une corrélation de 0 représente une absence de relation - elles ne sont pas liées. On ne peut donc pas faire de prédiction à partir d'une variable.
	$\text{}$
	*En valeurs absolues, on considère que:*
	0,80 - 1 = Corrélation important, de grande taille
	0,5 - 0,8 = Corrélation de taille moyenne
	0,20 - 0,5 = Corrélation de petite taille
	0 - 0,2 = Corrélation négligeable
	$\text{}$
	**Exemple:**
	$r = 0,72$ quand on monte sur un, on monte sur l'autre.
	$r = -0,61$ quand on monte sur une variable, on descend sur l'autre. Corrélation de taille moyenne
	$r = 0,007$ relation négligeable, quasi absence de relation. ^a76b07


**Statistiques inférentielles**
	Evaluer la probabilité que des données tirées sur quelques personnes au hasard représente une population.


# Chapitre 2

# Chapitre 3
