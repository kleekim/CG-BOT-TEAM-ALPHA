Comportements

- Rôle : ce que le robot sait faire. Un fichier par comportement.
- Fichiers : `suivre_ligne` et `eviter_obstacle` (Moni), `attaquer`, `chercher` et `rester_arene` (Gesycka), `surprise` (à remplir plus tard)
- Reçoit : `BehaviorId` et `WorldState`
- Produit : `Setpoint`
- Fonction : `runBehavior()`, déclarée dans `comportements.h`
- Responsables :Monica (ligne, obstacle), Gesycka (stratégie combat)
- À ne pas faire : écrire directement sur une broche du robot.
