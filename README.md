# Ateliers ML

## Installation de l'environnement avec docker

Pour pouvoir installer l'environnement requis pour ces ateliers avec docker, il faut:
- Installer docker _(no shit sherlock...)_. J'utilise docker-machine, c'est pourquoi les IP en dessous sont de la forme `192.168.99.100` et non `localhost`.
- Installer docker-compose. `pip3 install docker-compose` (python3 doit être installé)
- Une fois docker prêt à l'emploi, taper `docker-compose up -d jupyter && sleep 2 && docker exec ml jupyter notebook list`.
- Vous pouvez maintenant aller prendre une petite pause (non pas que tout ce travail accompli est éreintant, mais la phase d'installation prend facilement 10 minutes).
- La phase d'installation passée, vous aurez un token affiché dans votre terminal. Il vous suffit juste de le copier dans votre presse-papier, accéder à [votre notebook](http://192.168.99.100:8888), coller votre token dans le champ en haut, et c'est parti !


![](https://media.giphy.com/media/BdrSy2gqURFEk/giphy.gif)
