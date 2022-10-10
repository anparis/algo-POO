# Exercice POO hôtel

> But : réaliser l’application en POO permettant la gestion de réservations de chambres par des clients dans différents hôtels.

![capture ecran exo hotel](/assets/img/Hotel.PNG)

## Difficultes
- La chambre ne peut plus être réservée une fois réservée par client
- Il faut passer par une classe associative Reservation pour récupérer les réservations de l'hôtel et du client
- Fonction usort pour trier les tableaux en fonction de la date ou du numéro de chambre

## Glossaire
- Méthode statique => Méthode spéciale qui peut être appelée sans avoir à instancier une classe. Elle ne dépend pas de valeurs particulières des propriétés d'une instance.
    => On utilise un `::` 'operateur de portee' pour y acceder. 
        Exemple avec une class Restaurant :
    ```php
    $plats = Restaurant::getPlats();
    ```