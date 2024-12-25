On va faire des tests d'hypothèses sur le contenu du chapitre 3.
![[Chapitre 11.pdf]]
On mesure 2 variables (continues ou ordinales) et on en mesure la corrélation.
==ATTENTION: Une corrélation est comprise entre -1 et 1!!==
==0: corrélation nulle
1: Corrélation totale==

**Prédiction**: de cb d'unités la variable indépendante va-t-elle changer quand on change d'une unité la variable dépendante? 
- [ ] TODO: annoter l'arbre décisionnel pour ajouter l'exemple de prédiction ?

**Dans l'échantillon**
$r$ = coefficient de Pearson
$b$ = ordonnée à l'origine de la pente de régression
$a$ = pente de régression

**Dans la population**
$\rho$ = (rho) = coefficient de Pearson
$\beta$ = ordonnée à l'origine de la pente de régression
$\alpha$ = pente de régression


Tests statistiques sur les corrélations 
VS
Tests statistiques sur la pente de régression

# Tests statistiques sur les corrélations 
Est-ce qu'il y a une correlation entre 2 variables? 

*"Est-ce que la corrélation est nulle?"*
$H_0 = 0$
$H_0 \neq 0$ (test bilatéral)

*"Est-ce que la corrélation est positive"*
$H_0 = 0$
$H_0 \gt 0$ (test unilatéral)

*"Est-ce que la corrélation est négative"*
$H_0 = 0$
$H_0 \lt 0$ (test unilatéral)

*"Est-ce que la corrélation est différente de 0,5?"*
$H_0 = 0,5$
$H_0 \neq 0,5$


## Tester que $\rho$ est nul (coefficient de Pearson = 0) pour obtenir le $t$ du test de Student.
$t_{obs}=\dfrac{r}{S_X}$
$dl = N-2$

Exemple: 
*"Y a-t-il une relation positive"*
$H_0 = 0$
$H_0 \gt 0$ (test unilatéral)
$t_{obs}=\dfrac{r}{S_X} = \dfrac{0,72}{0,26} = 2,77$
$t_{0,05} = 1,1895$ (unilatéral et 7 dl)
$2,77 > 1,895$ -> rejet de l'hypothèse nulle -> Il y a donc  une corrélation positive

## Tester que $\rho$ est égal à une valeur particulière (coefficient de Pearson = X)
Dans le test $t$, on a besoin d'une distribution normale. Or si rho n'est pas égal à 0, on sait que la distribution ne sera pas normale.
Il faut passer de $r$ à $r'$ et de $\rho$ à $\rho'$en utilisant la table à la fin du syllabus. La transformation utilise le logarithme népérien.
$\rho'$: valeur attendue dans l'hypothèse nulle

On veut passer de la statistiques $t$ à la statistique $Z$

Exemple: 
*"Corrélation entre X et Y est-elle inférieure à 0,9?"* -> Test $Z$ sur une corrélation
$H_0 = 0$
$H_0 \lt 0,9$ (test unilatéral)

$r = 0,72$ -> $r' = 0,908$ 
$\rho = 0,9 -> \rho'=1,472$ 

$Z = \drfac{0,908-1,472}{\sqrt{\dfrac{1}{6}}}$ = 0,0838

Faire le test d'hypothèse sur Z classique:
$0,0838 > 0,05$ => Je ne rejette pas l'hypothèse nulle

## Intervalle de confiance sur les corrélations
On fait d'abord les intervalles de confiance sur les valeurs primes (').

$IC(P') = r' \pm Z_{a/2} * \dfrac{1}{\sqrt{N-3}}$
Ici, on obtient l'intervalle de confiance sur les valeurs transformées (primes). Il faut les convertir pour passer de prime à la valeur de base => Dans la table des primes, on cherche la valeur la plus proche pour trouver la valeur de base et ce, pour chacune des deux bornes de l'intervalle.
# Tests statistiques sur la pente de régression (prédictions)
Si la pente est horizontale, on est dans la situation où il n'y a pas de corrélation. Si la corrélation est de 0, $\beta$ sera = 0 aussi.

Les tests d'hypothèse portent sur la pente de régression $b$

$S_b = \dfrac{SY.X}{Sx\sqrt{N-1}}$

Sx: écart type de la variable X (variable indépendante)
Identifier la VD et la VI en utilisant "cause (VI)", "conséquence (VD)"

*Augmentation de 20% de la pente pour chaque point de plus sur l'indice d'inégalité des revenus?*
$H_0: \beta = 20$
$H_A: \beta > 20$

$dl = N-2$
$SY.X$ = 5.00 (voir chapitre 3)

Calculer le 




# Conditions d'application de la régression
## Homogénéité de la 