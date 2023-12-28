## Ma première connexion
L'application pgAdmin Server vous est fournie avec votre serveur Eole PostgreSQL, en complément à votre base de données. Elle est accessible depuis un navigateur à l'adresse
**http://ip-de-mon-serveur/pgadmin4** et nécessite un 1er compte de connexion.
Ce 1er compte de connexion vous sera fourni par votre service support; il se présente sous la forme **pgadmin@domaine-du-serveur**.

![acceuil](/img/acceuil.png)

Ce compte doit être utilisé comme compte de connexion provisoire, le temps pour vous de déclarer votre propre adresse de messagerie.
Il est conseillé de supprimer ce compte provisoire à l'issue.

## Créer un nouveau compte de connexion
Une fois connecté, outre le menu explicite **Modifier le mot de passe**, l’administrateur dispose d’un menu **Utilisateurs** permettant de déclarer de nouveaux rôles de connexion.

![users](file://img/users.png)

Un compte de connexion pgAdmin est une adresse de messagerie et un mot de passe comportant au moins 6 caractères. Pour ajouter un nouvel
utilisateur à pgAdmin, cliquez sur le bouton + situé en haut et à droite.

![users](file://img/add-users.png)

Vous pouvez alors saisir l'adresse de messagerie du nouveau compte de connexion à pgAdmin, ainsi que le mot de passe associé.
Vous pouvez également préciser quel rôle vous souhaitez associer à ce compte:
* **User** : ce rôle restreint le compte de connexion à la simple modification de son mot de passe en ne lui autorisant que le menu *Modifier le mot de passe*
* **Administrator** : ce rôle permet au compte de connexion la gestion de nouveau compte en lui autorisant le menu *Utilisateurs*

Le rôle *Administrator* autorise le compte de connexion associé :
* à créer de nouveau compte de connexion à pgAdmin
* à activer/désactiver un compte existant en basculant le bouton **Actif***
* à déverrouiller un compte qui aurait été verrouillé suite à 2 tentatives de connexion infructueuse de l'utilisateur


**Rappel** : à l'issue de la création de votre compte de connexion, il est conseillé de supprimer le compte provisoire fourni par le service support.
