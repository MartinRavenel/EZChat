# EZChat
A basic local chat room

Voici l'application de chat "EZChat" ! Voici comment l'utiliser : 
- extraire tous les fichiers
- compiler tous les fichiers java
- dans un premier terminal, lancer TestServeurSimple.java
- dans plusieurs autres terminaux, lancer ClientSimple.java ou “nc localhost 6000”
- envoyer des messages

Le serveur et les clients ont plusieurs commandes disponibles, qui sont rappelées au choix du pseudo. Pour le serveur : 
- /kick <pseudo> permet d'expulser un utilisateur
- /close permet de fermer le serveur. C'est une option préférable au ctrl + c dans le terminal, qui provoque quelques bugs.

Pour le client :

/name rappel le pseudo choisit du client
/change permet de changer de pseudo
/quit permet de quitter le chat. C'est une option préférable au ctrl + c qui provoque quelques bugs
