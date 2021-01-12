[:arrow_left: Retour vers le portfolio](https://github.com/ThibaultLanthiez/Portfolio)

# Intelligence artificielle pour des robots pompiers en programmation orienté objet

Le but de ce projet est de programmer une intelligence artificielle pour des robots pompiers devant éteindre des incendies sur une carte. Cette carte est constituée de divers éléments comme des points d'eau (pour que les robots rechargent leur réservoir), de la forêt et bien sûr de zones d'incendie. 

Ces robots sont de trois types différents. Il y a tout d'abord un drone qui à la capacité de survoler les forêts. Puis il y a un gros véhicule avec une vitesse très faible mais un très grand réservoir. Et enfin, il y a aussi l'inverse, un petit véhicule très rapide mais avec un petit réservoir. Ce dernier est donc obligé de faire beaucoup d'aller-retour entre les points d'eau et les incendies. 

En langage Java, il a donc fallu programmer le comportement des robots en fonction en fonction des obstacles qu'ils rencontrent (certains ne pouvant pas traverser la forêt), de leur vitesse et de la taille de leur réservoir.

Il a aussi fallu calculer le plus court chemin avec [l'algorithme de Dijkstra](https://fr.wikipedia.org/wiki/Algorithme_de_Dijkstra) pour indiquer aux robots comment se diriger vers les incendies. 

De plus, étant donné que l'on programme de façon orientée objet, le principe d'héritage des classes et méthodes était important. Ainsi, les 3 robots étaient définis dans 3 classes différentes et leur code qui leur été commun était factorisé dans une classe mère. 

# Code 
Les programmes ne sont pas disponibles étant donné que ce projet sera surement reproposé l'année prochaine à l'ENSIMAG.
