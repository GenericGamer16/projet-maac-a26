# objectifs de sprint
Avoir un prototype fonctionnel

# Éléments à implémenter
- La mangeoire devrait être capable de mesurer le poids de la nourriture. Un chien de taille moyenne peut manger entre 200 et 400 grammes de nourriture par repas.
	- Utilisation d'une loadcell
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
### Frankiboyy
1. La mangeoire doit pouvoir détecter s'il est bloqué. Une notification sonore, visuel ou autres, doit être mise en place.
2. La mangeoire doit avoir une interface utilisateur agréable et simple.
3. La mangeoire doit afficher la quantité de nourriture restante.

- Écran tactile
	- Implémenter le driver du module touch (ILI9341)
	- Implémenter les fonctions d'affichage de l'écran (ILI9341)
    - Créer une fonction d'alerte qui affiche un message sur l'écran.
	- Faire une fonction temporaire qui active le moteur de la mangeoire lorsque l'écran est touché
    - Implémenter une fonction qui affiche le poid actuel sur l'écran

### GenericGamer16
1. La mangeoire devrait être capable de mesurer le poids de la nourriture. 2. Un chien de taille moyenne peut manger entre 200 et 400 grammes de nourriture par repas.
3. La mangeoire doit pouvoir détecter s'il est bloqué. Une notification sonore, visuel ou autres, doit être mise en place.
4. La mangeoire doit pouvoir se débloquer au besoin. Un mécanisme doit-être prévu pour éviter les blocages. (optionnel pour ce sprint)
5. La mangeoire doit arrêter de fonctionner lorsqu'il est renversé ou vide.
6. La mangeoire doit afficher la quantité de nourriture restante.

- Moteur
    - Créer une fonction qui active le moteur dans le sens horaire
    - Créer une fonction qui active le moteur dans le sens anti-horaire (optionnel pour ce sprint)
    - Créer une fonction qui détecte l'état du moteur et appel une fonctions d'alerte si il est bloqué


- Loadcell
    - Implémenter une fonction qui mesure le poid actuel
    - Implémenter une fonction qui détecte si la mangeoire est renversé en regardant si le poids est négatif
    - Implémenter une fonction pour mesurer les poids sur la loadcell
    - Implémenter une fonction "tare" (mise à zero)


### Artgameur
1. La mangeoire devrait être capable de nourrir un chat normal pour 5 jours. Pour des croquettes denses en énergie on parle de 40 à 60 grammes par jours.
2.  L'entrée du réservoir doit être scellé. Si le réservoir tombe de côté, il ne doit s’ouvrir.
3. La mangeoire doit être stable et ne pas tomber lors de l’utilisation normale.
4. La mangeoire doit résister aux éclaboussures puisqu'un bol de nourriture est souvent à côté d'un bol d'eau.
5. La mangeoire doit être disponible en plusieurs couleurs.

- Models 3D
	- Habitacle de l'écran
	- Habitacle du moteur
    - Vis sans fin
    - Convercle/Ouverture
    - Habitacle de la loadcel
    - Plaque en suspend (prise du poids)