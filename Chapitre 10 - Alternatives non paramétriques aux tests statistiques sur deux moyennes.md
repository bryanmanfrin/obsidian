
![[Chapitre 10.pdf]]

Les tests non-paramétriques n'ont pas de condition d'application de normalité. On peut les utiliser tout le temps. Les hypothèses ne portent pas sur les moyennes. Les groupes sont-ils différents les uns des autres? 

Normalité? Tests paramétriques
Pas de normalité? Tests non-paramétriques.

Ces tests non-paramétriques sont moins puissants, on a plus de mal à déterminer les différences entre deux groupes.

Comment déterminer si les données se répartissent normalement dans un échantillon?
On peut faire des tests d'hypothèse pour savoir les données sont normalement distribuées dans un échantillon. Mais c'est laborieux à la calculatrice donc on ne fera pas ça. Dans ce cours, on va juste estimer si il y a une **tendance centrale**.

Effet plancher et effet plafond: on présente des scores maximum, des scores minimums et un grand nombre de scores proches.

Effet de plafond dans un échantillon de filles: 20, 12, 10, 20, 20, 20, 19, 19
Comparez les résultats des garçons et des filles? => Problème de normalité chez les filles
=> Test de la somme des rangs sur Wilcoxon. Ces deux groupes sont indépendants ET ont u problème de normalité.

Les échantillons sont-ils pairés? Oui ou non

# **Test de Wilcoxon**
$H_0:$ Les deux échantillons proviennent de la même population

## Transformer en rangs
Pour traiter les ex-aequo: on fait la moyenne des rangs lorsque les valeurs correspondantes sont successives.

Valeurs de départ: 0 1 1 2 2
Classement ordre dans le rang: 1 2 3 4 5
Traitement des ex-aequo: 1 2,5 2,5 4,5 4,5

**Comment vérifier les calculs? Si on se trompe dans les rangs?**
1: Le Rang le plus élevé est = N (sauf si ex-aequo sur les dernières données)
2: La somme totale des rangs doit être égale à $\sum_{rangs} = N * (N+1)/2$


# Test de la somme des rangs pour effectifs égaux
Il y a une table de valeurs critiques dans une table $W$.

En test bilatéral
$W_S$ = la plus petite des sommes des deux rangs (entre les échantillons 1 et 2)

En test unilatéral
On doit réfléchir un peu: la somme des rangs auxquels on s'attend à avoir le score les plus bas (i.e. patients contrôles ont moins de symptomes => $W_S$ = somme des rangs des patients du groupe contrôle)
$W_S$ = la somme des rangs qui serait la plus petite selon HA

Attention: Dans les tests non-paramétriques on rejette à l'inverse de ce qu'on a fait jusqu'ici!!!
On rejette l'hypothèse nulle si la valeur observée est **plus petite ou égale** à la valeur critique.

Exemple de rejet d'hypothèse: Les patients cardiaques subissent davantage d'évènements stressants.

Pour annuler l'effet de valeurs extrêmes sur les rangs quand les N des deux groupes sont différents, on va utiliser une formule qui va nous donner ???

Calculer le $W_S '$: (donne le même résultat que si on avait calculé la somme des rangs dans l'ordre décroissant)
$W_S$ = Somme des rangs du plus petit groupe
$W_S '$ = $n_1 * (n_1 + n_2 + 1) - W_S$

Dans le test unilatéral, on va choisir $W_S$ ou $W_S'$ en fonction de (voir p30).

$W_S$ = Somme des rangs du plus petit des deux groupes
$W_S'$ = Somme des rangs de l'autre groupe


# Le test des rangs pour échantillons pairés de Wilcoxon
Toujours problème de normalité.
On compare un avant/après (donc pairé). Exemple: tension artérielle d'une même personne après un entrainement.

On procède de la même façon (on transforme en rang).Sauf que les valeurs à trier dans l'ordre croissant est la **valeur absolue** de la différence des pairs de valeurs (${avant} - {après}$).

## La statistique $T$
La statistique $T$ a également sa propre table. 
Test bilatéral: je prends le 

