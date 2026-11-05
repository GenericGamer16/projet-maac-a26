# Éléments à implémenter

- La mangeoire doit résister aux éclaboussures puisqu'un bol de nourriture est souvent à côté d'un bol d'eau.
    - Préparer le plan du circuit imprimé afin de cacher l'électronique à l'intérieur de l'appareil.

- La mangeoire devrait être capable de mesurer le poids de la nourriture. Un chien de taille moyenne peut manger entre 200 et 400 grammes de nourriture par repas.
	- Utilisation d'une loadcell
        - Trouver une librairie Arduino pour le HX711
        - Tester la librairie et faire la calibration
		- Implémenter une fonction pour mesurer les poids sur la loadcell
		- Implémenter une fonction "tare" (mise à zero)

- La mangeoire doit avoir une interface utilisateur agréable et simple.
	- Utiliser un écran tactile
        - Trouver une librairie Arduino pour l'écran avec le ILI9341
        - Tester la compatibilité de la librairie sur un Nano Every
		- Implémenter le driver du module touch (ILI9341)
		- Implémenter les fonctions d'affichage de l'écran (ILI9341)
		- Faire une fonction temporaire qui active le moteur de la mangeoire lorsque l'écran est touché

- La mangeoire doit arrêter de fonctionner lorsqu'il est renversé ou vide.
	- Utilisation d'une loadcell
		- Implémenter une fonction qui détecte si la mangeoire est renversé en regardant si le poids est négatif

- La mangeoire doit afficher la quantité de nourriture restante.
    - Utiliser une loadcell et un écran
        - Implémenter une fonction qui mesure le poid actuel
        - Implémenter une fonction qui affiche le poid actuel sur l'écran

# Séparation des tâches
## Frankiboyy
### Élements du backlog
//@todo Franki

### Tâches
//@todo Franki

## GenericGamer16
### Élements du backlog

1. La mangeoire doit résister aux éclaboussures puisqu'un bol de nourriture est souvent à côté d'un bol d'eau.
4. La mangeoire doit arrêter de fonctionner lorsqu'il est renversé ou vide.

### Tâches

|Tâches liées à l'accéléromètre|Temps estimé|
|-------|-------|
|Assigner les pins pour l'accéléromètre et faire le branchement temporaire|1 heures|
|Configurer les pins de l'accéléromètre|1 heures|
|Lire l'accéléromètre|3 heures|
|Créer une fonction qui retourne «true» quand l'appareil est tombé. |1 heure|
|Temps total|6 heures|

|Tâches liées au circuit imprimé|Temps estimé|
|-------|-------|
|Placer initialement l'arduino|1 Heures
|Assigner et connecter les pins de l'écrans à l'arduino|5 heures|
|Assigner et connecter les pins du driver à l'arduino|4 heures|
|Assigner et connecter les pins de la loadcell à l'arduino|2 heures|
|Assigner et connecter les pins de l'accéléromètre sur l'arduino|3 heures|
|Temps total|15 heures|


## Artgameur
### Élements du backlog
//@todo Charles-Antoine

### Tâches

//@todo Charles-Antoine
