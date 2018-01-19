But
===
Produire le code serveur exposé via des API REST correspondant aux users stories décrites ci-dessous. 

Travail
-------
Lors de la planification du lundi matin, le product owner vous a assigné les users stories suivantes :

**User story 1 :**
> En tant qu'utilisateur ayant les droits "administrateur", je veux pouvoir insérer une question / réponse dans la base de connaissances (FAQ) du produit. Une question / réponse est définie par :
> 1. Le libellé de la question ;
> 0. Le libellé de la réponse ;
> 0. La liste des tags associés.

**User story 2 :**
> En tant qu'utilisateur, je veux pouvoir rechercher la réponse à une question sans avoir à saisir le texte exacte correspondant à une question ou à une réponse de la base de connaissance.

Attendus techniques
-------------------
Vous donnerez accès à `netheos` à votre projet hébergé sur github. Celui-ci devra être :
* compilable sous la forme d'un WAR (java 8+) ;
* déployable dans Tomcat ;
* assemblé via Maven.

Vous fournirez un fichier readme.md décrivant la procédure de tests de votre projet. Vous justifierez également vos choix en termes d'outils et d'implémentation.

Vous êtes libre d'utiliser le framework et le moteur de base de données que vous voulez tant que ceux-ci sont Open Source.

N'hésitez pas à poser vos questions si certains points ne sont pas assez clairs.

Critères d'évaluation
-------------------
Votre code sera jugé selon les critères suivants :
- Elégance ;
- Performances ;
- Sécurité ;
- Robustesse (tests).
