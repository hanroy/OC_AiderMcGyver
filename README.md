# Projet 3 - Aidez MacGyver à s'échapper !

## Fonctionnalités

- Il n'y a qu'un seul niveau. La structure (départ, emplacement des murs, arrivée), devra être enregistrée dans un fichier pour la modifier facilement au besoin.
- MacGyver sera contrôlé par les touches directionnelles du clavier.
- Les objets seront répartis aléatoirement dans le labyrinthe et changeront d’emplacement si l'utilisateur ferme le jeu et le relance.
- La fenêtre du jeu sera un carré pouvant afficher 15 sprites sur la longueur.
- MacGyver devra donc se déplacer de case en case, avec 15 cases sur la longueur de la fenêtre !
- Il récupèrera un objet simplement en se déplaçant dessus.
- Le programme s'arrête uniquement si MacGyver a bien récupéré tous les objets et trouvé la sortie du labyrinthe. S'il n'a pas tous les objets et qu'il se présente devant le garde, il meurt (la vie est cruelle pour les héros).
- Le programme sera standalone, c'est-à-dire qu'il pourra être exécuté sur n'importe quel ordinateur.


## Etapes

1. Créer le cadre de départ

Initialisez un repo Git et envoyez-le sur Github.

Commencez par créer le labyrinthe sans l’interface graphique. Quand la logique de votre labyrinthe est faite, utilisez le module TKinter pour dessiner l’interface graphique.

Puis intéressez-vous aux trois éléments principaux du jeu : le gardien, MacGyver et les objets. Comment les représenter dans votre programme ? Où sont-ils placés au commencement du jeu ?   

2.  Animer le personnage

Le seul élément mouvant est MacGyver. Créez les méthodes de classe qui permettent de l'animer et de trouver la sortie. Pour l'instant, faites une version simplifiée du jeu dans laquelle MacGyver gagne en arrivant face au gardien.

3. Récupérer les objets

Ajoutez la gestion des objets. Comment MacGyver les ramasse-t-il ?  Ajoutez également un compteur qui les listera.

4. Gagner !

Enfin, changez la fin du jeu : MacGyver gagne s'il a bien ramassé tous les objets et endormi le garde. Sinon, il perd.
