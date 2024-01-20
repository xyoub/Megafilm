si vous voulez ce projet telecharger le 
1) supprimer le dossier migration
2) add-migration name
3) update database
Diagramme de classe
![image](https://github.com/xyoub/Megafilm/assets/87517775/993475d8-15ef-41ce-9892-f8af15b1401d)
Les classes du diagramme sont les suivantes :

EFMigrationsHistory : Cette classe représente l'historique des migrations de base de données.
ShoppingCartItems : Cette classe représente les articles dans un panier d'achat.
Producers : Cette classe représente les producteurs de films.
Actors : Cette classe représente les acteurs de films.
Movies : Cette classe représente les films.
Cinemas : Cette classe représente les cinémas.
AspNetUserLogins : Cette classe représente les connexions des utilisateurs.
AspNetUsers : Cette classe représente les utilisateurs.
AspNetUserClaims : Cette classe représente les revendications des utilisateurs.
Orders : Cette classe représente les commandes.
AspNetUserTokens : Cette classe représente les jetons des utilisateurs.
AspNetUserRoles : Cette classe représente les rôles des utilisateurs.
AspNetRoles : Cette classe représente les rôles.
AspNetRoleClaims : Cette classe représente les revendications des rôles.
Les relations entre les classes sont les suivantes :

EFMigrationsHistory : Cette classe est liée à Movies, Cinemas, Actors, Producers, AspNetUsers, Orders, et AspNetRoles. Ces relations représentent l'historique des migrations pour ces classes.
ShoppingCartItems : Cette classe est liée à Movies. Cette relation représente un panier d'achat contenant des films.
Producers : Cette classe est liée à Movies. Cette relation représente un producteur qui a réalisé un film.
Actors : Cette classe est liée à Movies. Cette relation représente un acteur qui a joué dans un film.
Movies : Cette classe est liée à Cinemas. Cette relation représente un film qui est projeté dans un cinéma.
Movies : Cette classe est liée à Actors. Cette relation représente les acteurs qui ont joué dans un film.
Movies : Cette classe est liée à Producers. Cette relation représente le producteur qui a réalisé un film.
AspNetUserLogins : Cette classe est liée à AspNetUsers. Cette relation représente les connexions d'un utilisateur.
AspNetUsers : Cette classe est liée à AspNetUserClaims. Cette relation représente les revendications d'un utilisateur.
AspNetUsers : Cette classe est liée à Orders. Cette relation représente les commandes d'un utilisateur.
AspNetUsers : Cette classe est liée à AspNetUserTokens. Cette relation représente les jetons d'un utilisateur.
AspNetUsers : Cette classe est liée à AspNetUserRoles. Cette relation représente les rôles d'un utilisateur.
AspNetUserRoles : Cette classe est liée à AspNetRoles. Cette relation représente les rôles d'un utilisateur.
AspNetRoles : Cette classe est liée à AspNetRoleClaims. Cette relation représente les revendications d'un rôle.
Voici quelques exemples de relations entre les classes :

Un film peut avoir plusieurs producteurs.
Un film peut avoir plusieurs acteurs.
Un film peut être projeté dans plusieurs cinémas.
Un utilisateur peut avoir plusieurs connexions.
Un utilisateur peut avoir plusieurs revendications.
Un utilisateur peut passer plusieurs commandes.
Un utilisateur peut avoir plusieurs jetons.
Un utilisateur peut avoir plusieurs rôles.
Un rôle peut avoir plusieurs revendications.
Ce diagramme est un outil utile pour comprendre la structure d'un système de gestion de cinéma. Il permet de visualiser les classes et leurs relations, ce qui peut aider à comprendre comment le système fonctionne.
![image](https://github.com/xyoub/Megafilm/assets/87517775/6c1a0784-84a0-4efb-96cc-2043af20ed34)
![image](https://github.com/xyoub/Megafilm/assets/87517775/c0452003-10b7-4418-84c4-8c753b1a72a6)
![image](https://github.com/xyoub/Megafilm/assets/87517775/69456563-6bc9-4e0c-839e-c99ee75b5476)
![image](https://github.com/xyoub/Megafilm/assets/87517775/921220cd-5e3b-40a5-ab5e-061ec736998f)
![image](https://github.com/xyoub/Megafilm/assets/87517775/d66b1d31-b9a5-41e9-bff9-6b45f7716a89)
![image](https://github.com/xyoub/Megafilm/assets/87517775/5d9527c0-0a0f-4749-8db9-8ab7efe38831)
![image](https://github.com/xyoub/Megafilm/assets/87517775/b66734fa-68b6-402b-a6ed-741586c0fd41)
![image](https://github.com/xyoub/Megafilm/assets/87517775/07ebd05f-e63c-4a91-b60b-2a9bc6d6757e)







