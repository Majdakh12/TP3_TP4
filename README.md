Lien Github: https://github.com/Majdakh12/TP3_TP4.git

# TP3
La dépendance Web est une dépendance qui permet à une application de se connecter à un serveur web pour récupérer des données ou des services. Elle permet à l'application de communiquer avec une API web pour accéder à des informations telles que des images, des vidéos, des textes ou des données enregistrées sur un serveur distant. Elle permet également de soumettre des informations à une API web pour stocker ou mettre à jour des données sur un serveur distant. En résumé, la dépendance Web permet à une application de se connecter à un serveur web pour échanger des données et des services.

JPA (Java Persistence API) est une spécification Java qui fournit un moyen de gérer les données de base de données dans une application Java. Elle permet de mapper les objets Java aux tables de la base de données, de gérer les transactions et de créer des requêtes pour récupérer des données depuis la base de données. La dépendance JPA simplifie la gestion des données en utilisant des concepts objet-relationnel, tels que les entités, les relations, les requêtes et les transactions, plutôt que de devoir écrire du code SQL. En résumé, la dépendance JPA est une spécification Java qui permet de gérer les données de base de données dans une application Java en utilisant des concepts objet-relationnel.

Hibernate est une implémentation de la spécification JPA (Java Persistence API) qui permet de gérer les données de base de données dans une application Java. Il fournit une couche d'abstraction pour gérer les interactions avec la base de données, en utilisant des concepts objet-relationnel, tels que les entités, les relations, les requêtes et les transactions. Il permet de mapper les objets Java aux tables de la base de données, de gérer les transactions et de créer des requêtes pour récupérer des données depuis la base de données. Hibernate est un framework très populaire et largement utilisé pour la persistance des données dans les applications Java. En résumé, Hibernate est une implémentation de JPA (Java Persistence API) qui permet de gérer les données de base de données dans une application Java en utilisant des concepts objet-relationnel.

H2 est un système de gestion de base de données relationnel open-source écrit en Java. Il peut être utilisé comme une base de données embarquée dans une application Java ou comme une base de données autonome à l'aide d'un serveur. Il prend en charge les principaux standards de SQL, tels que les tables, les vues, les index, les contraintes et les transactions. Il est léger, rapide et facile à utiliser, et peut être intégré facilement dans des applications Java. H2 est souvent utilisé pour des tests et des développements en local, puisque il est facile à configurer et à utiliser. Il est également utilisé dans des applications qui nécessitent une base de données embarquée pour des raisons de performance ou de facilité d'utilisation. En résumé, H2 est un système de gestion de base de données relationnel open-source écrit en Java, souvent utilisé pour des tests et des développements en local ou pour des applications qui nécessitent une base de données embarquée.

DevTools (Outils de développement) est une dépendance fournie par Spring Boot qui permet de faciliter le développement et le débogage d'une application web. Il offre une variété de fonctionnalités telles que la possibilité de redémarrer automatiquement l'application lorsqu'un fichier est modifié, la possibilité de visualiser les requêtes HTTP et les réponses, la possibilité de visualiser les beans Spring, les propriétés et les configurations. Il permet également de visualiser les performances de l'application, les journaux et les erreurs, et de déboguer l'application en utilisant des outils tels que le débogueur intégré. En résumé, DevTools est une dépendance Spring Boot qui permet de faciliter le développement et le débogage d'une application web en offrant une variété de fonctionnalités pour une visualisation rapide et une résolution des problèmes.

Thymeleaf est un moteur de template open-source pour générer des pages web statiques ou dynamiques. Il peut être utilisé pour créer des modèles pour les applications web basées sur Spring. Il permet de créer des vues en utilisant des balises XML/XHTML/HTML5 standard, qui sont ensuite remplacées par des données dynamiques provenant du contrôleur. Il offre un grand nombre de fonctionnalités telles que la possibilité de créer des vues conditionnelles, des boucles, des formulaires, des liens, des commentaires, des traductions, des fragments de vue, etc. Il est compatible avec les principaux navigateurs web et prend en charge les principaux standards de l'industrie. En résumé, Thymeleaf est un moteur de template open-source qui permet de créer des vues pour les applications web basées sur Spring en utilisant des balises standard et en offrant une variété de fonctionnalités pour les formater et les afficher de manière dynamique.

question 13:
1-L'URL d'appel "/greeting" est paramétrée avec l'annotation @GetMapping("/greeting") de la méthode greeting().

2-Le fichier HTML à afficher est choisi en utilisant la valeur de retour de la méthode greeting qui est "greeting". Cette valeur est utilisée comme nom de la vue pour le moteur de template.

3-Le nom à qui nous disons bonjour est envoyé via le paramètre de requête "nameGET" qui est récupéré dans la méthode greeting() et ajouté à l'objet Model en utilisant l'attribut "nomTemplate" qui est utilisé par la vue pour afficher le nom de la personne à qui on souhaite dire bonjour

question 19:
oui création de la table adresse.

question 20:
oui. on voit bien la table

question 22:
L'annotation @Autowired en Spring est utilisée pour injecter automatiquement une dépendance dans une classe en utilisant le conteneur de beans Spring.

---------------------------------------------------------------------------------------------
TP4:

6-1 Faut-il une clé API pour appeler MeteoConcept ?
Non, il suffit de récupérer la météo d'un lieu visé par des coordonnées GPS

6-2 Quelle URL appeler ?
via l'URL suivante : https://api.meteoconcept.com/v1/forecast/locale/{latitude},{longitude}

6-3  Quelle méthode HTTP utiliser ?
La méthode HTTP à utiliser est GET.

6-4 Comment passer les paramètres d'appels ?
Pour passer les paramètres d'appel, il faut les inclure dans l'URL, comme indiqué ci-dessus.

6-6 Où est l'information dont j'ai besoin dans la réponse :
Pour afficher la température du lieu visé par les coordonnées GPS, on accéde à l'information dans la réponse à l'URL suivante : https://api.meteoconcept.com/v1/forecast/locale/{latitude},{longitude}/temp

6-7 Pour afficher la prévision de météo du lieu visé par les coordonnées GPS
Pour afficher la prévision de météo du lieu visé par les coordonnées GPS, on accéde à l'information dans la réponse à l'URL suivante : https://api.meteoconcept.com/v1/forecast/locale/{latitude},{longitude}/forecast
