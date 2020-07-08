***Bonsoir à tous. Il est disponible !! Faites-vous plaisir.***

**Pour information :**
Je suis en réflexion sur le fait de développer un plugin de ce widget afin de bénéficier de commandes pour vos scénarios notamment. Je vous tiendrais au courant de l'évolution.

**Le widget permet de :**
- Obtenir une météo sur 5 jours, 
- Heures par heures pour les 5 jours. 
- Personnalisation poussée :
   + Affichage ou pas d'un dégradé pour la température, la température ressentie, les rafales, l'humidité (de manière indépendante)
   + Affichage d'un seuil pour le vent, les précipitations 
   + Gestion des thèmes de Jeedom.
   + Affichage ou pas du panneau heures par heures

**Pour l'utilisation du widget, il est nécessaire de :**
- Créer un widget (ou importer le widget) dans Jeedom
- Copier les images se trouvant dans le dossier "cmd.info.string.MeteoFull" au bonne endroit : /data/customTemplates/dashboard/. **Garder le même nom que le dossier source ou alors n'oubliez pas l'option "images" permettant d'indiquer le chemin des images**
- Copier les images des conditions (sans le dossier) si vous le souhaitez dans le même dossier et au même endroit que les autres images
- Créer un virtuel avec une commande de type information et de type autre ainsi que décocher l'historisation de la commande
- Affecter à cette commande le widget MeteoFull
- Ajouter les options obligatoires suivantes (**bien respecter l'orthographe et la casse**) :
   + keyAPI : clé nécessaire afin de faire fonctionner une partie du widget. Pour ce faire, il est nécessaire de créer un compte et de prendre la clé gratuite sur : https://www.weatherbit.io/
   + latitude : la latitude (en décimale) du lieu souhaité (Par défaut Paris)
   + longitude : la longitude (en décimale) du lieu souhaité  (Par défaut Paris)

**Pour la personnalisation du widget, vous avez ces options supplémentaires si vous le souhaitez :** 
   + images : chemin où sont stockées les images (exemple : /data/customTemplates/dashboard/cmd.info.string.MeteoFull/) (Par défaut si l'option n'est pas renseignée, les icones des conditions viendront du site https://www.prevision-meteo.ch, les autres images seront bien présentes)
   + previsionsHeures : permet d'afficher ou pas le panneau de prévisions des heures (OUI / NON - Par défaut à NON)
   + temperaturesCouleur : permet d'afficher ou non le dégradé de couleurs pour les températures (OUI / NON - Par défaut à NON). Si non, il y aura bleu pour le mini et rouge pour le maxi au niveau des températures quotidiennes.
   + temperaturesRessentieCouleur : permet d'afficher ou non le dégradé de couleurs pour les températures ressenties (OUI / NON - Par défaut à NON)
   + rafalesCouleur : permet d'afficher ou non le dégradé de couleurs pour les rafales (OUI / NON - Par défaut à NON)
   + humiditeCouleur : permet d'afficher ou non le dégradé de couleurs pour l'humidité (OUI / NON - Par défaut à NON)
   + seuilVent : permet de définir un seuil (en km/h) à partir duquel, l'indicateur passera dans une couleur rouge pour l'écriture (par défaut à 200)
   + seuilPrecipitations : permet de définir un seuil (en mm) à partir duquel, l'indicateur passera dans une couleur bleue pour l'écriture (par défaut à 50)

**Le voici :**
https://github.com/AnthonyDomotique/widgetMeteoFull

**Pour le support :**
Merci d'utiliser le canal sur le discord (DOMOTECH) suivant : #devapps-anthony

**Enfin, je voudrais remercier par ordre alphabétique, @iPapy, @jcamus86, @Jerome, @Tom's pour tous les tests et leur disponibilité. Sans eux, vous ne pourriez pas utiliser ce widget.