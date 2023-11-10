Environnement de test:

Le test sera effectué sur un serveur de développement local, avec une base de données de test isolée. Des données de test seront préparées, comprenant des comptes d'utilisateur, des articles fictifs et des données de relecture.

Soumission des Articles:

1.1- Test de Création (Create): Créer un nouvel article avec tous les champs requis et des images. Vérifier que l'article apparaît dans la base de données avec le statut "EN_ATTENTE".

1.2- Test de Lecture (Read): Lister tous les articles soumis par un chercheur donné. Vérifier que seuls les articles soumis par ce chercheur sont retournés.

1.3- Test de Mise à Jour (Update): Mettre à jour un article existant. Vérifier que les changements sont persistés en base de données.

1.4- Test de Suppression (Delete): Supprimer un article. Vérifier que l'article n'est plus dans la base de données.

Processus de Relecture par les Pairs:

Test de Relecture: Simuler la soumission d'une évaluation par un pair. Vérifier que l'évaluation est correctement associée à l'article.

Accès Libre:

Test d'Accès Public: Vérifier qu'un article validé est accessible sans authentification. Les articles non validés ne doivent pas être accessibles en libre accès.

Évaluation des Articles:

Test d'Évaluation: Ajouter des évaluations à un article. Vérifier que la moyenne des évaluations est calculée et stockée correctement.



Validation des Articles:

Test de Validation: Valider un article en attente. Vérifier que son statut passe à "VALIDÉ" et qu'il est accessible publiquement.

Sécurité et Confidentialité:

Test de Sécurité: Vérifier que la base de données est sécurisée.