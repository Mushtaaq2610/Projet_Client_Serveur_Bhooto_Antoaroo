# Projet_Client_Serveur_Bhooto_Antoaroo

## Client Serveur
Introduction :
Le projet est de créer une connexion entre un client et un serveur ou on peut faire plusieurs requêtes de commande et ensuite le serveur l’exécutera.


## Fonctionnalité

- Le client fait sa demande au serveur comme un fichier, une liste des fichiers, effacer.
- Le serveur attend le client et répond aux demandes du client.
- Le serveur peut recevoir des demandes spécifiques d'une répertoire indiquez

## Compiler
- Entrez dans - cd bin
- Ecrivez - cmake ..
- Puis ecrivez - make


## Exécution
Pour lancer la programmation du projet on doit :
Premièrement il faut lancer le program serveur en utilisant les codes suivants :
sh
./serveur


Ensuite il faut lancer le program client pour pouvoir faire notre demande.
Si l'utilisateur ne mets pas d'IP adresse automatiquement il prend l'IP host local.

sh
./client 127.0.0.1


## Utiliser
### Client
Comment le program fonctionne et comment faire la demande.
Étape 1: Demande quelle commande allez-vous exécuter.

sh
SELECT A MODE
1)Find a Specific Files in a The Server Directory
2)List all Files from The Server Directory
3)Remove a File from The Server Directory
4)Exit the connection


Étape 2: Vous indiquez quelle commande vous chosiez

sh
Select 1/2/3/4
2


Étape  3: Inserez le répertoire du fichier que vous voulez modifier/utiliser

sh
Enter the path to the file : ../resources



Vu que la commande 2 est lister les fichiers dans le dossier ressources voici le résultat.

sh
.
..
test2.txt

### Serveur
Pendant qu'on lancez le serveur le message afficher sera:
sh
Listen
