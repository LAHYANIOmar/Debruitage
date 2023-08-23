# Debruitage
Débruitage d’une image

# Types des bruits
Bruit gaussien :
Le bruit gaussien est un bruit statistique ayant une fonction de densit ́e de probabilité  ́egale  la distribution normale. 
La fonction gaussienne aleatoire est ajoutée à la fonction Image pour générer ce bruit. Il est  ́egalement appelé bruit  ́electronique car il se produit dans les amplificateurs ou les détecteurs.
Dans ce projet, on a bruité l’image en couleur avec le bruit de gauss en utilisant une variance V = 1000 et une moyenne nulle. Ce choix des paramètres
rend l’image presque invisible, et ceci pour tester la méthode de débruitage employée.

Bruit ”salt and pepper” :
La 2  ́eme méthode s’appelle bruit poivre et sel et comme son nom indique.
il s’agit de tacheter l’image en blanc ou en noir. C’est un bruit impulsionnel qui altère aléatoirement une image num ́erique, faisant passer l’intensité
de certains pixels (répartis d’une manière aléatoire dans l’image) à la valeur minimum ou maximum de la plage dynamique du pixel, respectivement 0 et
255 dans le cas d’une image num ́erique cod ́ee en 8-bits.Le bruit poivre et sel qui apparait dans une image numérique est du soit à des erreurs de transmission de données, soit au dysfonctionnement ou à la présence de particules fines sur les  ́eléments du capteur de la caméra ou à des emplacements mémoire défectueux dans le matériel.

# Méthodes de débruitage
Non-local means denoising.

Filtre median.
