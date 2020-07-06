# widgetMeteoFull

Pour l'utilisation du widget, il est nécessaire de : 

- Créer un widget (ou importer le widget) dans Jeedom
- Copier les images si vous le souhaitez
- Créer un virtuel avec une commande de type information et de type autre ainsi que décocher l'historisation de la commande
- Affecter à cette commande le widget MeteoFull
- Ajouter les options suivantes (bien respecter l'ortographe et la casse) : 
	* image : chemin où sont stockées les images (exemple : /data/customTemplates/dashboard/METEO/)
	* keyAPI : clé nécessaire afin de faire fonctionner une partie du widget. Pour ce faire, il est nécessaire de créer un compte et de prendre la clé gratuite sur : https://www.weatherbit.io/
	* latitude : la latitude (en décimale) du lieu pour la maison
	* longitude : la longitude (en décimale) du lieu pour la maison
	* previsionsHeures : permet d'afficher ou pas le panneau de prévisions des heures (OUI / NON)
