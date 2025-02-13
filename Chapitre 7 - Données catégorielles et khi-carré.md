
![[stat-Chapitre 7.pdf]]
# Test Khi carré d'ajustement

La valeur du khi carré mesure le degré auquel les observations sur l'échantillon ne correspondent pas à l'hypothèse nulle attendue.
Plus la différence les observés et attendus, plus la valeur du khi carré est grande => Plus le Khi carré est grand, plus il y a une différence entre ce qui est observé dans l'échantillon et ce qui est attendu.

Porte sur une seule variable nominale. On teste si une certaine répartition de pourcentage s'applique sur la totalité de la population. A partir de 100 étudiants de l'université, on peut prendre va VI a réussi/n'a pas réussi. A partir de 100 étudiants, y a t-il plus de 50% des étudiants qui réussissent dans la population?
=> A partir d'un échantillon, puis-je conclure quelque chose sur la population?

>[!tip] Pourcentage implicite présent dans la question
  Les hommes sont-ils plus représentés dans les professions médicales? 50-50%
  Pas de VI + Variables nominale => Test Khi carré (voir arbre décisionnel)

  
Nombre de personnes dans le personnel médical
Echantillon: (ne pas conclure le pourcentage - erreur d'échantillonnage).

| M   | F   | Total |
| --- | --- | ----- |
| 65  | 35  | 100   |

Si on constitue des groupes d'échantillons au hasard, on aura parfois plus de femmes que d'hommes ou inversement. Plus l'échantillon est petit, plus les probabilités d'avoir une répartition inégale est importante.

Problème de Khi carré:
- on a un échantillon seulement
- On a un potentiel risque d'échantillonnage
MAIS on veut tirer une conclusion à partir de cet échantillonnage.

$H_0$: La population présente un rapport 1:1
$H_A$: La population présente un rapport $\neq$ de 1:1

$\khi = \sum{k}{i=1}\dfrac{O_i - E_i}$ 

L'hypothèse nulle est que 50% de la population soit hommes, pareil pour femmes.

## Comment calculer les fréquences attendues?
Ce à quoi on s'attendrait si le pourcentage attendu s'appliquait à l'échantillon => 50% d'hommes, 50% de femmes.
$N*p$ où N est la population totale (100 personnes)
où $p$ est le pourcentage attendu (50%) -> 
$100 * (50/100) = 50$ hommes 

$X_obs$:
$obs$ - ce qui est observé dans l'échantillon

Formule du Khi carré:

$\dfrac{(Observés - attendus)^2}{\text{fréquence attendue pour ce groupe (H ou F)}}$ 

Pourquoi on divise par la fréquence attendue? C'est une manière de tenir compte de la taille de l'échantillon. Plus la fréquence attendue est grande, plus on aura d'observations donc de fiabilité. Le test Khi carré est plus faible lorsqu'on a de nombreuses observations.


## Calculer la probabilité qu'on obtienne une fréquence spécifique si $H_0$ est vraie (50-50 pour H/F)

Pour calculer la probabilité, il faut une table semblable à celle des $Z$. Or, pour les Khi carré, on a souvent de nombreuses catégories (H/F/O/T/avion de chasse) et donc ça nécessite une table différente (présente en fin de syllabus aussi).

Degré de liberté: $\text{nombre de catégories - 1}$

Dans la table, le degré de liberté est représenté par le terme $dl$.

**Exemple: 1**
Khi carré: 9
Degré de liberté: 2 - 1 = 1
Seuil de 0,05

$\chi^2_{0,05} = 3,84$ (probabilité que le khi carré soit plus grand que la valeur critique)

9 > 3,84 => Le Khi carré est trop grand par rapport au seuil => on rejette l'hypothèse.

Exemple 2:
Exemple avec le soda

$H_0$: la répartition est de 1:1:1 (33%, 33%, 33%)
$H_1$: la répartition est différente de 1:1:1

|                      | A   | B   | C   | Total |
| -------------------- | --- | --- | --- | ----- |
| Fréquences observées | 30  | 54  | 36  | 120   |
| Fréquences attendues | 40  | 40  | 40  | 120   |
|                      |     |     |     | 120   |

$\chi^2_{obs} = \dfrac{(30-40)^2}{40} + ... = 7,8$
$dl$ = 1
Valeur critique qui dit que la probabilité est > 0,05: 

7.8 > 3.84 => on rejette l'hypothèse.

# Test Khi carré d'indépendance

## Conditions pour l'appliquer
**Indépendance des observations:** 
	Chaque participant doit être indépendant des autres (ie: ne pas faire remplir un questionnaire de 100 personnes par 50 puis copier/coller). 

**Les petites fréquences attendues:** 
	Une catégorie a très peu de sujets. L'erreur d'échantillonnage est alors plus grand. Si une des fréquences attendues est plus **petites que 5**, je ne peux **pas faire le test Khi carré**.

**L'inclusion des non-occurrences:** 
	ex: est-ce que le fait de consommer de l'alcool a un effet sur les chances d'accidents de la route (2 variables). Mais peut être présenté en disant "J'ai eu 58 accidents, 10 en état d'ivresse, 48 qui ne l'étaient pas" => conclusion: boire de l'alcool réduit les chances d'accident.
	=> Si on fait un test Khi carré d'ajustement, la conclusion est que "boire de l'alcool réduit les chances d'accident".
	Erreur: on regarde juste le nombre d'accidents et on oublie ceux qui ne font pas d'accidents.
	**Il faut inclure les non-occurrences** (pas d'accidents) et donc réaliser un test khi carré d'indépendance.

$dl = (L-1) * (C-1)$

Les variables nominales sont-elles liées ou indépendantes?

2 variables nominales => Test Khi carré d'indépendance.

Ex: Le genre influence le fait de travailler à temps partiel? Le fait d'être croyant influence-t-il le fait d'être marié?
Le fait de souligner la faute de la victime influence-t-il le verdict de la culpabilité?

**Hypothèse nulle: les deux variables sont indépendantes**
**Hypothèse alternative: les deux variables sont liées**

| Faute  | Coupable | Non coupable | Total |
| ------ | -------- | ------------ | ----- |
| Légère | 153      | 24           | 177   |
| Grave  | 105      | 76           | 181   |
| Total  | 258      | 100          | 358   |
$H_0$: Le verdict n'est **pas** influencé par le fait de mentionner la culpabilité de la victime

Comment obtenir les 4 valeurs dans les cellules si les variables étaient indépendantes l'unes de l'autre.
Probabilité simple: total marginal/total général

$T_{coupable}/N$ = 258/358 = 0,72% se sont terminés sur la culpabilité

Quand les variables sont indépendantes, on peut multiplier les probabilités simples pour obtenir la probabilité conjointe.

Tableau des probabilités simples

| Faute  | Coupable                      | Non coupable | Total |
| ------ | ----------------------------- | ------------ | ----- |
| Légère | (177/358) * (258/358) = 0,356 | 0,138        | 177   |
| Grave  | 0,364                         | 0,141        | 181   |
| Total  | 258                           | 100          | 358   |




