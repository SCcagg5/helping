# helping
Bien qu'elle soit légèrement aplatie aux pôles, la Terre est fondamentalement une sphère, et sur une surface sphérique, vous pouvez exprimer la distance entre deux points à la fois en termes d'angle et de distance linéaire. La conversion est possible car, sur une sphère de rayon "r", une ligne tracée du centre de la sphère à la circonférence, la longueur d'arc "L" tracée lorsque l'angle change d'un nombre "A" de degrés est :

```
L=2πrA/360
```

Longitudes et latitudes
Chaque point de la Terre est défini par des mesures uniques de longitude et de latitude, qui sont exprimées sous forme d'angles. La longitude est l'angle entre ce point et l'équateur, tandis que la latitude est l'angle entre ce point et une ligne allant de pôle à pôle et passant par Greenwich, en Angleterre.

Si vous connaissez les longitudes et les latitudes de deux points, vous pouvez utiliser ces informations pour calculer la distance qui les sépare. Le calcul se fait en plusieurs étapes, et comme il est basé sur la géométrie linéaire - et que la Terre est incurvée - il est approximatif.

Soustrayez la plus petite latitude de la plus grande pour les lieux qui sont tous deux situés dans l'hémisphère nord ou dans l'hémisphère sud. Additionnez les latitudes si les lieux sont situés dans des hémisphères différents.

Soustrayez la plus petite longitude de la plus grande pour les lieux qui sont tous deux situés dans l'hémisphère oriental ou dans l'hémisphère occidental. Additionnez les longitudes si les lieux sont situés dans des hémisphères différents.

Multipliez les degrés de séparation de la longitude et de la latitude par 111 139 pour obtenir les distances linéaires correspondantes en mètres.

Considérez la ligne entre les deux points comme l'hypoténuse d'un triangle rectangle dont la base "x" est égale à la latitude et la hauteur "y" est égale à la longitude qui les sépare. Calculez la distance qui les sépare (d) en utilisant le théorème de Pythagore :

````
d^2=x^2+y^2
```
