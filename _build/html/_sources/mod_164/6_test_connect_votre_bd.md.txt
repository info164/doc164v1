### Test de la connexion avec votre BD
* Test simple de la connexion à votre BD avec votre requête
  * Ouvrir le fichier "APP_FILMS_164/database/2_test_connection_bd.py"
  * Modifier "MA" requête par votre requête, exemple ;
    ```SQL
        SELECT * FROM t_votretabledevotrebd
    ```
  * Cliquer avec le bouton droit sur l'onglet de votre fichier et choisir "run" (CTRL-MAJ-F10)
  * En cas d'erreurs : ouvrir votre fichier ".env" à la racine de votre projet, vérifier les indications de connexion pour votre
  BD.