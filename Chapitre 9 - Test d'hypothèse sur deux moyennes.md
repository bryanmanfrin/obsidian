![[Chapitre 9.pdf]]


Le **score D** (score de différence) indique s'il y a une amélioration ou une détérioration. On peut ne pas avoir de différence (0).

Exemple d'hypothèse nulle dans les échantillons pairés: $\mu_D = 0$

On utilise la même formule que pour le chapitre différent (on mesure la différence entre 2 moyennes) sauf que les symboles sont différents pour représenter le contexte différent.

$t=\dfrac{\bar{D} - \mu_D}{\dfrac{S_D}{\sqrt{N}}}$

$\bar{D}$: -4,29
$S_D$ = 16,04 => C'est l'écart type des différences 
$N$ = 31
$dl$ = N - 1 = 30
Résultat de la formule: -1,49
=> Chercher la valeur dans la table $t$.

1,49 < 2,042 = on ne rejette pas $H_0$ (où 2,042 correspond au degré de liberté 30 dans la colonne pour 0,025 et non 0,05 car on est en bivarié)
**Nous ne pouvons pas affirmer que les scores évoluent.**

# Intervalle de confiance


Exemple de valeurs en appliquant la formule: –10,17 < μD < 1,59
=> Étant donné que 0 se trouve dans l'intervalle, on ne peut pas exclure que le score de développement mental n'évolue pas (reste stable) entre 6 et 24 mois.

Exemple
	Tester que les enfants ayant un poids réduit  ont une détérioration score de développement mental de 15 points.
	=> Echantillon pairés
	=> Scores de différence

Hypothèses: 
$H_0: \mu_D = -15$  (dans les hypothèses nulles, on a toujours un $=$)
$H_A: \mu_D <-15$ 


**Attention:** 
Garder le symbole de $\mu_D = -15$ lorsqu'on l'applique à la formule (double $-$ devient $+$).


# Tests sur deux moyennes pour échantillons non pairés

>[!warning] Quand les scores sont indépendants, calculer la différence entre deux colonnes n'a pas de sens!



## Variance hétérogène ou homogène?


## Variance homogène
La variabilité est considérée comme étant la même.

Exemple: est-ce que la mémoire est la même entre les jeunes et les personnes âgées.
VI: sujets jeunes ou âgés
VD: nombre de mots mémorisés.
	Ce sont des échantillons indépendants car les jeunes ne sont pas les vieux. Pour des échantillons dépendants, il aurait fallu mesurer les jeunes puis attendre 50 ans avant de les remesurer.

$H_0: \mu_1 - \mu_2 = 0$
$H_A: \mu_1 - \mu_2 \neq 0$

La moyenne de mots retenue par les jeunes et la moyenne des vieux est différente de 7,3 mots.

Pour l'hypothèse nulle, on s'attendrait à voir les deux graphs de distribution normale qui se superposent. Mais vu qu'on a 7.3 points de différence, elles ne se superposeront pas.

Variance dans la population ($S^2_P$)
On va utiliser les deux variances des deux groupes, les mettre ensemble pour en faire une moyenne et utiliser cette moyenne pour estimer la moyenne dans la population.

**Moyenne pondérée:**
Quand on n'a pas le même nombre de sujets dans les deux groupes, on va donner plus ou moins de poids à la moyenne d'un groupe selon qu'il a beaucoup ou peu de valeurs dans le groupe.


$\mu_1 - \mu_2$ dans la formule est ce qu'on a dans l'hypothèse nulle ($\mu1 - \mu_2 = 0$) => $0$.

La variance de la population va toujours se trouver quelque part entre les variances des deux groupes: $S^2_1 < S_P^2 < S^2_2$ 

