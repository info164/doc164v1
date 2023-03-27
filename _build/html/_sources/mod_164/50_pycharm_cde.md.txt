# Pour "rafraîchir" les versions des packages (Terminal de "PyCharm") 



Pour tenir les versions des packages à jour.

    pip install pipupgrade
    pipupgrade --verbose --latest --yes

* En cas d'erreurs :

    Il faut alors mettre à jour "manuellement"
(PyCharm: File->Settings->Project->Python interpreter. Double clic sur un package à mettre à jour)


# Avant d'envoyer votre projet.
La commande ci-dessous est indispensable.
Cela permet de mettre à jour la liste de tous les packages à installer pour que votre projet fonctionne.
    
    pip freeze > requirements.txt
