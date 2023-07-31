# loyer

Imaginez que vous voulez savoir si vous payez trop cher votre loyer.
Vous disposez d’un ensemble de données composé de N = 21614 observations et 11 caractéristiques             (x1, x2, x3, … , x11) servant à prédire le prix du loyer y. 

 
Description du dataset
•	bedrooms => nombre de salles de chambre
•	bathrooms => nombre de salles de bain
•	surface_living => surface de vie privée (espace de privée)
•	surface_home => surface de l’appartement
•	floors => nombre de salon
•	waterfront => bordure de mer
•	view => nombre de vue sur mer
•	condition => condition de vie
•	grade => classe
•	year_built => année de construction
•	year_renovated => année de renovation	 
Régression linéaire univarié
1.	Pour avoir une meilleure idée du prix du loyer en fonction de la surface (surface_home), afficher le graphique en forme de nuage de point représentant le montant du loyer en fonction de la surface.
2.	Clairement, d'après la visualisation, que pouvez-vous donc émettre comme hypothèse hθ(x) de modélisation du phénomène surface par rapport au prix ?
3.	Remplacer les valeurs des paramètres   dans l’hypothèse hθ(x) et représenter graphiquement la droite qu'on a trouvée, pour vérifier qu'elle colle bien aux données.

4.	Maintenant qu’on a le paramètre optimal θ, utilisez le modèle pour effectuer des prédictions du loyer pour une surface de 5400 m2 et 12500 m2.

5.	Utilisez la fonction linear_model disponible dans package scikit-learn pour trouver la valeur des paramètres  .


Régression linéaire multivarié
Maintenant qu’on a trouvé un premier modèle, il serait possible de tester plein d’hypothèses différentes pour aller plus loin et améliorer ses performances. 
On ajoute des caractéristiques :
•	bedrooms
•	bathrooms
•	surface_living
•	surface_home
•	floors
•	waterfront
•	view
•	condition
•	grade
•	year_built
•	year_renovated


1.	Utilisez la fonction linear_model disponible dans package scikit-learn pour trouver la valeur des paramètres θ = (θ0, θ1, θ2, θ3, θ4, θ5, θ6, θ7, θ8, θ9, θ10, θ11, θ12).
2.	
3.	Utilisez la fonction linear_model disponible dans package scikit-learn pour trouver la valeur des paramètres θ = (θ0, θ1, θ2, θ3, θ4, θ5, θ6, θ7, θ8, θ9, θ10, θ11, θ12).
