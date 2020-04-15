# php-socket-on-alwaysdata-with-rachet
Après des heures de recherche, j'ai enfin trouver comment faire mes sockets avec PHP sur ALWAYSDATA

Dans la configuration de alwaysdata :
-> ajouter un site -> programme utilisateur
dans adresse mettez par exemple : ws.example.fr, cette adresse doit etre utilisé pour se connecter avec websocket dans index.html et plus specifiquement dans le script : 

var conn = new WebSocket('wss://ws.example.fr');

Dans commande : php /home/xxxxxx/www/chemin/vers/cmd.php
CMD.PHP doit lancer le serveur sur le port 8100 !
et voilà, tout simplement :D

Sujet qui m'on aider :o 
https://forum.alwaysdata.com/viewtopic.php?id=5023
