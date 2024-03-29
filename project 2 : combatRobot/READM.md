# README

## Description

Ce code Arduino contrôle un robot à l'aide de servomoteurs pour les mouvements, une caméra et un pistolet à eau. Il utilise également un capteur de distance à ultrasons pour détecter les obstacles et réagir en conséquence pour éviter les collisions tout en déployant ses fonctionnalités.

## Matériel requis

- Arduino (ou un microcontrôleur compatible)
- Servomoteurs x2
- Capteur de distance à ultrasons
- Pistolet à eau

## Configuration des broches

- `m11` : Broche pour le moteur arrière gauche
- `m12` : Broche pour le moteur arrière droit
- `m21` : Broche pour le moteur avant gauche
- `m22` : Broche pour le moteur avant droit
- `Servo GUN` : Broche pour le servo contrôlant le pistolet à eau
- `Servo TRIG` : Broche pour le servo contrôlant le déclencheur de la caméra
- `TrigPin` : Broche de déclenchement du capteur à ultrasons
- `EchoPin` : Broche de réception du capteur à ultrasons

## Fonctionnalités

- **Avancer** : Le robot avance en activant les moteurs avant gauche et droit.
- **Reculer** : Le robot recule en activant les moteurs arrière gauche et droit.
- **Gauche** : Le robot tourne à gauche en activant le moteur arrière droit et le moteur avant gauche.
- **Droite** : Le robot tourne à droite en activant le moteur arrière gauche et le moteur avant droit.
- **Arrêt** : Tous les moteurs sont arrêtés.
- **Déplacement du servo de pistolet à eau (GUN)** : Contrôle du mouvement du servo pour le pistolet à eau.
- **Déplacement du servo de déclenchement (TRIG)** : Contrôle du mouvement du servo pour le déclencheur de la caméra.
- **Détection d'obstacles** : Utilisation du capteur de distance à ultrasons pour détecter les obstacles et éviter les collisions.

## Utilisation

1. Assurez-vous d'avoir correctement connecté tous les composants conformément à la configuration des broches.
2. Téléversez le code sur votre Arduino.
3. Alimentez votre robot et observez son comportement.
4. Les moteurs et les fonctionnalités supplémentaires peuvent être contrôlés en envoyant des commandes via le moniteur série Arduino.

## Commandes via le moniteur série

Les commandes suivantes peuvent être envoyées via le moniteur série Arduino pour contrôler le robot :

- '1' : Avancer
- '2' : Gauche
- '3' : Droite
- '4' : Reculer
- '5' : Arrêt
- '6' : Déplacer le servo TRIG
- '7' : Déplacer le servo GUN

Assurez-vous que la vitesse de transmission série est réglée sur 9600 bauds.

## Avertissement

- Assurez-vous d'avoir suffisamment d'espace pour que le robot se déplace sans heurter d'obstacles.
- Manipulez le pistolet à eau avec précaution et veillez à ne pas mouiller les composants électroniques.

## Auteur

Ce code a été écrit par [daniel djikpesse](lien_vers_profil_github).
