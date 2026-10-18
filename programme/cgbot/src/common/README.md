Common (regroupement des interfaces)

- Rôle : contenir ce que tous les blocs partagent.
- `types.h` : les données échangées (`SensorData`, `WorldState`, `BehaviorId`, `Setpoint`, `MotorCommand`).
- `config.h` : tous les réglages (broches, seuils, vitesses, paramètres).
- Règle : toute modification de `types.h` est validée par Esther. Aucune valeur en dur ailleurs que dans `config.h`.
