0-Membres :

Zouggar Ayoub
Layadi Ahmed
Aloui Abderrahmane

1-Architecture global de l'application :
A- cotée client :

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

Pourquoi utiliser le modèle Spring MVC ?

Le modèle MVC vous permet d’être plus efficient en vous donnant la possibilité de réutiliser le même code plusieurs 
fois dans d’autres applications similaire à celle que vous avez et ainsi que de séparer votre structure en multiple
 calques. Cette combinaison vous offre une meilleure maintenance de votre projet et vous facilite la tâche durant 
les tests unitaires & vous permet de travailler à plusieurs sur un même projet (ex : Le développeur back-end peut 
mettre en place la structure sans intervenir sur le front-end, vice-versa).

Un autre avantage est le fait qu’il y a peu d’accrochage entre les vues, les modèles et les contrôleurs,
 ce qui vous permet d’avoir un code propre où les fonctions & les classes peuvent être facilement réécrite 
& optimisé.

B-Coté serveur ou fourniseur de servise :

Java ( pour programmé les web services de notre application) :est un langage de programmation orienté objet créé par James Gosling et Patrick Naughton, employés de Sun Microsystems, avec le soutien de Bill Joy (cofondateur de Sun Microsystems en 1982), présenté officiellement le 23 mai 1995 au SunWorld.

en utilise un framework java pour Converter les documents qui s'appele ASPOSE API 


2-Architecture de la Couche Donnée :

SGBD relationalle :

Un SGBD (Système de Gestion de Bases de Données) est un logiciel qui stocke des données de façon organisées et cohérentes. Un SGBDR (Système de Gestion de Bases de Données Relationnelles) est le type particulier de SGBD qui fera l’objet de ce TP. 

Les bases de données les plus répandues sont :

Oracle, qui est considéré comme un des SGBDR les plus performants.
Microsoft SQL Server, la mouture de microsoft, qui est intégré au framework .NET.
mySQL, un logiciel libre fonctionnant souvent de pair avec Apache et Php, et de ce fait très répandu dans la programmation web.
Access, incorporé à Microsoft Office. Il présente l’énorme avantage de mettre à disposition de l’utilisateur une interface graphique. En contrepartie il est mono-utilisateur et de faible capacité. 

Dans notre Mini projet nous utilisons MySql pour stoquer les données temporarement aprés la conversion de fichier .

3-La maniére de gestion des demandes des clients :Par les threads 

Thread (de l'anglais qui désigne à l'origine un fil textile) peut faire référence à :

un thread ou fil de discussion : un ensemble de messages sur un forum ou un groupe de discussion sur Internet ;
un thread ou fil d'exécution : un ensemble d'instructions similaire à un processus en informatique ;
Threads : un téléfilm britannique de 1984, faux documentaire sur les conséquences d'une éventuelle guerre nucléaire ;
Thread : un album du groupe japonais 10-FEET (2012).

4-Les technologies utilisées:
a- Java Enterprise Edition (JEE) : elle est déja définie au dessus ,avec un serveur local glassfish 5.0
b- JSTL API : est un framework jee pour facilite les codes de notre pages jsp
c- ASPOSE API : est un framework java son objectif est pour la conversion des documents d'un type a un autre 
d- java Mail API :est un framework java pour l'envoie et la reception des mails dans une application java 
e- Serveur de base de données mySql : pour gérer la base de donnée de notre application




