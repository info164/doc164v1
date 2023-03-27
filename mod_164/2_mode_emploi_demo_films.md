## Mode d'emploi de cette démonstration
* Démarrer le serveur MySql (Laragon(heidi.sql), uwamp ou xamp ou mamp, etc))
* Dans "PyCharm", importer MA BD à partir du fichier DUMP
    * Ouvrir le fichier "APP_FILMS_164/database/1_ImportationDumpSql.py"
    * Cliquer avec le bouton droit sur l'onglet de ce fichier et choisir "run" (CTRL-MAJ-F10)
    * En cas d'erreurs : ouvrir le fichier ".env" à la racine du projet, contrôler les indications de connexion pour la
      bd.
* Test simple de la connexion à la BD
    * Ouvrir le fichier "APP_FILMS_164/database/2_test_connection_bd.py"
    * Cliquer avec le bouton droit sur l'onglet de ce fichier et choisir "run" (CTRL-MAJ-F10)
* Démarrer le microframework FLASK
    * Dans le répertoire racine du projet, ouvrir le fichier "run_mon_app.py"
    * Cliquer avec le bouton droit sur l'onglet de ce fichier et choisir "run" (CTRL-MAJ-F10)
