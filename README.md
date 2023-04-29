<h2> Gestion sécurisée des patients </h2>
Gestion sécurisée des patients est une application web JEE simple qui permet aux utilisateurs de gérer les patients de manière sécurisée. Elle a été développée à l'aide du framework Spring MVC, Thymeleaf, Spring Data JPA et Spring Security.

<h3> Fonctionnalités </h3>
Les principales fonctionnalités de cette application incluent:

- Création, mise à jour et suppression de patients
- Affichage des informations des patients
- Recherche de patients par nom 
- Authentification des utilisateurs avec Spring Security
<h3> Installation </h3>
*`Pour installer l'application, vous devez d'abord cloner le dépôt Github sur votre machine locale`. Vous pouvez le faire en exécutant la commande suivante dans votre terminal:

```bash
git clone https://github.com/chifaabelmaaza/secured_patient_app.git
```

*`Ensuite, vous devez créer une base de données MySQL` appelée *`gestion_patients` et mettre à jour le fichier *`application.properties` avec les informations de connexion à la base de données.

*`Vous devez également configurer Spring Security` en mettant à jour les fichiers *`SecurityConfig.java` et *`WebSecurityConfig.java` avec les informations d'authentification appropriées.

* `Enfin, vous pouvez exécuter l'application` en exécutant la commande suivante à la racine du projet:

```bash
mvn spring-boot:run
```

L'application sera ensuite accessible à l'adresse suivante:

```bash
http://localhost:8082/
```

<h3> Utilisation </h3>
Une fois que l'application est en cours d'exécution, vous pouvez l'utiliser pour ajouter, mettre à jour ou supprimer des patients, rechercher des patients par nom. Vous pouvez également vous connecter à l'application en utilisant vos informations d'authentification.
