Décision

- Rôle : choisir quel comportement exécuter. Applique d'abord les priorités de sécurité (par exemple éviter le bord avant d'attaquer), puis interroge la mission active.
- Reçoit : `WorldState`
- Produit : `BehaviorId`
- Fonction : `decide()`, déclarée dans `decision.h`
- Responsable : monica , jessica
- À ne pas faire : contenir la stratégie d'une épreuve (elle se trouve dans `missions/`).
