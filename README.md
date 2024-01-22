# Projet Banque

Ce projet est une application de gestion de comptes bancaires. Il est développé en Java avec le framework Spring Boot et utilise une base de données SQL.

## Technologies utilisées

- Java
- Spring Boot
- SQL
- Maven

## Fonctionnalités

- Gestion des clients : création, mise à jour et récupération des informations des clients.
- Gestion des comptes : création, mise à jour et récupération des informations des comptes.
- Gestion des transactions : création et récupération des transactions.

## Installation

1. Clonez ce dépôt sur votre machine locale.
2. Assurez-vous d'avoir installé Java et Maven sur votre machine.
3. Ouvrez le projet dans votre IDE préféré (par exemple, IntelliJ IDEA).
4. Exécutez le fichier `src/main/java/fr/uphf/projet/Application.java` pour démarrer l'application.

## Utilisation

L'application expose plusieurs endpoints REST pour interagir avec les données. Voici quelques exemples :

- `POST /clients` : crée un nouveau client.
- `GET /clients?nom={nom}&prenom={prenom}` : récupère les informations d'un client spécifique.
- `PUT /clients` : met à jour les informations d'un client spécifique.
- `POST /comptes/{IBAN}/cartes` : crée une nouvelle carte pour un compte spécifique.

## Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.
