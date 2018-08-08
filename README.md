# Challenges AJAX/Symfony

Support : https://github.com/O-clock-Fusion/Symfo-E04-intro-ajax

Vous pouvez créer les 2 challenges dans la même appli Symfony, dans 2 contrôleurs différents.

## Fortune cookie

### Objectif

Créer une page pour afficher [un message "fortune cookie"](https://www.google.fr/search?q=fortune+cookie) aléatoire.

- Reprendre la trame du livecoding.
- Créer un modèle FortuneModel qui contiendra une liste de messages (à créer aussi).
- Créer une méthode dans FortuneModel pour renvoyer un message aléatoire.
- Récupérer et afficher le message côté front.

## Challenge : Jeu du trop petit trop grand

### Objectif

Jeu du trop petit trop grand : deviner un nombre entre 1 et 100.

- Trame AJAX précédente + utilisation de la Session Symfony.
- Le serveur doit pouvoir **définir un nombre aléatoire entre 1 et 100** qu'il garde en mémoire **quand on arrive sur la page**.
- **Proposer un nombre**, via un champ texte et un bouton "Soumettre", transmis en AJAX.
- Le serveur **compare** le nombre soumis et le nombre mémorisé et **renvoie** "trop petit" ou "trop grand" ou "gagné !".
- Recharger la page pour rejouer, ou faites évoluer votre code pour relancer une nouvelle partie.

## Challenge : un zest d'AJAX dans la Todolist

Modifier l'appli Todolist existante.

- Faire en sorte que la fonction _delete Task_ fonctionne via AJAX.
- Si besoin [revoir oKanBan](https://github.com/O-clock-Fusion/S06-E06-challenge-Kanban/blob/master/js/app.js) pour l'inspiration JS (notamment au niveau des `data-id`).
- Pour supprimer un élément du DOM via jQuery, voir : https://api.jquery.com/remove/

Bon courage !
