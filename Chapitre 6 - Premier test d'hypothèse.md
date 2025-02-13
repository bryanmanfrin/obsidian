![[stat- Chapitre 6.pdf]]

Raisonnement statistique inférentiel: Sur base de 10 lancés de dés, si j'obtiens 9x un 6, j'ai l'impression qu'il est truqué.

1) Poser une hypothèse
2) Récolter des observations
3) Calculer la probabilité d'obtenir ces observations si l'hypothèse est correcte
4) Tirer des conclusions en fonction de la probabilité calculée. 
   Probabilité faible (< 5%, < 0.05) -> rejet de l'hypothèse
    ("Il est très improbable que l'individu appartienne à une population saine. Il appartient à une population qui a des troubles neurologiques")
   Sinon, on **ne rejette pas** l'hypothèse mais en même temps on n'accepte pas directement l'opposé de l'hypothèse

On va alors utiliser la distribution normale et trouver le $Z$ pour en connaitre la probabilité.

# L'hypothèse nulle
On pose une hypothèse nulle (le traitement est inefficace)
et
une hypothèse alternative (le traitement est efficace)

Notation des hypothèses:
$H_0: \mu = 100$
$H_A: \mu < 100$
$\sigma = 20$

On va alors utiliser 

## Les erreurs possibles
Je rejette l'hypothèse nulle alors qu'elle est vraie: faux positif (plus grave car on affirme qu'un individu appartient à une population alors que non).
Je ne rejette pas l'hypothèse nulle  alors qu'elle est fausse: faux négatif ("pas assez de preuve", moins grave car moins d'implications)


# Erreurs $\alpha$ et $\beta$ 
$\alpha$: seuil de signification (5%)

Si on essaye de situer une personne dans deux populations sans connaitre la moyenne d'une des populations (i.e. troubles neurologiques), on va indiquer que $\mu = ?$ pour cette population.

Les 5% de sujets avec les scores les plus faibles transposés dans la distribution normale des individus sains seront posés comme faux-positifs. On va donc se tromper sur les 5% d'individus en les classant comme personnes à troubles neurologiques.

Erreur de 1ère espèce $\alpha$:
Erreur de 2ème espèce $\beta$:


## Tests unilatéraux et bilatéraux

Test unilatéral: on rejette l'hypothèse nulle
Test bilatéral: on rejette les hypothèses lorsque je me trouve dans les extrêmes hautes ET basses.
On rejette l'hypothèse nulle quand o est dans les 2,5% les plus bas et les 2.5% ($\alpha/2$) les plus élevés.
Est-ce qu'on a un individu qui a un score différent de la moyenne? On va alors chercher les extrémités.

Exemple:
$H_0: \mu = 100$
$\sigma = 20$

Score de 58

P(X < 58) < $\alpha/2$ 
P(X > 58) > $\alpha/2$ 
P(X < 58) = 0.0179

$0.0179 < 0,025$ => L'individu souffre de troubles neurologiques car il est sous l'extrémité des 2.5%.


Autre exemple: P(X > 160) = 0,0013
0,0013 < 0,025 Rejeter $H_0$

## Technique de la valeur critique
Je peux comparer le Z trouvé pour un score pour avec la valeur critique (1,645) pour savoir si je suis dans les extrêmes (ça évite juste d'aller chercher la proba pour le Z dans le tableau en comparant directement les Z).


# L'intervalle de confiance
Formule qu'on va utiliser pour donner les valeurs de la population pour laquelle on ne rejette pas l'hypothèse nulle.

Deux bornes entre lesquelles on est quasi sur (95%) de trouver le sujet. Autour de la moyenne:
=> Moyenne $pm$ qq chose

Calcule la limite inférieure et supérieure

$18,2 < \mu < 97,2$

$OC_{0,95} = X \pm Z_{\alpha/2}\sigma$



- [x] faux-positifs vs faux-négatifs ✅ 2025-02-13

