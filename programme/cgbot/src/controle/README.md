Contrôle

- Rôle : calculer les commandes des moteurs : PID (proportionnel au début), rampes d'accélération, limites de vitesse et de sécurité, conversion de la vitesse et de la rotation en puissance gauche et droite.
- Reçoit : `Setpoint`
- Produit : `MotorCommand`
- Fonction : `control()`, déclarée dans `controle.h`
- Responsable : Yoane
- À ne pas faire : connaître l'épreuve ou la stratégie en cours.
