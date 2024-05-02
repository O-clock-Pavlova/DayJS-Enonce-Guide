# Jouons avec les dates !

Aujourd'hui nous avons vu comment nous pouvions créer un module, afin de compartimenter notre code. Nous avons également découvert qu'il existait une infinité de modules déjà existants, récupérables, et installable via npm. Ici nous allons utiliser l'un des modules les plus populaires : dayjs !
Il va vous permettre de jouer avec les dates en faisant des calculs et/ou des formatages.

## Énoncé débrouillard

1. Afficher un tableau HTML contenant la liste des livres de notre collection.
2. Rechercher et installer le module npm [dayjs](https://day.js.org/).
3. Formater la date de parution de cette façon : Thursday, July 29th 1954.
4. Ajouter une colonne spécifiant l'âge du livre.

## Énoncé guidé

<details><summary>À tout moment, n'hésitez à regarder la version guidée du point sur lequel vous bloquez</summary>

1. Dans la constante books nous avons un tableau d'objets javascript contenant différentes clé/valeur par exemple `title: "The Fellowship of the Ring"`. Nous avons vu comment boucler sur un tableau de façon à récupérer les objets un par un et créer la ligne correspondante (`<tr>`). Ensuite, sans faire de boucle nous pouvons créer une nouvelle case par paire de clé/valeur par exemple `'<td>' + book.title + '</td>'` dans la ligne. _(Si le tableau pose problème, dans un premier temps vous pouvez  faire une liste `<ul><li>` au lieu du tableau)_ 
2. Nous avons vu cela en cours aujourd'hui, vérifiez bien la présence et le contenu du fichier `package.json` après installation. Les informations sont aussi disponibles sur la [documentation](https://day.js.org/) <details><summary>Toujours pas ?</summary>
  2a. Dans le dossier du projet, dans un terminal, il faut initialiser notre projet npm avec `npm init`.  
  2b. Puis trouvez ou regardez la [documentation sur l'installation](https://day.js.org/docs/en/installation/node-js) pour installer dayjs. Vous devriez avoir toutes les informations nécessaires.  
  2c. N'oubliez pas le `require` dans votre script pour utiliser dayjs (cf lien ci-dessus).</details>
3. Il faut chercher le mot clé 'format', pour cela passez par google ou directement avec la barre de recherche sur la ... devinez où ? Vous devriez réussir à trouver cette [page](https://day.js.org/docs/en/display/format), utilisez alors les informations présentes pour afficher la date sous le bon format.
4. Ici pas d'aide en plus, je suis sûr que la documentation dayjs contient la solution. C'est le but de ce challenge de chercher les réponses ;)

</details>

## Bonus

La [documentation](https://day.js.org/docs/en/installation/installation) reste votre meilleur alliée !

1. Configurer dayjs avec les locales françaises.
2. Créer deux modules, contenant les données et la construction du tableau. Les utiliser dans l'application.
3. Bonus qui pique : ordonner la liste des livres par date de parution<details><summary>Indice</summary>Regardez du côté de array.sort</details>
