![[Chapitre 3.pdf]]
On décrit la relation entre deux variables dans un échantillon. Si on connait le score de la variable 1, on peut prédire le score de la variable 2. Si la mesure de relation est égale à 0, ça veut dire qu'il n'y a pas de relation entre deux variables.

- Je vais vous présenter une différence de moyenne entre les étudiants de psycho et les étudiants de Logo. Est-ce qu'il y a une relation entre les deux variables? 
- Est-ce qu'il y a une différence entre les gens qui ont beaucoup guindaillé et ceux qui n'ont pas beaucoup guindaillé?

## Décrire la relation entre deux variables nominales
On va beaucoup utiliser la table de contingence. Elle représente la distribution des fréquences d'une variable nominale pour chaque modalité d'une autre variable nominale.

**Exemple:**

| test   | Troubles anxieux | Aucun trouble anxieux | Total |
| ------ | ---------------- | --------------------- | ----- |
| Hommes | 1881             | 6669                  | 98912 |
| Femmes | 3817             | 7646                  | 12392 |
| Total  | 5698             | 14315                 | 20013 |

|        | Troubles anxieux | Aucun trouble anxieux | Total |
| ------ | ---------------- | --------------------- | ----- |
| Hommes | 22%              | 78%                   | 100%  |
| Femmes | 33,3%            | 66,7%                 | 100%  |

## Rapport de chances
Lorsqu'on a beaucoup de catégories et qu'on ne veut faire le rapport que de deux de ces catégories (combien de fois plus de risque qu'un se trouve dans cette catégorie de cette variable lorsqu'on se trouve dans la catégorie de cette autre variable? Quel risque de trouble anxieux lorsqu'on est femme?).
Les rapports de chances se calculent sur des fréquences, pas sur des pourcentages. Il faudra reconstruire le table de contingence avec les fréquences si on a des pourcentages.
On va calculer les chances pour al modalité de la variable indépendante "homme/femme".
Quels sont les risques d'avoir des troubles anxieux?
Chances pour les hommes d'être anxieux: 1881 / 6669 = 0,282 (ou 1 pour 3, 5)
Chances chez les femmes: 3817/7646 = 0,499 (ou 1 pour 2)
Rapport de chances: valeur plus grande divisée par valeur plus petite: 0,499/0,282 = 1,77
>Si je suis une femme, j'ai 1,77 fois plus de chances/risque qu'un homme d'avoir des troubles anxieux.

**Table de contingence**

|             | Malades | Non-Malades |     |
| ----------- | ------- | ----------- | --- |
| Exposés     | A       | B           | TE  |
| Non-exposés | C       | D           | TNE |
|             | TM      | TNM         | T   |


**Prévalence**
	Proportion d'individus atteints
	Nombre de personnes avec des symptômes / nombre de personnes **totales** $(A+C)/T$
	(165)/1580 = 0,1044 - 10,44% de personnes atteintes

**Risque absolu**
	**Prévalence** de la maladie dans l'un des deux groupes. Atteints/non-atteints.
	On divise le nombre de personnes malades par le nombre de personnes de la catégorie
	
	$\dfrac{A}{TE}$
	=> "Pourcentage de personnes malades chez les exposés"
	
	$\dfrac{C}{TNE}$
	=> "Pourcentage de personnes malades chez les non-exposés"

**Risque attribuable:**
	Sert à connaitre à quel point le fait d'être exposé augmente les chances d'être malade par rapport à ceux qui n'ont pas été exposés.
	=> "Pourcentage de personnes exposées et atteintes - Pourcentage de personnes non-exposées mais atteintes."
	$\dfrac{A}{TE} -  \dfrac{C}{TNE}$

**Risque relatif:**
	Rapport entre les risques absolus des deux groupes. Lorsqu'on est fumeur de cannabis, il y a deux fois plus de risque d'être atteint de risque psychotiques.
	$\dfrac{\dfrac{A}{TE}}{\dfrac{C}{TNE}}$
	Les personnes exposées ont X fois plus de chances d'être malades.

**Rapport de chances**
	Le rapport des chances qu'une maladie précise survienne chez un groupe exposé à un facteur de risque par rapport au groupe non-exposé.
	**Calcul croisé**
	$(A*D) / (B*C)$

**Quelle mesure choisir?**
	Rapport de chances > risque relatif
	Risque attribuable => lorsque je veux insister sur des faibles risques réels pour les maladies rares
	Risque relatif => lorsque je veux mettre en relation deux 

**Le diagramme de dispersion**
	/ : relation positive entre les variables
	\ : relation négative entre les variables
	- : absence de relation entre les variables
	Vi: en abscisse (X)
	VD en ordonnées (Y)
	Prédiction = $\hat{Y}$

**Covariance**
	Est-ce que les variables varient ensemble ? Reflète le degré auquel deux variables varient ensemble.
	Si on avait une relation, si on a un score élevé sur la première, on devrait s'attendre à trouver un score élevé sur la deuxième? Mais comment savoir ce qui est un score élevé? On compare à la moyenne.
	Une covariance égale à 0 indique qu'il n'y a pas de tendance entre les deux variables
	Une covariance négative, quand on est au dessus de la moyenne pour une des deux variables, on est en dessous de la moyenne pour l'autre (car on a fait $- fois +$.
	Exemple: X = 0,67
	Moyenne de tous les X = 0,65
	X est très près de la moyenne car $0,67 - 0,65 = 0,02$
	$COV_{XY} = \dfrac{\sum{XY} - \dfrac{\sum{X}\sum{Y}}{N}}{N-1}$


**Le coefficient de corrélation de Pearson ($r$)**
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


**Calcul de la droite de régression**
	On doit d'abord savoir ce qu'est une droite "bien ajustée". La droite la mieux ajustée est celle dont les points sont en moyenne le plus proches de la droite. 
	"La droite qui minimise les écarts/les résidus."
	La droite représente les valeurs qu'on utiliserait pour faire une prédiction. Si on a un point, la distance du point à la droite représente une "erreur de prédiction" (si on avait tenté de prédire).
	Etant donné qu'une droite bien ajustée est censée être parfaitement au milieu de l'ensemble des points, on peut considérer que si on faisait la moyenne des écarts des valeurs par rapport à la ligne ($Résidu (Y-\hat Y)$), on tomberait sur $0$.
	$\text{}$
	**Pour trouver la droite:**
	Rapport de la covariance sur la variance de la variable X. Quand j'avance de 1 sur la variable X, je me déplace de $b$ points sur l'axe y.
	
	$b=\dfrac{COV_{XY}}{(S_X)^2}$
		 Où $Sx$ est l'écart type des $X$, puis mis au carré
		 b est la coordonnée en Y quand X = 1
	$\text{}$
	$a=\bar Y - b\bar X$
		où $\bar Y$ est la moyenne des Y,
		$\bar{X}$ est la moyenne des X 
		$a$ est l'ordonnée à l'origine
	$a$ est le point de départ. "Quand on a 0 sur X, à quelle hauteur on va débuter?"
	$\text{}$
	Premier point de la droite (si a = 2 et b = 3.5):
	a = 2 => ${ x:0, y:2 }$
	Deuxième point de la droite:
	b = 3.5 => ${x: 1, y = 3.5}$ 
	$\text{}$
	**Pour prédire la position d'un score quand on a la droite**
	$\bar{Y} = bX + a$
		b: pente
		a: ordonnée à l'origine
		X: valeur du prédicteur





>[!tip]- ppt
>![[Chapitre 3.pdf#page=55]]


Quand on a l'équation d'une droite de prédiction, on peut prédire le score. Ne pas tenter de prédire des scores si ils ne sont pas représentés (on a calculé une droite entre 0,5 et 0,8, ne pas tenter de prédire un score de 0,1).

Une corrélation ne signifie pas de lien de cause à effet. (p95)
"Les gens obèses ont plus de machines à laver". Plus le pays est riche, plus les gens ont la capacité d'acheter une machine à laver mais aussi peuvent acheter plus à manger et devenir obèse.
"Plus il y a de lieux de culte dans une ville, plus il y a de la criminalité". La taille de la ville détermine les deux: plus la ville est grande, plus il y a de lieux de cultes. Plus la ville est grande, plus il y a de criminalité.
-> "Fausse corrélation" ou "corrélation absurde"

Comment représenter des statistiques bivariées entre deux variables?
- Texte (p98 - pdf)
- On peut aussi représenter sous forme de matrices de corrélation. Chaque cellule de la matrice représente les corrélations entre deux variables.



Les gens qui veulent faire peur utilisent souvent le risque relatif:
> une maladie rare: chez les gens non-exposés, une personne sur un million d'habitants
> chez les gens exposés à la pathologie, 3 sur un million
> Si on veut faire peur, on utilise le risque relatif: si vous avez été exposé au vaccin, vous aurez 3x plus de risque
> Risque attribuable: 2 chances de plus par million - beaucoup moins impressionnant.

