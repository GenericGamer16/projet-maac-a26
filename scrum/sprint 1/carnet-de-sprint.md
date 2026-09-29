# Objectif de sprint
Avoir un prototype fonctionnel

# Éléments à implémenter
- La mangeoire devrait être capable de mesurer le poids de la nourriture. Un chien de taille moyenne peut manger entre 200 et 400 grammes de nourriture par repas.
	- Utilisation d'une loadcell
        - Trouver une librairie Arduino pour le HX711
        - Tester la librairie et faire la calibration
		- Implémenter une fonction pour mesurer les poids sur la loadcell
		- Implémenter une fonction "tare" (mise à zero)

- La mangeoire doit pouvoir détecter s'il est bloqué. Une notification sonore, visuel ou autres, doit être mise en place.
	- Utilisation d'un moteur et d'un écran
		- Créer une fonction qui détecte l'état du moteur et appel une fonctions d'alerte si il est bloqué
        - Créer une fonction d'alerte qui affiche un message sur l'écran.

- La mangeoire doit pouvoir se débloquer au besoin. Un mécanisme doit-être prévu pour éviter les blocages. (optionnel pour ce sprint)
	- Utilisation d'un moteur
		- Créer une fonction qui fait fonctionner le moteur dans le sens inverse. 


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
1. La mangeoire doit pouvoir détecter s'il est bloqué. Une notification sonore, visuel ou autres, doit être mise en place.
2. La mangeoire doit avoir une interface utilisateur agréable et simple.
3. La mangeoire doit afficher la quantité de nourriture restante.

### Tâches
|Tâches liées à l'écran tactile|Temps estimé|
|-------|-------|
|Trouver une librairie Arduino pour l'écran avec le ILI9341| 1 heures|
|Tester la compatibilité de la librairie sur un Nano Every| 1 heures|
|Implémenter le driver du module touch (ILI9341)| 1 heures|
|Implémenter les fonctions d'affichage de l'écran (ILI9341)| 2 heures|
|Créer une fonction d'alerte qui affiche un message sur l'écran.| 1 heures|
|Faire une fonction temporaire qui active le moteur de la mangeoire lorsque l'écran est touché| 2 heures|
|Implémenter une fonction qui affiche le poid actuel sur l'écran| 1 heures|
|Temps total| 9 heures|

## GenericGamer16
### Élements du backlog
1. La mangeoire devrait être capable de mesurer le poids de la nourriture. 2. Un chien de taille moyenne peut manger entre 200 et 400 grammes de nourriture par repas.
3. La mangeoire doit pouvoir détecter s'il est bloqué. Une notification sonore, visuel ou autres, doit être mise en place.
4. La mangeoire doit pouvoir se débloquer au besoin. Un mécanisme doit-être prévu pour éviter les blocages. (optionnel pour ce sprint)
5. La mangeoire doit arrêter de fonctionner lorsqu'il est renversé ou vide.
6. La mangeoire doit afficher la quantité de nourriture restante.

### Tâches

|Tâches liées au moteur|Temps estimé|
|-------|-------|
|Créer une fonction qui active le moteur dans le sens horaire| heures|
|Créer une fonction qui active le moteur dans le sens anti-horaire (optionnel pour ce sprint)| heures|
|Créer une fonction qui détecte l'état du moteur et appel une fonctions d'alerte si il est bloqué| heures|
|Temps total| heures|

|Tâches liées à la Loadcell|Temps estimé|
|-------|-------|
|Trouver une librairie Arduino pour le HX711| heures|
|Tester la librairie et faire la calibration| heures|
|Implémenter une fonction qui mesure le poid actuel| heures|
|Implémenter une fonction qui détecte si la mangeoire est renversé en regardant si le poids est négatif| heures|
|Implémenter une fonction pour mesurer les poids sur la loadcell| heures|
|Implémenter une fonction "tare" (mise à zero)| heures|
|Temps total| heures|


## Artgameur
### Élements du backlog
1. La mangeoire devrait être capable de nourrir un chat normal pour 5 jours. Pour des croquettes denses en énergie on parle de 40 à 60 grammes par jours.
2. L'entrée du réservoir doit être scellé. Si le réservoir tombe de côté, il ne doit s’ouvrir.
3. La mangeoire doit être stable et ne pas tomber lors de l’utilisation normale.
4. La mangeoire doit résister aux éclaboussures puisqu'un bol de nourriture est souvent à côté d'un bol d'eau.
5. La mangeoire doit être disponible en plusieurs couleurs.

### Tâches

|Tâches liées aux models 3D|Temps estimé|
|-------|-------|
|Modelisation du contenant|2 heures|
|Modelisation de l'habitacle de l'écran|2 heures|
|Modelisation de l'habitacle du moteur|2 heures|
|Modelisation de la vis sans fin|4 heures|
|Modelisation du couvercle|2 heures|
|Modelisation de l'habitacle de la loadcel|1 heures|
|Modelisation de la plaque en suspend (prise du poids)|2 heures|
|Tests et ajustements des models|5 heures|
|Temps total|20 heures|