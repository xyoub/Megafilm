si vous voulez ce projet telecharger le 
1) supprimer le dossier migration
2) add-migration name
3) update database
Diagramme de classe
![image](https://github.com/xyoub/Megafilm/assets/87517775/993475d8-15ef-41ce-9892-f8af15b1401d)
Les classes du diagramme sont les suivantes :

# Diagramme des relations de la base de données du système de gestion de cinéma

## Classes

- **EFMigrationsHistory:** Historique des migrations de la base de données.

- **ShoppingCartItems:** Articles dans un panier d'achat.

- **Producers:** Producteurs de films.

- **Actors:** Acteurs de films.

- **Movies:** Films.

- **Cinemas:** Cinémas.

- **AspNetUserLogins:** Connexions des utilisateurs.

- **AspNetUsers:** Utilisateurs.

- **AspNetUserClaims:** Revendications des utilisateurs.

- **Orders:** Commandes.

- **AspNetUserTokens:** Jetons des utilisateurs.

- **AspNetUserRoles:** Rôles des utilisateurs.

- **AspNetRoles:** Rôles.

- **AspNetRoleClaims:** Revendications des rôles.

## Relations

- EFMigrationsHistory est lié à Movies, Cinemas, Actors, Producers, AspNetUsers, Orders, et AspNetRoles, représentant l'historique des migrations pour ces classes.

- ShoppingCartItems est lié à Movies, représentant un panier d'achat contenant des films.

- Producers est lié à Movies, représentant un producteur qui a réalisé un film.

- Actors est lié à Movies, représentant un acteur qui a joué dans un film.

- Movies est lié à Cinemas, représentant un film projeté dans un cinéma.

- Movies est lié à Actors, représentant les acteurs qui ont joué dans un film.

- Movies est lié à Producers, représentant le producteur qui a réalisé un film.

- AspNetUserLogins est lié à AspNetUsers, représentant les connexions d'un utilisateur.

- AspNetUsers est lié à AspNetUserClaims, représentant les revendications d'un utilisateur.

- AspNetUsers est lié à Orders, représentant les commandes d'un utilisateur.

- AspNetUsers est lié à AspNetUserTokens, représentant les jetons d'un utilisateur.

- AspNetUsers est lié à AspNetUserRoles, représentant les rôles d'un utilisateur.

- AspNetUserRoles est lié à AspNetRoles, représentant les rôles d'un utilisateur.

- AspNetRoles est lié à AspNetRoleClaims, représentant les revendications d'un rôle.

## Exemples de relations

- Un film peut avoir plusieurs producteurs.

- Un film peut avoir plusieurs acteurs.

- Un film peut être projeté dans plusieurs cinémas.

- Un utilisateur peut avoir plusieurs connexions.

- Un utilisateur peut avoir plusieurs revendications.

- Un utilisateur peut passer plusieurs commandes.

- Un utilisateur peut avoir plusieurs jetons.

- Un utilisateur peut avoir plusieurs rôles.

- Un rôle peut avoir plusieurs revendications.

![image](https://github.com/xyoub/Megafilm/assets/87517775/6c1a0784-84a0-4efb-96cc-2043af20ed34)
![image](https://github.com/xyoub/Megafilm/assets/87517775/c0452003-10b7-4418-84c4-8c753b1a72a6)
![image](https://github.com/xyoub/Megafilm/assets/87517775/69456563-6bc9-4e0c-839e-c99ee75b5476)
![image](https://github.com/xyoub/Megafilm/assets/87517775/921220cd-5e3b-40a5-ab5e-061ec736998f)
![image](https://github.com/xyoub/Megafilm/assets/87517775/d66b1d31-b9a5-41e9-bff9-6b45f7716a89)
![image](https://github.com/xyoub/Megafilm/assets/87517775/5d9527c0-0a0f-4749-8db9-8ab7efe38831)
![image](https://github.com/xyoub/Megafilm/assets/87517775/b66734fa-68b6-402b-a6ed-741586c0fd41)
![image](https://github.com/xyoub/Megafilm/assets/87517775/07ebd05f-e63c-4a91-b60b-2a9bc6d6757e)







