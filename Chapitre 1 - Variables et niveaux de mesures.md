La bonne identification du type de variable est nécessaire pour la résolution.

# Ressources
![[psychostat_1.pdf]]
 Il y a généralement plusieurs unités d'observation. Lrosqu'il n'y en a qu'une, ce sera un "cas unique". 
 
 **Unité d'observation**: 
	 étudiants de 4, 5, 6ème année
 
 **Mesure d'observation**: 
	 niveau de harcèlement

 **Variables**: la timdité, l'âge, le QI, le genre, score de dépression etc. Habituellement dénomées par une majuscule - âge du troisème sujet (A3)
	 Propriété de l'unité d'observation qui peut prendre plusieurs valeurs.
	 Une variable affete à chaque unité d'observation une et une seule valeur.
	 Exemple: on note toutes nos boissons préférées. On demandera plutot quelle est la boisson préférée plutot que de demander une liste. De cette façon on pourra associer une seule réponse à la question/variable

Exemple de variables:

Sujet | Genre
1           M
2           F
3           F

# Les types de variables

## Les variables nominales
On attribue à chaque sujet une étiquette.
> Prénom et nom de famille (exemple du prénom préféré de l'année).

Il n'y a pas de classement, pas de valeur chiffrée.
Le code postal est un chiffre mais c'est avant tout une étiquette (4000 n'est pas 2x2000)
Couleur des yeux, genre, profession, religion, état civil, préférence manuelle, diagnostic psychiatrique.

### Exceptions
Les variables nominale encodée sous forme de valeur chiffrée (état civil = 1). 

### Représentation

Table de fréquence

| Etat civil  | Fréquence |
| ----------- | --------- |
| Marié       | 10        |
| Célibataire | 5         |
| Total       | 15        |


Graphique circulaire (en camembert) - moins intuitif
Diagramme en barre

Note: variable (état civil) n'est pas la fréquence (10, 5, ...)
## Les variables ordinales

On classe les sujets les uns par rapport aux autres. 
Les valeurs sont ordonnées.
On a peu d'infos sur les différences entre 2 scores.
On n'est pas certains que la distance entre deux variables est toujours la même, je sais juste que je suis au dessus/en dessous du critère suivant/précédent.
### Exemple: 
indice de satisfaction: 
	Peu satisfait, moyennement satisfait, ok, satisfait, très satisfait
Notation de points aux tests:
	A, B, C, D, E, F 
Classement:
	1er, 2eme, 3eme à une course mais on ne connait pas le temps entre eux, juste leur ordre.

## Variable métrique
Permet une estimation précise de la différence entre deux sujets.

### Exemple
L'âge:
	Si je S1 a 30 ans et S2 a 65 ans, on connait la différence d'âge entre les deux personnes.
Temps de réponse
	Mesurable

### Echelle d'intervalle
Dans les échelles d'intervalle, on n'a pas de zéro. Exemple, la température.
Une température de 0 ne correspond pas à une absence de mesure; la valeur est de zéro mais la valeur existe.
### Echelle de rapport
Dans les échelles de rapport, il y a un vrai zéro. 
Exemple
	Note à l'examen. Un vrai 0 car il y a une absence du comportement désiré.


# Identifier le type de variables
Nominale: semblable ou différent
Ordinale: égal supérieur ou inférieur
Métrique: supérieur, inférieur de x unités 

### Avantages des différentes variables
LA variable métrique est plus puissante que les autres variables, permet une grande sophistication des variables avec un meilleur niveau de mesure.

Variable nominal > variable ordinale > variable métrique

# Variables dépendantes & indépendantes

Exemple:
	Nombre d'année d'expérience du professeur va-t-il influencer le niveau de bruit dans les amphis.
	Variable dépendante: la quantité de bruit dans l'amphi
	Variable indépendante: le nombre d'années d'expériences
Vi => VD
Groupe -> Résultat à l'examen
Stress -> Mortalité
Niveau d'étude -> Revenus

[[Arbre décisionnel]]


# Erreurs typiques
- Mauvaise identification de l'unité d'observation
	L'unité d'observation peut être un sujet ou un groupe (compter le nombre d'injures lors d'un débat, on peut compter le nombre d'insultes totales - si on juge le caractère violent du groupe - ou le nombre par personne)
- Mauvaise identification du niveau des variables
- Inversion entre Vi et Vd


# Statistiques descriptives 
Ensemble des outils permettant de résumer les données obtenues sur une ou plusieus variables
Exemple: 
**Représentation graphique:**
	table de fréquence, graphiques

**Mesure de tendances**


$\text{Fréquence relative}=\dfrac{\text{Fréquence de la catégorie}}{\text{Somme des fréquences de toutes les catégories}} = 0 \geq x \leq 1$

	Valeur entre 0 et 1

Etendue: la distance entre la plus petite et la plus grande valeur.
Les mesures de tendance centrale
Le centre de distribution, la valeur typique
Le mode: valeur la plus fréquente dans notre distribution (svt dans les valeurs métriques). 

Indices de tendance centrale:
Une seule fréquence qui ressort: Distribution modale
2 fréquences égales: Distribution multimodale
\> 2 fréquences qui ressortent: distribution classique

Médiane (variable nominale métrique):
	Autant de données au dessous qu'en dessous. "Barricentre" de la distribution (les observations doivent être triés dans l'ordre croissant avant de prendre la valeur de l'observation la plus au milieu). En cas de nombre pair
3, 5, 5, 6, 7, 8, [ici] 9, 11, 12, 13, 15, 15
médiane = 8+9 / 2 =  = 8,5

#lexique Moyenne (variables nominales)
	Somme des scores divisé par le nombre de scores


## Calcul de variance
### Division par $N$ ou pas $N-1$
Quand on calcule la variance d'un échantillon il y a deux objectifs:
- $N$: J'ai un ensemble de données pour toute la population et je veux vois la variabilité alors je divise par N. Si je suis face à toute la population, alors je peux juste diviser par N.
- $N-1$: Diviser par N: Si j'ai un objectif de calcul de variance de la population. Est-ce que j'utilise un échantillon pour connaitre la variance de la population? Alors je divise par N-1. "Calculer dans l'objectif de calculer ce qu'il se passe dans la population à partir d'un échantillon => N-1."

![[Pasted image 20241003091149.png]]
Formule rapide:
![[Pasted image 20241003091240.png]]
La moyenne des écarts au carré est de 16,36. Ca ne représente pas grand chose pour nous. On doit alors faire la racine carrée pour revenir à une valeur plus simple et plus compréhensible. 
$\sqrt{variance} = \text{écart type}$

Ecart type: sorte d'écart typique autour de la moyenne. Les individus s'écartent de x points "typiquement" autour de la moyenne.









