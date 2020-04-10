- [X] Initialiser projet node
- [X] Initialiser projet git
- [X] Publication sur github
- [X] Installation eslint & configuration
- [X] Installation express & mysql
- [X] Création d'une table MySQL -> mettre les commandes de créations dans le projet (fichier .sql) :
    - [X] Articles
        - [X] id
        - [X] title
        - [X] content
        - [X] author (INT)
        - [X] created_at (DATETIME)
    - [X] Comments
        - [X] id
        - [X] article_id (INT)
        - [X] author (INT)
        - [X] content
        - [X] created_at (DATETIME)
- [X] Création d'un CRD (pas d'Update, on l'a pas vu) node :
    - [X] Route '/api/articles/create' -> permet de créer un article_id
    - [X] Route '/api/articles/delete' -> permet de supprimer un article par son id
    - [X] Route '/api/articles'        -> permet de récuperer les 5 derniers articles créés dans un tableau
    - [X] Route '/api/comments/create' -> permet de créer un commentaire
    - [X] Route '/api/comments/delete' -> permet de supprimer un commentaire par son id
    - [X] Route '/api/comments'        -> permet de récuperer les 5 derniers commentaires postés
- [X] Création de formulaires HTML pour tout tester
    - [X] Articles
        - [X] create.html
        - [X] delete.html
    - [X] Comments
        - [X] create.html
        - [X] delete.html
