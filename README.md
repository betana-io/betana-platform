# betana-platform

Pour regler le probleme de repo avec docker-compose :

- Créer un nouveau repo avec comme dependances les repos de front et de back. Grace a gitsubmodules

- Pour faire fonctionner le repo globale avec les dependances :

1 - git clone git@github.com:betana-io/betana-platform.git // cloner le projet global

2 - cd betana-platform && git submodule init && git submodule update --remote // pour initialiser les dependances du repo et ensuite les clones dans les dossier correspondant

3 - cd "dans chaque dependance" && git checkout main // pour se deplacer dans la bonne branche
