
# Interpolation Polynomiale – MATLAB


## Contexte
Ce projet explore deux techniques classiques d’interpolation polynomiale : Lagrange et Newton, appliquées à différentes fonctions mathématiques 
pour comparer leur précision et leur stabilité.
L’étude met en lumière les effets du nombre de points d'interpolation ainsi que du choix de la fonction, en particulier en présence du phénomène de Runge.

## Objectifs
Implémenter les méthodes de Lagrange et Newton pour des interpolations polynomiales.
Étudier le comportement de ces interpolants sur deux fonctions :
  - 𝑓(𝑥)=𝑒^𝑥
  - 𝑓(𝑥)=1 /(1+25𝑥^2)  (fonction de Runge)
Analyser l’évolution de l’erreur absolue et relative lorsque le nombre de points augmente.

## Méthodes implémentées
- Lagrange : calcul du polynôme via la formule de base.
- Newton : construction du polynôme par les différences divisées.
Comparaison graphique entre la fonction réelle et son interpolant.
Calculs de l’erreur absolue et relative sur une grille dense.

