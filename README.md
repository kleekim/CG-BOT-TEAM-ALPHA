CG BOT - Team Alpha

Programme du robot CG BOT.

Structure

- `docs/` : présentation , documentation
- `programme/cgbot/` : le programme du robot (`cgbot.ino` et le dossier `src/`)
- `tests/` : faux capteurs et tests

Les blocs du programme

Capteurs, Perception, Décision (avec les Missions), Comportements, Contrôle, Actionneurs. Chaque bloc a son dossier dans `programme/cgbot/src/`, avec son README.


  Règles de travail
  
- La branche `main` contient uniquement du code stable.
- Chacun travaille sur sa propre branche, créée à partir de `develop`.
- Chacun dépose son code par Pull Request vers `develop`.
- Personne ne touche à `main` : seule l'architecte y fusionne `develop`, quand tout est testé.
- Chacun modifie uniquement son dossier.
