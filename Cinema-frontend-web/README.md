<b>Objectif de ce Tp : </b> 

Le but de ce tp est de la conception et la création d’une application web qui permet de gérer des cinémas.<br>
•	Chaque cinéma se trouvant dans une ville est défini par son code, son nom et sa position géographique. <br>
•	Le cinéma contient un ensemble de salles.<br>
•	Chaque salle qui est définie par son numéro, son nom contient un ensemble de places.<br>
•	 Chaque place a un numéro et positionnée géographiquement.<br>
•	Quotidiennement, on programme plusieurs projections de films dans des salles.<br>
•	Chaque Projection se déroule dans une séance, concerne un Film et se déroule dans une Salle à un date de projection et un prix fixe.<br>
•	Chaque séance est définie par son numéro et l’heure de début e la séance.<br>
•	Chaque projection on prévoie un ensemble de Tickets.<br>
•	Chaque Ticket concerne une Place et défini par le nom du client, le prix du ticket et le code payement.<br>
•	Les films sont classés par catégories<br>

<b>L’architecture de l’application :</b> 

L’application se compose de 2 Parties : La partie backend et la partie Frontend.<br>

La partie backend est basée sur Spring Boot et se compose des couches DAO, Service (Métier) et Web.<br>
• La couche DAO est basée sur Spring Data, JPA, Hibernate<br>
• La couche Métier est définie par une interface et une implémentation quelques spécifications fonctionnelles qui nécessite des calculs ou des traitements particuliers <br>
• La couche Web est basée sur des API Restful basée sur Spring Data Rest ou des RestController<br>

La partie Frontend est basée sur le Framework Angular.<br>
La sécurité est basée sur Spring Security et Json Web Token


# CinemaFrontWeb

Ce projet est généré par [Angular CLI](https://github.com/angular/angular-cli) version 12.1.1.

## Serveur de développement

Exécutez `ng serve` pour un serveur de développement. Accédez à `http://localhost:4200/`. L'application se rechargera automatiquement si vous modifiez l'un des fichiers sources.


## Build

Exécutez `ng build` pour générer le projet. Les artefacts de construction seront stockés dans le répertoire `dist/`.

## Exécuter des tests unitaires

Exécutez `ng test` pour exécuter les tests unitaires via [Karma](https://karma-runner.github.io).


## Aide supplémentaire

Pour obtenir plus d'aide sur Angular CLI, utilisez `ng help` ou consultez la page [Angular CLI Overview and Command Reference] (https://angular.io/cli).
