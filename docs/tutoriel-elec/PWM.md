---
sidebar_position: 2
---

# PWM

Aussi connu sous le nom de **Modulation de Largeur d'Impulsion (MLI)** pour les anglophobes, les **PWM** représentent une part essentielle à maîtriser pour vos projets d'électroniques et d'informatique.

### Comment ça marche ?

En générant une Pulse Width Modulation on peut moduler la puissance transmise par notre carte.

En effet, en faisant varier très rapidement la valeur de notre signal entre un état haut et un état bas pendant une certaine durée, on fait varier la valeur moyenne de notre sortie de manière à ce qu'il vaille n'importe quelle valeur entre ces deux états.

Le rapport entre la durée de variation de l'état haut et celui de l'état bas durant une période est ce que l'on appelle **"rapport cyclique"** qui est généralement exprimé en pourcentage.

Pour mieux comprendre cela, en voici une illustration:

![PWM1](./imgd/PWM1.png)

RQ: si le rapport cyclique vaut 100%, on obtient un échelon et si le rapport cyclique vaut 0% on obtient en effet, un signal nul.