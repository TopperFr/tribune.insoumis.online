# Tribune

La tribune est un blog propulsé par [Nikola](https://getnikola.com/) qui contient des tribunes de la France Insoumise. Il est hebergé sur github-pages.

## Éditer ou rajouter des posts

 * Créer un fichier dans posts/ avec le bon format (s'inspirer des fichiers existants)
 * L'extension détermine le format employé. Je recommande le markdown (.md)

## Publier les changements

 * Tous les commits sur la branche "master" lancent la regénération du site. Si vous faites une pull request, le site va donc être mis à jour au moment de merge.
 * Sinon, vous pouvez forcer le déploiement en installant nikola localement (```pip install nikola``` & ```nikola github_deploy```)
