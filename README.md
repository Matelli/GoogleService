# GoogleService

http://www.mistra.fr/

Sample : [https://github.com/Matelli/GoogleService-Sample](https://github.com/Matelli/GoogleService-Sample)

## Installation

Afin d'integrer cette librairie, rajouter ces lignes dans votre pom.xml

```
<repositories>
	<repository>
    	<id>GoogleService</id>
        <url>https://raw.github.com/Matelli/GoogleService/mvn-repo/</url>
    </repository>
</repositories>
```

```
</dependencies>
	<dependency>
		<groupId>fr.matelli</groupId>
		<artifactId>MatelliGoogleService</artifactId>
		<version>0.1.1</version>
	</dependency>
</dependencies>
```

## Feature

* OAuth 2.0 de Google
* Gestion du Refresh Token
* Service Calendar avec le scope "CalendarScopes.CALENDAR"
   * Création du service Google Calendar
   * Création d'un calendrier
   * Création d'un évenement
   * Abonnement à un calendrier
   * Retourne la liste des calendriers
   * Retourne la liste des évenements d'un calendrier
   * Retourne toutes les informations d'un calendrier
   * Retourne toutes les informations d'un évenement
   * Mise à jour d'un évenement
   * Supprime un évenement d'un calendrier
* Service Drive avec le scope "DriveScopes.DRIVE"
   * Création du service Google Drive
   * Création d'un dossier
   * Recherche de fichier
   * Retourne les métadonnées d'un fichier
   * Récupère une liste de tous les fichiers
   * Création d'un nouveau fichier
   * Supprime un fichier
   * Copie un fichier existant
   * Renommer un fichier
   * Deplace le fichier dans la corbeille
   * Restaure un fichier de la corbeille

## Version

* [0.1.1](https://github.com/Matelli/GoogleService/tree/mvn-repo/fr/matelli/MatelliGoogleService/0.1.1) (2014-05-12)
   * Utilisation du service Calendar avec le scope "CalendarScopes.CALENDAR"
   * Opération de base sur les service Google Drive et Calendar
   * Ajout du support pour OAuth 2.0 de Google
   * Gestion des Refresh Token

## Licence

[![Creative Commons](http://i.creativecommons.org/l/by-sa/3.0/fr/88x31.png)](http://creativecommons.org/licenses/by-sa/3.0/fr/)

Cette librairie est mise à disposition selon les termes de la [Licence Creative Commons Attribution - Partage dans les Mêmes Conditions 3.0 France.](http://creativecommons.org/licenses/by-sa/3.0/fr/)
