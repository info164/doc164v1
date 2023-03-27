# Copie de votre DUMP MySql
    
## ATTENTION !!! AVANT TOUT FAIRE UNE SAUVEGARDE DE VOTRE DUMP MySql   

* Ouvrir à l'aide d'un éditeur votre fichier DUMP MySql.
* Copier tout votre code MySql (CTRL-A  CTRL-C)  
* Ouvrir mon fichier DUMP MySql "APP_FILMS_164/database/MACCAUD_OLIVIER_INFO1X_FILMS_162_2023.SQL"
  * Effacer les lignes 18 jusqu'à la fin du fichier. (CTRL-SHIFT-END puis DELETE)
  * Coller votre code à partir de la ligne 18
  * Contrôle : Il doit y avoir les 3 instructions MySql ci-dessous tout au début du fichier :

```SQL
  -- Destruction de la BD si elle existe. 
  -- Pour être certain d'avoir la dernière version des données      
  DROP DATABASE IF EXISTS VOTRENOM_VOTREPRENOM_VOTRECLASSE_VOTRESUJET_164_2023;
  -- Création d'une nouvelle base de donnée
  CREATE DATABASE IF NOT EXISTS VOTRENOM_VOTREPRENOM_VOTRECLASSE_VOTRESUJET_164_2023;
  -- Utilisation de cette base de donnée
  USE VOTRENOM_VOTREPRENOM_VOTRECLASSE_VOTRESUJET_164_2023;
```

* Renommer ce fichier MySql (clic droit sur l'onglet)
  * Ce fichier "DUMP" doit se nommer "VOTRENOM_VOTREPRENOM_VOTRECLASSE_VOTRESUJET_164_2023.SQL"
* Dans le répertoire "database" vous devez placer vos fichiers (PDF: Cahier des charges, MCD, MLD, dictionnaires des données et SQL : requêtes, etc)

* Ouvrir le fichier ".env"
  * Changer les deux noms de variables comme ci-dessous ;
```SQL
NAME_BD_MYSQL="VOTRENOM_VOTREPRENOM_VOTRECLASSE_VOTRESUJET_164_2023"
NAME_FILE_DUMP_SQL_BD="../database/VOTRENOM_VOTREPRENOM_VOTRECLASSE_VOTRESUJET_164_2023.SQL"
```
