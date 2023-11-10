PhpFinalCC Projet final Cloud Campus PHP Symfony 


Jour 1 : 

Spécifications - Plateforme de publication de recherche en libre accès

 L'objectif principal de ce projet est de concevoir et de mettre en œuvre une plateforme permettant aux chercheurs de publier leurs articles de recherche en libre accès tout en maintenant un processus rigoureux d’examen par les pairs.


 Caractéristiques principales : Soumission d'articles : Les chercheurs doivent pouvoir soumettre leurs articles via la plateforme.

 Processus d'évaluation par les pairs : Le processus d'évaluation par les pairs doit être maintenu.

 Les articles soumis seront examinés par des pairs experts dans le domaine.

 Chaque article fera l’objet de plusieurs cycles de relecture et d’édition.

 Accès libre : 
 
 Tous les articles acceptés seront librement accessibles  par toute personne sur la plateforme, conformément à l'objectif d'accès ouvert.
 Révision des articles : Les pairs devront fournir des critiques constructives sur les articles soumis.


 Archivage des articles : Les articles acceptés doivent être archivés de manière appropriée pour garantir leur pérennité et leur accessibilité à long terme.

 
 Implémentation : CRUD des articles : utilise symfony pour configurer rapidement  le CRUD des articles, des rôles d'utilisateurs et de leurs espaces.

 Confirmation postale :
 
  Tous les articles ajoutés par les chercheurs seront au statut « EN ATTENTE » et ne seront donc pas accessibles aux lecteurs en libre accès mais uniquement aux pairs/éditeurs.

 L'éditeur aura la possibilité d'approuver ou non l'article du chercheur.
 Si l'article est authentifié, il apparaîtra en libre accès.

 Sécurité et confidentialité : Sécurité de la base de données.

