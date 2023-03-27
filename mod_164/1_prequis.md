# Pour pouvoir faire fonctionner "ma" démo
* Ma démo consiste en une interface (HTML, FLASK, Python, etc) et une BD MySql.
  * Il s'agit d'un gestionnaire de films et leurs genres associés.
  * Soit un système CRUD (Create Read Update Delete) presque complet sur les 3 tables de la BD films : Soit "t_film"; "t_genre" et la table intermédiaire "t_genre_film"
* Un serveur MySql doit être installé
  * LARAGON (heidi.sql) ou XAMPP ou UWAMP
  * MAC : MAMP ou https://www.codeur.com/tuto/creation-de-site-internet/version-mysql/
* Python doit être installé.
  * ATTENTION : Cocher la case pour que le "PATH" intègre le programme Python
  * Une fois la "case à cocher" du PATH cochée, il faut choisir d'installer
  * Un peu avant la fin du processus d'intallation, cliquer sur "disabled length limit" et cliquer sur "CLOSE"
  * Le test de Python se fait après avec le programme "PyCharm"
* Installer "GIT"
  * https://gitforwindows.org/
  * Le test de "GIT" se fait dans le programme "PyCharm"
* "PyCharm" (community) doit être intallé, car toutes mes démonstrations sont faites avec cette version de l'IDE.
:::{tip}
Vous pouvez télécharger tous les produits de JetBrains car vous êtes étudiant.
:::
 

  * Lors de l'installation, il faut cocher toutes les options ASSOCIATIONS, ADD PATH, etc
  * Ouvrir "PyCharm" pour la première fois pour le configurer. Choisir le bouton "New Project"
  * Changer le répertoire pour ce nouveau projet, il faut créer un nouveau répertoire "vide" sur votre disque en local.
  * Il est important d'avoir sélectionné le répertoire que vous venez de créer car "PyCharm" va automatiquement créer un
    environnement virtuel (venv) dans ce répertoire
  * Menu : File->Settings->Editor->General->Auto Import (rubrique Python) cocher "Show auto-import tooltip"
  * PyCharm vient d'ouvrir une fenêtre avec le contenu du "main.py" pour configurer les actions "UNDO" et "REDO"
  * Sélectionner tout le texte avec "CTRL-A" puis "CTRL-X" (Couper), puis "CTL-Z" (UNDO) et faites un REDO "CTRL-Y" et "PyCharm" va vous demander de choisir l'action du "CTRL-Y" raccourci pour faire un "REDO". (Dans 98% des éditeurs de texte, le "CTRL-Y" représente l'action "REDO"... pas chez JetBrains)

