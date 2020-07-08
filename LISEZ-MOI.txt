Pour l'utilisation du widget, il est nécessaire de : 

- Créer un widget (ou importer le widget) dans Jeedom
- Copier les images si vous le souhaitez
- Créer un virtuel avec une commande de type information et de type autre ainsi que décocher l'historisation de la commande
- Affecter à cette commande le widget MeteoFull
- Ajouter les options suivantes (bien respecter l'ortographe et la casse) : 
	* image : chemin où sont stockées les images (exemple : /data/customTemplates/dashboard/METEO/) (Par défaut icone du site https://www.prevision-meteo.ch)
	* keyAPI : clé nécessaire afin de faire fonctionner une partie du widget. Pour ce faire, il est nécessaire de créer un compte et de prendre la clé gratuite sur : https://www.weatherbit.io/
	* latitude : la latitude (en décimale) du lieu pour la maison (Par défaut Paris)
	* longitude : la longitude (en décimale) du lieu pour la maison (Par défaut Paris)
	* previsionsHeures : permet d'afficher ou pas le panneau de prévisions des heures (OUI / NON - Par défaut à NON)
	* temperaturesCouleur : permet d'afficher ou non le dégradé de couleurs pour les températures (OUI / NON - Par défaut à NON). Si non, il y aura bleu pour le mini et rouge pour le maxi au niveau des températures quotidiennes.
	* temperaturesRessentieCouleur : permet d'afficher ou non le dégradé de couleurs pour les températures ressenties (OUI / NON - Par défaut à NON)
	* rafalesCouleur : permet d'afficher ou non le dégradé de couleurs pour les rafales (OUI / NON - Par défaut à NON)
	* humiditeCouleur : permet d'afficher ou non le dégradé de couleurs pour l'humidité (OUI / NON - Par défaut à NON)
	* seuilVent : permet de définir un seuil (en km/h) à partir du quel, l'indicateur passera dans une couleur rouge pour l'écriture (par défaut à 200)
	* seuilPrecipitation : permet de définir un seuil (en mm) à partir du quel, l'indicateur passera dans une couleur bleue pour l'écriture (par défaut à 50)
