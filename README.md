# www.coccinailes.fr
Site web du club de parapente des Coccin'ailes du pays d'Allevard

## Ajouter un bulletin météo
les bulletins météo se trouvent dans le répertoire `bulletins-meteo/_posts/année`. Chaque fichier correspond à un bulletin.

Il faut respecter la règle de nommage suivante pour les noms de fichier des bulletins météo: `année-mois-jour-titre.md`.
Le titre n'a aucune importance mais est obligatoire. Il est conseillé de mettre `meteo` ou `bulletin`.

Ensuite dans le contenu du fichier, le plus simple est de prendre exemple sur un bulletin existant.

La syntaxe du contenu du fichier est du markdown. Plus d'infos [ici](https://guides.github.com/features/mastering-markdown/).
Avec l'éditeur en ligne de fichier il y a l'onget `preview` qui permet de se faire une idée du rendu avant publication.

Une fois le contenu créé, il faut prendre en compte la modification en cliquant sur le bouton vert en bas de la page `Commit new file`.

Il faut compter quelques minutes pour que le site soit mis à jour automatiquement.

## Newsletters
Elles se trouvent dans `_posts/newsletters` et leur fonctionnement est identique aux bulletins météo.

## Autres modifications sur le contenu des pages
Pour les autres pages, pour corriger des informations, il faut modifier directement les fichiers `.md` à la racine du site
ou dans `_décollages` et `_atterrissages` pour les sites de vol.

## Arrangements graphiques
Pour modifier l'affichage du site, tout se trouve dans `_layouts`.

## autres informations
Le site utilise jekyll, voir https://docs.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll pour plus d'infos.
