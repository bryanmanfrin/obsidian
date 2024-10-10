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
| Total  | 2397             | 23971                 |       |

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

## Prévalence
Proportion d'individus atteints
Nombre de personnes avec des symptômes / nombre de personnes totales (165 * 100)/1580 = 10,44% de personnes atteintes

Risque absolu:
Prévalence de la maladie dans l'un des deux groupes. Atteints/non-atteints.

Risque attribuable:
La différence de gens atteints de troubles psychotiques entre les fumeurs et les non-fumeurs est de 8,7%. Il y a donc un lien entre les deux variables. Etre fumeur ou non a un impact. 8,7% du risque est attribuable au fait de fumer du cannabis.

**Risque relatif:**
Rapport entre les risques absolus des deux groupes. Lorsqu'on est fumeur de cannabis, il y a deux fois plus de risque d'être atteint de risque psychotiques.

Les gens qui veulent faire peur utilisent souvent le risque relatif:
> une maladie rare: chez les gens non-exposés, une personne sur un million d'habitants
> chez les gens exposés à la pathologie, 3 sur un million
> Si on veut faire peur, on utilise le risque relatif: si vous avez été exposé au vaccin, vous aurez 3x plus de risque
> Risque attribuable: 2 chances de plus par million - beaucoup moins impressionnant.

Rapport de chances: 
Rapport entre les chances des deux groupes.

## Quelle mesure choisir?
Rapport de chances > risque relatif
Risque attribuable => lorsque je veux insister sur des faibles risques réels pour les maladies rares
Risque relatif => lorsque je veux mettre en relation deux 



## Calcul de la droite de régression
>[!tip]- ppt
>![[Chapitre 3.pdf#page=55]]

On doit d'abord savoir ce qu'est une droite "bien ajustée". La droite la mieux ajustée est celle dont les points sont en moyenne le plus proches de la droite. 
"La droite qui minimise les écarts/les résidus."
La droite représente les valeurs qu'on utiliserait pour faire une prédiction. Si on a un point, la distance du point à la droite représente une "erreur de prédiction" (si on avait tenté de prédire).
Etant donné qu'une droite bien ajustée est censée être parfaitement au milieu de l'ensemble des points, on peut considérer que si on faisait la moyenne des écarts des valeurs par rapport à la ligne ($Résidu (Y-\hat Y)$), on tomberait sur $0$.

**Pour trouver le droite:**

$b=\dfrac{COV_{XY}}{S^2_X}$
	rapport de la covariance sur la variance de la variable X. Quand j'avance de 1 sur la variable X, je me déplace de $b$ points sur l'axe y. 
$\text{}$
$a=\bar Y - b\bar X$
	où $\bar Y$ est la moyenne des Y et $\bar X est $ où $a$ est l'ordonnée à l'origine

$a$ est le point de départ. Quand on a 0 sur X, à quelle hauteur on va débuter?

Premier point de la droite (si a = 2 et b = 3.5):
a = 2 => ${ x:0, y:2 }$
Deuxième point de la droite:
b = 3.5 => ${x: 1, y = 3.5}$ 



>[!tip]- ppt
>![[Chapitre 3.pdf#page=55]]

