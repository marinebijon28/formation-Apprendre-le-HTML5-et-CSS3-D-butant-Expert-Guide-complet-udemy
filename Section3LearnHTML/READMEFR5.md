#### formation udemy : Apprendre le HTML5 et CSS3 Debutant Expert Guide Complet 

### Section 3 : Apprendre le HTML

## L'éléments HTML head

# structure html
Alors que maintenant vous avez vu comment vous pouvez rédiger du code HTML. On va s'intéresser que le premier élément qu'on va rencontrer dans une structure HTML qui est la balise head.

Head c'est tout simplement l'en tête. La première chose qu'on va faire. J'ai créé un nouveau fichier qui s'appelle index.html. Vous pouvez le voir de l'explorer dans un dossier cours  html et css. Vous allez voir que je vais travailler avec ce dossier tout au long de ce cours et on va pouvoir gérer les fichiers. Ce qui m'intéresse maintenant ce qu'on peut placer dans la balise head. C'est déjà de créer une structure html dans ce fichier html. 

# doctype
La première chose le DOCTYPE. 

# html
Ensuite, on ouvre une balise html, évidemment on la ferme. On va y placer deux autres balises. 

# head
La première ça va être le head qu'on place toujours en premier c'est l'en-tête du fichier.

# body
Ensuite, la balise que l'on appelle body. C'est le corps, on a vu comment ça fonctionné. On va mettre ici un espace ce qui va permettre d'avoir ici. Mes balises qui vont bien être indenté. 

# Données dans la balise head
Dans cette balise head. Entre ces deux balises là. On va y placer des éléments. En fait, qui ne vont pas forcément avoir d'impact visuel sur votre site, mais par contre ça va permettre de communiquer des informations qui vont être utile. Notamment pour les moteurs de recherche ou encore pour indiquer au navigateur quel il encodage faut utiliser pour la page web. On va avoir que pour remplir ce head du nouveau du site.

# documentation officielle
Je vous encourage a consulté la documentation officielle ça doit être un réflexe à chaque fois que vous voulez faire que vous ne maîtrisez pas forcément. On va aller à la documentation, on va aller au niveau de technologie et on va choisir html a gauche on a toujours les mêmes choses et on va descendre un peu. Au niveau de référence, vous avez les références ici. Vous allez pourvoir observer des références des éléments html c'est ça qui va nous intéresser. On va cliquer dessus, on peut observer des catégories. Ce qui va nous intéresser c'est les métadonnées. Tout ça que vous allez utiliser à l'intérieur de votre balise head. D'ailleurs on peut voir que la balise head est là. Il y a des choses qu'on va impérativement utiliser et d'autre un peu moins. Je vais passer très rapidement en revue les éléments. 
Base va définir l'url de base à utiliser pour le site quand des url vont être composé, on va utiliser l'élément base l'url de base. 
Head c'est ce qu'on est en train de voir que ça fournit les informations générales des métadonnées sur le document. 
Ensuite, on va avoir d'autres balises links. La balise link va être très intéressante qu'elle va permettre de mettre en relation notre fichier html avec un autre. C'est essentiellement utiliser par exemple pour relier une feuille de style css a notre page html donc on va l'utilisé dans la seconde partie avec le css, mais ça peut être utiliser pour d'autre chose. On va y revenir au moment venu. 
La balise méta, la balise la plus importante ici du contenu du head parce que l'élément html méta va permettre de données pas mal d'information au niveau des metadonnées c'est très important pour un site notamment pour le référencement est autre. 
La balise style quand vous allez vouloir faire du css à l'intérieur de notre fichier sans utiliser le link on y reviendra aussi. 
La balise title permet tout simplement de définir un titre au document html. Justement on va s'intéresser title, on va revenir sur Visual Studio Code. On va modifier créer notre balise title. Je vous montre tout de suite comment cela fonctionne et ici je vais écrire :

# title
<title>mon super site web</title>
J'enregistre mon fichier pour le moment si je fais un alt + b. J'avais mis l'extension pour pouvoir exécuter le fichier. On peut voir ici qu'au niveau de son nom c'est mon super site web parce que j'ai changé la balise title. Imaginons que je ne mets pas cette balise je vais la supprimer temporairement. Je fais un ctrl + s et je ré-ouvre ici ma page et je l'actualise ca porte le nom index.html pourquoi parce que je n'ai pas défini de type à mon site. Je vais ici définir le title. Je vais remettre la bonne indentation et donc j'ai définit le titre ce qui fait au niveau de mon site quand j'actualise on va pouvoir voir que j'ai bien mon super site web et là. Cela a un intérêt visuel, mais pas que tout ce que vous allez mettre ici. Par exemple le title c'est très important pour les moteurs de recherche. Il faut mettre un nom pertinent qui correspond a votre site sans que ce soit trop long, etc. Il faut mettre un nom qui correspond a votre site c'est vraiment très important et évidemment pour les moteurs de recherche. Voilà pour la balise title vous avez compris son fonctionnement. 

# meta
Ensuite, si on retourne au niveau de la documentation, on a la partie méta. Cette partie va nous intéresser grandement. On peut voir qu'à l'intérieur cet élément comme le charset que l'on a déjà rencontré. Ça permet de définir l'encodage de la page web. Ce que je vais faire créer une balise méta. 

<meta charset="utf-8">
C'est une balise vide et évidemment je vais mettre l'attribut charset qui est égal à l'utf-8 qui est d'ailleurs le système par défaut ici de Visual Studio. Ça va permettre en faire si vous avez des problèmes d'accent et autre d'affichage. Si vous utilisez cette balise va résoudre le problème, ça va forcer le navigateur a utilisé l'encodage utf-8. Ce n'est pas bien compliqué, on va retourner ici. 
On va descendre. On va voir une multitude d'attribut. 
Content qui est assez intéressant qui va nous permettre par exemple de l'associer a un autre attribut ça va marcher par deux. Je vais vous montrer tout de suite. 
http-equiv on l'utilise plus aujourd'hui. On peut voir que ce n'est plus recommandé d'utiliser. Ça permet de définir le content-language. Là on va plus l'utiliser. On va le faire ensemble par la suite, mais pas avec les balises méta. 
Si je descends, j'ai le content-type, le name. Le name est assez intéressant et on va s'y intéresser tout de suite. 

# name
C'est quoi le name ? Ça permet de définir des métadonnées une description de votre document. Donc regardé si je descends un peu ici on va voir que le name peut prendre comme valeur : auteur, description, générateur, keywords ou générateur. Celui le plus utilisé cette description. Ça va contenir un contenir un résumé concis et pertinent de la page web. Donc, comment on va coder ça. On va tout simplement ouvrir une autre balise meta. 

<meta name="description" content="Description du site web" />
On va utiliser name et on va dire que c'est égal à description. Maintenant on va de voir utiliser l'attribut content qui marche par paire pour simplement affecter dans description ce que je veux y affecter tout simplement. Je vais dire que c'est égal a description du site web. Cela est intéressant non seulement au niveau du référencement de vous aider, mais aussi vous regarder une page comme Google. J'ai fait une requête de recherche de cinéma. Vous pouvez voir ici la description du site. Elle va apparaître dans les moteurs de recherche. On peut voir qu'elle n'est pas très longue et c'est assez intéressant. Si je clique sur ce site. On va faire un clique droit pour afficher le code source de la page. On va pouvoir voir dans le head que j'ai des balise meta. J'ai le charset utf-8. Je vais chercher au niveau du name description. On peut voir qu'il y en a d'autre comme keywords, auteur, etc. On a bien la balise description. On peut voir : Retrouvez tous les films au cinéma, les séances dans toute la France, le guide des meilleurs films à voir, les films à voir à la TV, ....
On peut voir que c'est assez intéressant, je vous encourage a regardé le code html des pages web parce que ça vous permettra de comprendre. On peut voir ici il n'y a pas mal de méta. On en plus bas comme Twitter ici, ce sont des métas pour les réseaux sociaux. On ne va pas l'utiliser pour le moment au moment venu vous pourrai vous y intéresser. Comme on peut le voir c'est assez intéressant et on a pas mal de valeur comme on peut voir ici auteur qui définit l'auteur du document. Cela je pourrais le faire, mais cela n'est pas trop utilisé, on a la description qu'on vient d'utiliser. On pourrait utiliser keywords aussi. Keywords c'est plus très utilisé parce que c'est plus trop pertinent. 

<meta name="keywords" content="html, programmation, CSS" />
On peut encore l'utiliser le name est égal keywords. On va dire que content est égal et là on va mettre des mots clés. Imaginons qu'on fait un site sur le HTML. Par exemple html, programmation, CSS, etc. On peut en mettre pas mal. Ce sont des mots-clés des tags qui permettent d'identifier dessus. Ce qu'il faut savoir aussi vous pouvez voir la documentation officielle pour le reste, mais on a aussi une méta pour la langue.

<html lang="fr">
Ça on l'utilise plus parce que ça deviens obsolète, C'est au niveau de la balise html. On va déclarer l'attribut langue qui est lang est chez nous c'est fr donc la France. Donc, voilà comment on va faire que vous dire encore là-dessus. Je vous ai parlé des autres balises link et tout ça. On les verra au moment venu. 

On a fait le tour des choses. On peut voir que ce n'est pas bien compliqué dans ce head. Pour le moment on va s'atteler à deux trois méta. L'utf et la description du site. Ça c'est très important et celle-ci keywords on n'est pas obligé de la mettre. On la met de moins en moins parque ici le titre et le meta name description. On va pouvoir faire une description qui va permettre d'indexer le site au niveau des moteurs de recherches et d'avoir une description. Donc, voilà ce qui a dire pour l'élément head de notre fichier html. Ce n'est pas bien compliqué je vous encourage à aller voir la documentation lorsque vous aurez besoin de la garnir un peu plus, mais dans le cas de ce cours, on ne va pas aller plus loin. Les autres métas sont bien spécifiques. Ici on va avoir un cas général. On n'a pas forcément besoin de méta, mais on en ajoutera tout le long de ce cours. Bon maintenant je vais vous donner rendez-vous dans la prochaine session parce que là. On a vu ce que c'était la balise head. On a fait le tour ce n'est pas très bien compliqué. Maintenant on va s'intéresser à ce qu'on peut mettre dans le body c'est-à-dire le corps du html.