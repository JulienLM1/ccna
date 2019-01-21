TP 3 - Plusieurs réseaux : routage statique
I. Création et utilisation simples d'une VM CentOS
4. Configuration réseau d'une machine CentOS
a. On utilise la commande curl qui permet de faire des requêtes HTTP pour montrer que l'on a internet.

![](https://i.imgur.com/32SF3OI.png)!


b. On ping notre VM depuis notre PC et inversement.

![](https://i.imgur.com/gsMiD3P.png)
![](https://i.imgur.com/ceR2xge.png)


c. On utilise la commande route print -4 sur notre PC et ip route sur notre VM pour afficher la table de routage.

![](https://i.imgur.com/av3mp2j.png)
![](https://i.imgur.com/dBJZGiX.png)


5. Faire joujou avec quelques commandes
Pour le ping et la table de routage, cf. ci-dessus.

Pour télécharger un fichier on utilise curl:

![](https://i.imgur.com/58cO49j.png)



Pour connaître l'adresse IP d'un site, on utilise dig:

![](https://i.imgur.com/CuPEbx7.png)
![](https://i.imgur.com/JeqZP6p.png)




II. Notion de ports et SSH
1. Exploration des ports locaux
Utilisez la commande ss pour lister les ports TCP sur lesquels la machine virtuelle écoute. Ajoutez l'option :

-t pour avoir les ports TCP
-l pour avoir les ports en écoute
-n pour avoir le numéro du port, plutôt qu'un nom
-p pour connaître l'application qui écoute sur ce port




![](https://i.imgur.com/XnvVnKQ.png)
