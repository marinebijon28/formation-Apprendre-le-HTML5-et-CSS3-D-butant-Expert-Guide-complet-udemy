#### formation udemy : Apprendre le HTML5 et CSS3 Debutant Expert Guide Complet 

### Section 2 : Découverte du langage HTML

## Créer votre première page HTML

# éditeur de code IDE
Il est temps maintenant de rédiger ensemble notre première page de code HTML et d'afficher notre page web. Pour ce faire nous allons utiliser un éditeur de code. Pour ceux qui débutent complètement, un éditeur de code je vais faire très court. Je pense qu'il vaut mieux vous montrer comment tout ça fonctionne, l'avantage parce que c'est optimisé. 
On peut rédiger du code avec n'importe quel logiciel par exemple un simple blocnote. Le problème c'est qu'il faudra vraiment être très strict sur la syntaxe, etc. Il n'a pas d'outil dans le blocnote qui vous aide à rédiger du code.
Hors un éditeur de code c'est cela que ça va faire. Ça va permettre de saisir du code comme vous faisiez comme un traitement de texte, mais vous allez voir quelques petits avantages. Par exemple l'auto complétion ça va vous permet de terminer les mots que vous commencez. Les balises vont vous être proposées. Vous allez avoir la génération de la balise fermante. Vous aurez de la colorisation syntaxique pour savoir là où il y a des erreurs. Il y a plein de petits avantages.

# installation IDE
Je vais installer avec vous un IDE que j'affectionne particulièrement. À vous de choisir le vôtre. Vous pouvez utiliser le même que le mien. Pour ceux qui débutent ça sera peut-être le plus simple. On va se rendre sur la page de Visual Studio Code.
L'avantage de cet IDE, c'est que vous avez plusieurs versions possibles. Vous pouvez le voir que l'ait pour Mac, Linux et Windows. Sélectionner le bon OS et cliquez sur download. Je vais l'exécuter, un double click et j'aurai simplement, qu'accepter les termes de la licence et le chemin par défaut. Je fais suivant deux fois. Je vais créer une icône sur le bureau, je vais ajouter le patch et ouvrir avec un click droit Visual Studio Code sur un fichier. On va l'installer, on peut voir que c'est terminé et on va pouvoir exécuter visual Studio Code. Je vais supprimer le fichier setup et j'ai bien visual Studio code que je vais pouvoir exécuter.

# description de l'interface Visual Studio Code
On ouvre, on voit une interface qui peut faire peur au premier abord qui a l'air complexe. Je vais agrandir la fenêtre sur tout l'écran. Sur la droite on peut voir pas mal de possibilité de outils langages, etc. On va pouvoir fermer la fenêtre Bienvenue.
C'est un simple éditeur de texte je vais devoir faire un nouveau fichier. On peut observer un fichier qui s'appelle sansnom-1. C'est en fait son nom. 
Nous voulons enregistrer c'est du HTML. Vous avez des choses assez intéressantes. En bas à droite la ligne où vous vous trouvez, on peut voir la colonne et la ligne. Là on est sur la ligne 1 colonne 1. Ensuite, vous avez les espaces qu'on ne va pas vraiment utiliser. L'UTF-8 qui est l'encodage par défaut UTF-8, on ne va pas le modifier. Si vous cliquez vous pouvez le modifier, mais ce n'est pas nécessaire, échappe pour quitter. Ensuite, ce qui va être très intéressant c'est le langage que vous utiliserez dans votre page. 
C'est éditeur de code qui va vous permettre de coder entre tous c'est langage. En toute logique, on devrait lui mettre du HTML pour lui indiquer que c'est du HTML, mais on ne sera pas obligé parce que l'on va faire. On va tout simplement enregistrer notre fichier. Pour moi, je vais faire un dossier sur le bureau appeler cours HTML CSS.

# Fausse page
Maintenant je vais pouvoir stocker mes fichiers. Je vais sur le menu tout en haut dans fichier cliquer sur enregistrer sous. Je vais aller dans le bureau dans le dossier cours HTML et CSS. Mon premier fichier va s'appeler premiere.page.html. N'oubliez pas l'extension si vous ne l'avez pas renseigné. Maintenant on peut voir le chemin du fichier et on a un onglet avec le fichier. Je vais pouvoir plusieurs fichiers ce qui va être intéressant. 
Ensuite, je vais pouvoir écrire ma première page html. Vous avez pu voir, je vous ai parlé des balises. On ne va pas s'en servir pour faire une page web, il ne faut pas être balaise. Vous allez voir là que je vais voir ce que j'ai écrit sur ma page. Je vais marquer bienvenue sur ma première page page HTML. Vous pouvez voir quand j'écris certains mots html ici, j'ai des choses qui s'affichent et cela est très intéressant. Pour enregistrer les modifications : sauvegarder fichier.
Maintenant que notre page est créée, on va aller l'exécuter pour voir ce que ça donne dans un navigateur. Je retourne sur le bureau, je vais ouvrir mon dossier et on peut y voir ma première page. Je vais faire un double click. On peut observer qu'on a bien : Bienvenue sur ma première page html.
Pourquoi je vous disais que l'IDE était facultatif parce que je pourrais très bien décidé d'ouvrir le blocnote. Tout simplement glisser ce fichier dedans tout simplement dedans et on voit bien j'ai le contenu. Je pourrais même écrire : ceci est une ligne écrite depuis blocnote. On enregistre. Si maintenant je rexécute ma page on peut voir sur ma page HTML : bienvenue sur ma première page html. Ceci est une ligne écrite depuis blocnote.


# Les avantages d'un IDE
On peut voir que l'IDE Visual Studio Code est totalement facultatif. Il va avoir par contre de gros avantages :

# Premièrement, imaginons que maintenant créer un paragraphe.
<p></p>
Je vais utiliser ici mon chevron ouvrant, mon p et mon chevron fermant. Vous pouvez voir automatiquement que visual studio code ma généré ma balise fermante. C'est ce qu'on appelle l'auto complétion : ça va fermer des balises, ça va aussi vous proposer la syntaxe code des balises HTML. Ça ne s'arrête pas là, on peut bien voir que mon curseur est bien placé au milieu. Ce qui est intéressant, c'est que je vais pouvoir écrire ceci est un paragraphe. Je retourne à la ligne c'est un gagne temps, au cas j'oublie de fermer ma balise ça le fait pour moi.

# emmet
Ensuite, y a d'autres possibilités, cela va fonctionner avec pas mal de balise, mais vous avez la possibilité par exemple d'utiliser emmet. C'est quoi? Au lieu  de taper ma balise <img> je vais taper directement img, je vais avoir une abréviation emmet et je vais faire entrer. Regarder ce que fait l'éditeur, il me propose deux attributs qui vont être les plus courants. Quand on utilise la balise img c'est src je vais stocker mon chemin et dans alt la description de mon image. La balise est faite, on gagne du temps sans avoir beaucoup de choses à renseigner. Ça nous propose les balise intéressante, donc d'un point de vue syntaxique c'est intéressant et on a plus qu'à renseigner les attributs.

Autre raccourci ctrl + pour zoommer et ctrl - pour dézoomer.
À la place de ctrl pour mac c'est commande.

# Structure d'un fichier HTML
Je vous ai parlé d'une structure d'un fichier HTML. On commence par le doctype html, puis les deux balises HTML. Ensuite, je vais avoir une balise head et dehors de la balise head je vais avoir le body. C'est assez pénible à taper grâce a visual studio code, vous pouvez taper html avec emmet et vous choisissez la deuxième proposition. On peut voir que cela génère le squelette html de votre page web. Vous pouvez voir qu'il y a des choses en plus qu'on n'a pas vu. Il y a un attribut langue à la balise html qui permet de définir la langue. Le codage utf-8, et ici on reviendra plus tard sur les meta et vous avez une balise title.

vous pouvez voir que c'est très intéressant, vous avez d'autres possibilités. Avec la loupe à droite vous ouvrez faire des recherches dans les documents ou de remplacer des choses ça peu toujours être intéressant. Là vous avez la source contrôle là, on va trop utiliser dans le cadre HTML. Vous avez une partie déboggage qui va être intéressante pour debugger vos erreurs. Vous avez surtout une partie extension. L'extension c'est un magasin qui va vous  permettre d'ajouter plein d'extension que vous n' auriez pas par défaut dedans. Il en existe plein sur internet. 

# installation d'extension
Là par exemple je vais installer une extension très pratique open dans un browser et j'ai bien l'extension. Si je clique dessus j'ai bien un résumé sur la droite. C'est une nouvelle page qui c'est ouvert dans mon navigateur. On m'explique comment tout ça fonctionne. On utilise alt + B pour ouvrir le fichier  dans le navigateur par défaut ou shift + alt + B pour choisir un autre navigateur installé sur votre machine. Pour installer il suffit d'appuyer sur installer. Une fois installé on peut le désactiver où le désinstaller. C'est dans mes extensions que j'ai installées sur ma machine. On va pouvoir tester tout de suite si ça fonctionne. Je vais dans le fichier html je fais un commande + s et j'utilise la combinaison de touches qu'ils m'ont de faire alt + b. Cela ouvre bien le fichier dans le browser et je peux le refermer.

Vous avez créé votre première page HTML, j'espère que vous avez compris que l'éditeur de code va vous faire gagner du temps. Je vous expliquerai d'autres manipulations assez intéressantes pour coder plus facilement. Avoir moins d'erreurs de syntaxe et de coder plus vite. Tout au long de ce cours parce que j'utilise Visual Studio Code je vous montrerais au fur à mesure. Si vous avez un autre éditeur de code faudra vous documenter vous-même.