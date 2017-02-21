# Tribune

La tribune est un blog propulsé par [Nikola](https://getnikola.com/) qui contient des tribunes de la France Insoumise. Il est hebergé sur github-pages.
[Accéder au blog : tribune.insoumis.online](http://tribune.insoumis.online)
[![Build Status](https://travis-ci.org/Insoumis/tribune.insoumis.online.svg?branch=master)](https://travis-ci.org/Insoumis/tribune.insoumis.online)

## Éditer ou rajouter des posts

 * Créer un fichier dans posts/ avec le bon format (s'inspirer des fichiers existants)
 * L'extension détermine le format employé. Je recommande le rest (.rst) ([Quick guide](http://docutils.sourceforge.net/docs/user/rst/quickref.html))

## Publier les changements

 * Tous les commits sur la branche "master" lancent la regénération du site. Si vous faites une pull request, le site va donc être mis à jour au moment de merge.
 * Sinon, vous pouvez forcer le déploiement en installant nikola localement (```pip install nikola``` & ```nikola github_deploy```)
