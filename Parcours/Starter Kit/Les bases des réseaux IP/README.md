# Les bases des réseaux IP

## __1:Une image du modèle OSI ainsi qu'une brève description. Pour chaque couche du modèle OSI, donnez des exemples__

![1_-hQHFX-UjlruHDf9Je0lXg](https://user-images.githubusercontent.com/112661363/190869289-84100f51-9a2e-4aa4-9b43-54a2c4c9b753.png)

Le modèles OSI, l'Open System Interconnexion est un modèle qui permet de comprendre les interactions entre les protocoles à travers les 7 couches qui le composent :

Il y a d'abord la première couche, la couche physique, représentée par les câbles, la fibre optique, ou encore les ondes.

La deuxième couche est la couche liaison, représentée par le protocole ethernet.

La troisième couche, la couche réseau est représentée par les adresses IP.

La quatrième couche est la couche transpot, représentée par les UDP (User Datagram Protoclol) et TCP (Transmission Control Protocol)

La cinquième couche est la couche session, représentée par de multiples sessions.

La sixième couche est la couche présentation, représentée par l'encryption (qui permet d'encoder des imformations) et HTTP.

La dernière couche est la couche application et est représentée par Intenret, Chrome etc.

---

## __2:Citez le nom de l'autre modèle couramment utilisé et joindre une photo__

Le modèle TCP / IP est souvent utilisé.

![OIP](https://user-images.githubusercontent.com/112661363/190890500-8884e458-9da8-4659-9138-77311ac8269a.jpg)

---

## __3:Qu’est ce qu’un LAN ? Citez des exemples de LAN__

Le LAN : le Local Area Network désigne un réseau d'une étendue limitée, utilisé donc dans un espace limité, intérieur, c'est à dire dans des domiciles privés par exemple, pour avoir un réseau local, intérieur.

C'est notament un port que l'on branche sur un routeur pour pouvoir communiquer avec les autres ( dans un espace donc privé, limité )

Donc pour exemple de LAN ou pourrait avoir un réseau dans un domicile par exemple avec tout les appareils branchés, des ordinateurs, qui peuvent communiquer ensemble grâce au LAN.

Il est aussi utilisé dans des entrteprises par exemple, et ceci est le même principe, un réseau privé avec tout les appareils branchés qui peuvent communiquer ensemble.

## __4:Dans la vidéo, on mentione l’adresse MAC. Expliquez en détail son utilité. Cette adresse est codée sur 48 bits en Hexadécimal. Après quelques recherches, expliquez ce qu’est un bit, un octet__

L'adresse MAC (Media Acess Control ) est une adresse qui est unique à chaque appreil, suivant la postion qu'il a. Chaque appareil a une position spécifique, donc une adresse MAC spécifique.C'est donc l'adresse physique d'un équipement.

Le bit est une unité d'information pouvant prendre la valeur 0 ou la valeur 1. C'est la quantité minimale d'information transmise par un message, et constitue à ce titre l'unité de mesure de base de l'information en informatique. Il est en base 2, la base binaire et n'utilise donc que deux chiffres. 0 ou 1.

Un octet est un groupe de 8 bits, qui permet de coder jusqu'à 256 caractères différents. Il permet de coder des informations.

## __5:Egalement, on parle d’hexadécimal. Après recherches, donnez l’équivalent hexadécimal du nombre décimal 58, 40, 3, et 146. Vous pouvez vous aider d’un convertisseur en ligne. Vous apprendrez dans une prochaine activité comment passer de la notation décimal à hexadécimal ou binaire.__

0D 58 = 0H 3A

0D 40 = 0H 28

0D 3 = 0H 3

0D 146 = 0H 92

## __6:Donner la définition d’un réseau WAN.__

Le WAN, Wide Area Network, est un réseau d'une plus grande étendue que le LAN, qui s'étant sur une plus grande zones géographiques et qui relie plusieurs réseaux de type LAN, et qui permet ainsi la communication entre plusieurs réseaux privés, intérieurs, car le WAN est un réseau de type extérieur, étendu.

## __7:L’adresse IP la plus couramment utilisée pour nos box internet à la maison est : 192.168.1.1. Donner l’écriture binaire de cette adresse IP (vous pouvez vous aider d’un convertisseur en ligne)__

1 1 0 0 0 0 0 0 . 1 0 1 0 0 0 0 1 . 0 0 0 0 0 0 0 1 . 0 0 0 0 0 0 0 1 

## __8:Donnez deux exemples d’adresses IPv4 privéés de classe C. Les périphériques porteurs de ces adresses peuvent ils cohabiter sur le même réseau ?__

192.168.1.0

192.168.1.1

192.168.1.255

Oui ils peuvent cohabiter sur le même réseau car il y aura une adresse publique différente.

## __9:Renseignez vous sur la notation CIDR. Comment écrit on le masque 255.255.255.0 en notation CIDR ?__

/24

car la partie réseau correspond aux 24 bits les plus à gauche.

## __10:Rappeler ce que signifie DNS et son utilité__

DNS, Domain Name Server. C'est grâce au DNS que la connexion s'établit car le DNS se charge de trouver la bonne adresse IP à chaque demande que nous allons faire au routeur, pour établir la connexion. Sans lui il faudrait à chaque fois rentrer l'adresse IP dont nous avons besoin de nous-même.

## __11:Rappeler ce que signifie DHCP et son utilité__

DHCP, Dynamic Host Configuration Protocol. C'est un processus qui permet d'obtenir une adresse IP quand on ne l'a pas et que l'on veut se connecter à un réseau. C'est le meilleur protocole des 3 couches car il fait une relation entre les 3. Par exemple, je branche mon pc ( couche 1 ), je veux établir une connexion ( couche 2 ) mais je n'ai pas d'adresse IP donc le DHCP va demander une adresse IP et la trouver. ( liaison avec couche 2 car il va lui donner l'adresse IP )

## __12:Dans la vidéo, un test est effectué en ligne de commande (« ipconfig ») pour voir la configuration IP de l’ordinateur. Exécutez cette commande sur votre PC et joignez une capture d’écran__

![Capture d’écran (27)](https://user-images.githubusercontent.com/112661363/190895998-21cf0176-b98c-40a8-b77b-5e8b80138529.png)

## __13:Quelle adresse IP nous indique un problème de configuration IP ?__

192.168.1.1

## __14:Rappelez le port par défaut pour le protocole HTTP, HTTPS, FTP, SSH, Telnet, POP et SMTP. Pour chacun d’entre eux, expliquer brièvement leur utilité__

HTTP = port 80, HTTPS = 443, FTP = 21, SSH = 22, Telnet = 23, POP = 110, SMTP = 25.

Le sigle HTTP signifie "protocole de transfert hypertexte". Plus simplement, il désigne le protocole utilisé sur Internet pour transmettre les pages web. Sa principale utilisation est la consultation de serveurs web.

L’intérêt principal du HTTPS est de garantir la sécurité des utilisateurs ainsi que des données que nous échangeons. En effet, cette sécurité empêche les attaques du type Man In The Middle

Le ftp (File Transfer Protocol) est le protocole de transfert de fichiers. Autrement dit, ce protocole permet d'envoyer des fichiers de son disque dur vers un serveur distant.

 Secure Shell (SSH) est un norme logicielle pour prendre en charge le transfert de données cryptées entre deux ordinateurs. Il peut être utilisé pour prendre en charge des connexions sécurisées, des transferts de fichiers ou des connexions à usage général.
 
Telnet (terminal network ou telecommunication network, ou encore teletype network) est un protocole utilisé sur tout réseau TCP/IP, permettant de communiquer avec un serveur distant en échangeant des lignes de texte et en recevant des réponses également sous forme de texte.

 le POP (Post Office Protocol) est un protocole qui permet de récupérer les courriers électroniques situés sur un serveur de messagerie électronique. En dehors d'un paramétrage spécifique, POP se connecte au serveur de messagerie, s'authentifie, récupère le courrier, peut effacer le courrier sur le serveur, et se déconnecte.
 
 Le protocole SMTP (Simple Mail Transfer Protocol) est utilisé pour transmettre des messages électroniques sur Internet. Ce protocole est utilisé par la plupart des clients de messagerie pour remettre des messages au serveur, et est également utilisé par les serveurs pour transférer les messages vers leur destination finale.
 
## __15:Listez les différents outils de dépanage cités dans la vidéo. Pour chacun d’entre eux, essayer la commande dans votre invite de commande Windows et joindre une capture d’écran du résultat. (Pour le ping, faites un ping de google.fr, idem pour tracert)__

![Capture d’écran (28)](https://user-images.githubusercontent.com/112661363/190897228-3870197c-235d-4992-8058-cd5dfe3fe8e7.png)

![Capture d’écran (29)](https://user-images.githubusercontent.com/112661363/190897231-09191f4d-39b7-4af8-a745-23f1ea2bb3e5.png)

![Capture d’écran (30)](https://user-images.githubusercontent.com/112661363/190897244-c3cd8f21-dc19-4ce7-8a84-c9deb60f5b62.png)

![Capture d’écran (31)](https://user-images.githubusercontent.com/112661363/190897267-f555a362-0a1c-43df-b9c6-8208cfce6ee6.png)

## __16:Pour chacune des commandes réseau Windows listées ci-dessus, donnez l'équivalent pour Linux__


## __17:Prendre une capture d'écran de la fin de la vidéo résumant les différentes couches avec les exemples.__

![Capture d’écran (32)](https://user-images.githubusercontent.com/112661363/190897408-e7caba21-5e0e-4b60-8946-728b65699f94.png)






