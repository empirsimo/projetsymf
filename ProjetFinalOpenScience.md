Projet Final : Open Science

Contexte : 

Le monde de la publication scientifique est très fermé aujourd’hui. En effet, quelques éditeurs seulement se partagent un monopole controversé sur les droits à la publication scientifique. Pour publier un article de recherche, les chercheurs doivent : 
Envoyer l’article à l’éditeur et payer une contribution.
L’éditeur fait relire par un premier pair qui fait un retour constructif et donne une appréciation
Le chercheur retravaille son article
On refait cette étape 3 fois jusqu’à obtenir un article convenable. Ce processus peut prendre entre 12 et 18 mois car plusieurs mois sont nécessaires à chaque fois pour obtenir le retour du relecteur.
Si l’article obtient des appréciations positives, l’éditeur lit alors l’article et choisit de le publier ou non.
Le monde de l’édition scientifique est très petit et les éditeurs se font payer de multiples fois pour chaque parution : par les scientifiques, par l’État et par les lecteurs.
Les recherches ensuite ne sont pas en accès libre, mais disponibles uniquement via la base de données de l’éditeur dont chaque lecture et chaque citation se paie à l’unité par les prochains chercheurs.

Cette façon de faire est critiquée car accusée de ne pas rendre accessible un savoir qui devrait (selon certain) être ouvert à tous. Elle rend également compliqué la collaboration internationale ou même entre universités et chercheurs.




Solution : 

Pour répondre à ce problème, vous allez concevoir et réaliser une plateforme de publication de recherches en libre accès. Le processus strict de relectures par les pairs devra être respecté.

Vous avez 4,5 jours, le rendu final devra être déposé avant vendredi, 12h00.
Le barème de notation vous sera communiqué à l’avance.

Des rendus intermédiaires sont attendus à chaque fin de journée.
Vous devez les soumettre sous la forme d’un document unique (Rapport) contenant tous vos livrables.


Les missions du jour sont là pour vous guider dans la réalisation du projet.
Demandez un feedback à chaque étape.


Missions Jour 1 : Conception

Initialiser un dépôt Git avec un projet Symfony et une base de données.
Envoyer l’url Github.

Écrire le cahier des charges du projet en 2 pages.

Réaliser un wireframe avec Excalidraw.io

(Optionnel) Réaliser une maquette avec Figma

Écrire le document de spécifications techniques en 2 pages.

Mettre en place le système d’authentification classique par cookie.
L’utilisateur se connectera avec email + mot de passe.

Merci de tout mettre dans un même document.


Missions Jour 2 : Test Driven Development (TDD)

Écrire une version simplifiée d’un cahier de tests : 
Imaginez un parcours utilisateur complet : de la simple visite, à l’inscription, à la connexion, à l’upload d’un document, à la revue d’un article.
Imaginez aussi le parcours de vie d’un article.
Traduire ces parcours en User Stories sous la forme : 
	En tant que visiteur non-connecté
	Quand je me rends sur la page d’accueil
	Alors je dois voir la liste des articles publiés.

Traduire vos User Stories en tests de bout-en-bout, aussi appelés tests applicatifs, en utilisant PHPUnit.

Choisir une User Story et l’implémenter. 
Faire passer le test correspondant. Envoyer le screen.

Continuer à implémenter vos US en faisant passer les tests.

Objectifs de la journée : valider 10% de tests.
Merci de mettre un screen dans votre rapport à la fin de la journée.
