1-Architecture global de l'application :

Modèle-vue-contrôleur(MVC):

 ou MVC est un motif d'architecture logicielle destiné aux interfaces graphiques lancé en 1978 et très populaire pour
 les applications web. 
Le motif est composé de trois types de modules ayant trois responsabilités 
différentes : les modèles, les vues et les contrôleurs.

Un modèle (Model) contient les données à afficher.
Une vue (View) contient la présentation de l'interface graphique.
Un contrôleur (Controller) contient la logique concernant les actions effectuées par l'utilisateur.
Ce motif est utilisé par de nombreux frameworks pour applications web tels que Ruby on Rails, Django,
 ASP.NET MVC, Spring, Struts, Symfony, Apache Tapestry ou Angular Js.

Java Platform, Enterprise Edition, Java EE:

est une spécification pour la plate-forme Java d'Oracle, destinée aux applications d'entreprise La plate-forme étend
 Java Platform, Standard Edition (Java SE) en fournissant une API de mapping objet-relationnel, des architectures
 distribuées et multitiers, et des services web3. La plate-forme se fonde principalement sur des composants
 modulaires exécutés sur un serveur d'applications.

Spring API :

framework Spring est une boite à outils très riche permettant de structurer, d'améliorer et de simplifier 
l'écriture d'application JEE. Spring est organisé en module

Gestion des instances de classes (JavaBean et/ou métier),
Programmation orientée Aspect,
Modèle MVC et outils pour les application WEB,
Outils pour la DAO (JDBC),
Outils pour les ORM (Hibernate, iBatis, JPA, ...),
Outils pour les applications JEE (EJB, JTA, Servlet, JSP, ...),

Pourquoi utiliser le modèle Spring MVC ?

Le modèle MVC vous permet d’être plus efficient en vous donnant la possibilité de réutiliser le même code plusieurs 
fois dans d’autres applications similaire à celle que vous avez et ainsi que de séparer votre structure en multiple
 calques. Cette combinaison vous offre une meilleure maintenance de votre projet et vous facilite la tâche durant 
les tests unitaires & vous permet de travailler à plusieurs sur un même projet (ex : Le développeur back-end peut 
mettre en place la structure sans intervenir sur le front-end, vice-versa).

Un autre avantage est le fait qu’il y a peu d’accrochage entre les vues, les modèles et les contrôleurs,
 ce qui vous permet d’avoir un code propre où les fonctions & les classes peuvent être facilement réécrite 
& optimisé.

2-Architecture de la Couche Donnée :

SGBD relationalle :

Un SGBD (Système de Gestion de Bases de Données) est un logiciel qui stocke des données de façon organisées et cohérentes. Un SGBDR (Système de Gestion de Bases de Données Relationnelles) est le type particulier de SGBD qui fera l’objet de ce TP. 

Les bases de données les plus répandues sont :

Oracle, qui est considéré comme un des SGBDR les plus performants.
Microsoft SQL Server, la mouture de microsoft, qui est intégré au framework .NET.
mySQL, un logiciel libre fonctionnant souvent de pair avec Apache et Php, et de ce fait très répandu dans la programmation web.
Access, incorporé à Microsoft Office. Il présente l’énorme avantage de mettre à disposition de l’utilisateur une interface graphique. En contrepartie il est mono-utilisateur et de faible capacité. 

Dans notre Mini projet nous utilisons MySql pour stoquer les données temporarement aprés la conversion de fichier .

3-La maniére de gestion des demandes des clients :
pour cette partie on utilise l'architecture client serveur parceque la procedure de conversations des documents et les documents   luis méme sont centralise au niveau du serveur pour que le serveur doit jeres les conversations des client 





