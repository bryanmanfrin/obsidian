
Une probabilité est comprise entre 0 et 1.
![[psychostate - Chapitre 5.pdf]]

## La probabilité additive (**OU**)
> Pour un ensemble d'évènements mutuellement exclusifs (**OU**), la probabilité d'occurrence d'un évènement ou de l'autre est égale à la somme de leurs probabilités séparées.
> Pour un ensemble d'évènements exhaustifs, la probabilité de l'ensemble est égale à 1.
> 
> **Exemple d'évènements mutuellement exclusifs**
> Probabilité d'un 5 OU d'un 6 sur un dé = P(5) + P(6) = 1/6 + 1/6 = 0,17 + 0,17 = 0,33


## La probabilité multiplicative (**ET**)
> La probabilité d'occurrence conjointe de deux ou plusieurs évènements indépendants est égale au produit de leurs probabilités individuelles.
> Pile ou face:
> Quelle est la probabilité d'obtenir 2 pile sur 2 pièces?
> 0,5 x 0,5 = 0,25 (1 chance sur 4)
> Quelle est la probabilité d'avoir 5 filles sur 5 naissances ? 0,5 x 0,5 x 0,5 x 0,5 x 0,5 = 0,03125


## Exemples d'exercices
**Quelle est la probabilité qu'une famille avec deux enfants ait deux filles ou deux garçons?**
=> FF OU GG
FF = 0,25
GG = 0,25
FF OU GG = 0,25 + 0,25

(autre représentation visuelle)
**FF**
**GG**
GF
FG

**Quelle est la probabilité qu'une famille avec deux enfants ait deux garçons ou une fille?**
(utilisation de probabilité binomiale qui ne sera pas vue au cours cette année).


## Probabilité conjointe
La probabilité de co-occurrence de deux ou plusieurs évènements (probabilité d'avoir Pile et Face).
Si deux évènements sont indépendants, leur probabilité d'occurrence conjointe peut être calculée à l'aide de la loi multiplicative.


## Probabilité conditionnelle
Quelle est la probabilité de tirer Pile si j'ai tiré Face
Une urne contient 6 boules blanches et 2 boules noires? Quelle probabilité de tirer une noire? **2/8**
Probabilité de "A" si "B"

Quelle est la probabilité de tirer une boule noire au second tirage si j'ai retiré une blanche au premier tirage? 
=> On va calculer la probabilité de tirer une noire parmi 5 blanches et 2 noires? 2/7 = 0,29
En retirant la bille blanche de la condition, j'ai rendu les évènements indépendants. Je peux donc juste faire 2/7.

Probabilité d'obtenir un pile si j'ai déjà obtenu pile précédemment? 
=> Ne change rien car les évènements sont indépendants entre eux $(\bar{A} | \bar B) =\bar A$


Exercice des assureurs et des ceintures:
Il y a un lien entre le fait de porter une ceinture et d'avoir des enfants.
Quelle est la probabilité qu'une personne prise au hasard dans l'échantillon porte la ceinture?
Le prof pour y répondre, rend tout conditionnel en reformulant =>
Quelle est la probabilité de porter la ceinture quand on ne sait pas si la personne a des enfants ou non?
P(C) = 0,30 (30 personnes sur 100 portent la ceinture)

Quelle probabilité de porter la ceinture si j'ai des enfants? Je cache tout ce qui n'est pas sous la condition (je cache: "si j'ai des enfants", "le total")

FAUX:
Enfants (0,2) + ceinture (P(C) = 0.3)? 
P(E, C) = 0,3 x 0,2 = 0,06 = ERREUR, on ne peut pas car on pense que ce sont des évènements dépendants (les parents portent plus la ceinture)

Quelle est la probabilité de porter la ceinture étant donné que j'ai des enfants
P(C | E) = 15/20 = 0,75 = Ca c'est ok


## Connaître la distribution d’une population informe sur la probabilité de scores tirés aléatoirement

Dans cet échantillon, quelle est la probabilité de tirer au hasard une personne mariée? 0,38
Divorcé? 0,15


## Probabilité pour les variables métriques
Question absurde (la réponse est **0**) "Quelle est la probabilité d'obtenir un QI de 112? => **0**" 
=> On ne peut pas calculer de probabilités sur une valeur provenant d'un ensemble de variables métriques, on va plutôt calculer la probabilité pour un intervalle. #tuyau

## Probabilités pour les variables normalement distribuées
50% des gens ont un score supérieur à la moyenne, 50% inférieur à la moyenne.
P(>50) = 0,5
P(<50) = 0,5
On nous donne une table de correspondance

La probabilité va varier en fonction de sigma et mu
$\mu=100 \text{ et } \sigma=15$

Problème des tables des probabilités dans la distribution normale=> chaque graph est différent en fonction du sigma et du mu donc la table sera différente.
Au lieu d'avoir un graph par variante de table, on va ajuster la donnée venant de la table de distribution normale en fonction.
Le Z score donne une moyenne de 0 et un écart type de 1. Il peut être négatif.
$Z = \dfrac{X - \mu}{\sigma}$

La probabilité d'avoir un P(Z < -1) = P(Z > 1) car la distribution est symétrique.
Il y aura toujours une question sur un intervalle de confiance à l'examen  (p.75) #tuyau 


Exercice parrainage:

5.3:


