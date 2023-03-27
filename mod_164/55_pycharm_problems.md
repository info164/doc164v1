## Pycharm et les problèmes liés au hasard des configurations

###### Si vous constatez que vous n'avez pas de répertoire "venv" ("Environnement virtuel")
* Quitter PyCharm.
* Avec l'explorateur de fichiers aller dans le répertoire du projet
:::{important}
:class: myclass1,myclass2
:name: tip_delete_dir
Effacer les 3 sous-répertoires suivants (répertoire caché ".git" , ".idea" et "venv")
:::
  * Ouvrir "PyCharm", puis "File"-->"Open..." un projet et choisir le répertoire racine de votre projet
:::{important}
:class: myclass1,myclass2
:name: tip_venv
Il doit vous proposer de recréer un "virtual environnement".
  * Vous devez voir un nom de répertoire "venv" juste derrière le nom du votre répertoire.
  * Vous confirmez la création de cet environnement virtuel.
:::