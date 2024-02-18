# README

## Description

Ce code Arduino permet d'enregistrer et de jouer des séquences de mouvements pour un bras robotique à l'aide de servomoteurs. Il inclut des fonctionnalités pour enregistrer les mouvements en temps réel et les reproduire par la suite.

## Matériel requis

- Arduino (ou un microcontrôleur compatible)
- Servomoteurs x3 (ou plus pour des mouvements supplémentaires)
- Bouton d'enregistrement
- Bouton de lecture
- Bouton pour effacer la mémoire flash (facultatif)
- LED (facultatif, pour indiquer l'état de l'enregistrement)

## Configuration des broches

- `recordButtonPin` : Broche pour le bouton d'enregistrement
- `playButtonPin` : Broche pour le bouton de lecture
- `flashButton` : Broche pour le bouton d'effacement de la mémoire flash (facultatif)
- `servoPin`, `servoPin1`, `servoPin2`, etc. : Broches pour les servomoteurs
- `feedbackPin` : Broche pour le retour analogique du mouvement (facultatif)
- `analogPin1`, `analogPin2`, etc. : Broches pour les entrées analogiques supplémentaires (facultatif)

## Fonctionnalités

- **Enregistrement** : Permet d'enregistrer les mouvements des servomoteurs en temps réel.
- **Lecture** : Permet de reproduire les mouvements enregistrés précédemment.
- **Effacement de la mémoire flash** : Permet d'effacer la mémoire flash de l'Arduino pour enregistrer de nouvelles séquences (facultatif).

## Utilisation

1. Connectez les composants conformément à la configuration des broches.
2. Téléversez le code sur votre Arduino.
3. Utilisez le bouton d'enregistrement pour enregistrer les mouvements souhaités.
4. Utilisez le bouton de lecture pour reproduire les mouvements enregistrés.

## Commandes

- **Bouton d'enregistrement** : Appuyez pour démarrer l'enregistrement des mouvements.
- **Bouton de lecture** : Appuyez pour lire les mouvements enregistrés.

## Avertissement

- Manipulez les servomoteurs avec précaution pour éviter tout dommage.
- Assurez-vous que les mouvements enregistrés ne causent pas de collision ou de dommage aux composants environnants.

## Auteur

Ce code a été écrit par [daniel djikpesse](https://github.com/komidjikpesse).
