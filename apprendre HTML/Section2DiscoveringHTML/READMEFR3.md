## formation udemy : Apprendre le HTML5 et CSS3 Debutant Expert Guide Complet 

## Section 2 : Découverte du langage HTML

# Syntaxe HTML
Dans cette section on va s'ntéresser au base du HTML. Comment on peut construire HTML et notamment voir comment fonctionne HTML au niveau de la syntaxe. La syntaxe est pas tres compliqué parce que c'est un langage de balisage.
Pour créer une phrase dans un fichier HTML, on va tout simplement utliser des balises. 

# Example de balise
<p>Ceci est une phrase</p>
J'ai donc une phrase qui est <p>Ceci est une phrase.</p>. On peut voir que j'ai de deux balises <p> qui sont apparue. C'est une balise qui permet d'écrire un paragraphe en HTML.
Cette balise on peut voir qu'il y en a deux :
- La première c'est la balise ouvrante
- Ensuite vous avez la balise fermante

Elle est constituée pour la balise ouvrante d'un chevron ouvrant de la lettre, ou le nom de la balise, en l'occurence p et d'un chevron fermant.
Ensuite on y met nos phrases, nos phrases, nos textes, nos paragraphes. Quand nos paragraphes sont terminées. On va simplement utilisés un chevron, ouvrant un slash, le nom de la balise et on referme avec un chevron fermant.

# Élément HTML
Ça c'est une balise en fait aui marcher par paire : c'est-à-dire qu'il y a une balise ouvrante et une balise fermante automatiquement.
La différence entre la balise ouvrante et fermante, cest le slash. Cela permet aux navigateurs ce qu'il y a entre eux les balise ouvrante et fermante est tout simplement un paragraphe. Alors si on prends le contenu complet. Les balises et la phrase : on appelle ça un Élément HTML. C'est important de bien le comprendre

# Attributs
Ensuite, on avoir des éléments qui sont des attributs. Des attributs c'est très simple.

<p         </p>
Ici nos balises <p>. On peut voir que la balise ouvrante est un peu différente que d'habitude parce aue je n'ai pas mis de chevron fermant. J'ai la balise fermante qui est tout fait classique.

<p class="important"></p>
<p class='important'></p>
Pourquoi je n'ai pas fermé la balise le chevron de balise ouvrante. Si on doit ajouter un attribut c'est-là ou on doit le mettre. Si j'utilise l'attribut class. On verra plus tard ce que c'est. Je lui affecte avec le signe égale avec des simple quote ou des double côte ça marcherai aussi.

Important ça veut dire que se paragraphe dépends de la classe important. Vous ne savez pas encore ce que c'est. La classe va permettre tout simplement de revenir sur ce paragraphe est de modifier grâce au CSS sont apparence. En tout cas, il existe en beaucoup, et on peu voir que c'est assez simple à utiliser. On va les utiliser en déclarant les attributs dans la balise ouvrante.

<p class='important'>Ceci est mon paragraphe</p>
Ensuite qu'en j'ai fait ça, je mets mon texte. Là cela va fonctionner, mais au niveau de la classe vous ne le verrez pas à l'affichage. Le HTML sait qu'il y a un attribut classe qui s'appelle important.

<p class="important"></p>
Cette partie est la balise ouvrante. J'ouvre mon p et au lieu de le refermer directement avec le chevron fermant je vais y mettre mes attributs. C'est comme ça que cela va fonctionner et ici on peut observer une balise fermante.

Le HTML va être simplement le fait de connaître les balises et les attributs, etc. A force vous allez voir que vous allez les retenir facilement. En plus, je vais vous expliquer : les balises, les attributs. 

# Mozilla Developer Network
Les plus importantes mais il est possible que vous tombiez sur des balises que vous ne connaissez pas. Je vais vous donner l'adresse d'un site qui s'appelle Mozilla Developer Network : developer.mozilla.org/fr/. C'est très intéressant, ce site en fait va vous permettre d'utiliser la documentation HTML qui est en plus traduite. 

Une fois que vous êtes sur le site, vous allez au niveau de technologies et vous choisissez HTML.
Alors là on peut voir sur le menu gauche qui va être intéressante, vous avez la documentation et vous avez toute les références. C'est ca qui va nous intéresser, si je cherche ici, je demande d'afficher les éléments HTML. On peut voir une liste qui est apparue assez conséquente, qui possède tous les éléments HTML. Si je descend comme c'est classée par ordre alphabétique. 

On va pouvoir observer que j'ai mon <p>. Si je clique dessus ça va m'indiquer : l'élément HTML <p> représente un paragraphe de texte. Les paragraphes sont généralement représentés comme des blocs et séparés par un espace vertical. On a même un exemple en-dessous mais qui contient du texte, on ne va pas s'en occuper pour le moment. Si on descend on a encore des exemples, on nous explique des choses.

On a surtout les attributs de cette balise . En fait cet élément comme les autres élément HTML inclus les attributs universels. Quand il n'y a pas vraiment d'attribut spécifique à cette balise, vous allez pouvoir utiliser les attributs universels. Or si vous utilisez une balise qui a des attributs bien spécifique. Elles vont apparaitre là et elles vont être expliqué.

Si on revient au niveau de technologies HTML. On va pouvoir aussi observer qu'en-dessous d'élément HTML. On a les attributs universels, on peut en voir pas mal, ce qui va être assez intéressant.

On peut découvrir class, si je clique sur class : L'attribut universel class indique une liste de classes associées à l'élément courant. Grâce au CSS ensuite on va pouvoir accéder aux paragraphes qui ont comme attribut la classe : class="note editorial". Dans notre cas c'était important, si j'avais attribué cette classe à plusieurs paragraphes. Je pourrais grâce aux CSS sur l'apparence de tous les paragraphes simplement dans le CSS, c'est assez intéressant.

Autre chose que je voulais signaler sur le site : c'est que vous avez des éléments HTML avec une petite poubelle rouge à côté, ça veut dire que c'est obsolète et qu'il faut éviter de l'utliser. Cette fonctionnalité est obsolète : cette fonctionnalité a été supprimée des standards du Web. Bien que quelques navigateurs puissent encore la supporter, elle est en cours d'éradication. Ne l'utilisez ni dans d'anciens projets, ni dans de nouveaux. Les pages et applications Web l'utilisant peuvent cesser de fonctionner à tout moment.

De la même manière que vous avez un pouce bleu vert le bas qui vous dit que ce n'est pas standardiser.Il vous dit : cet élément n'est pas standard et ne doit pas être utilisé ! Pour intégrer du son à une page web, on utilisera l'élément <audio>. En gros elle ne fonctionnera pas forcément si vous êtes sur internet pour une utilisation pour tous le monde. 

Vous avez tous ce qu'il faut ici. Si vous revenez au niveau de HTML et des attributs. Vous avez quelques petits icones ici une api expérimentale vous mieux pas l'utiliser en production. Bien que la prise en charge de cet attribut ne soit pas homogène pour les navigateurs, celui-ci est pris en compte par les outils de traduction automatique (Google Translate par exemple) et les outils de traduction utilisés par les traducteurs. Aussi, cet attribut doit être utilisé par les auteurs web afin d'indiquer correctement le contenu qui ne devrait pas être traduit. Vou aurez bien compris qu'il faut l'utiliser.

Alors ce site Mozilla Développer Network va vous être dans grand secours. Si ce n'est pas traduit vous pouvez le changer cliquer changer la langue, vous allez être en bas de la page et vous allez pouvoir la sélectionner.

# Les éléments imbriqués
Pour les éléments ca va pas être bien compliqué.
<p>apprendre le<strong> html </strong>c'est facile</p>
Vous pouvez voir ici à l'écran j'ai toujours mon aparagraphe avec un texte différent : apprendre le html c'est facile. 

<p>apprendre le html c'est facile</p>
On voit bien ici que j'ai mis des balises pour le paragraphe ouvrante et fermante. 

<p>apprendre le<strong> html </strong>c'est facile</p>
Vous pouvez apercevoir à l'intérieur que j'ai imbriqué deux balises strongs. Elles entourent le texte html avec la balise ouvrante a gauche avec : le chevron ouvrante, strong et le chevron fermant. La balise fermante avec : chevron ouvrant, slash,strong, chevron fermant. 

Pour savoir ce qui est la balise strong aller voir la documentation ca va me permettre de mettre le texte en gras. Le HTML va être la pour le contenu. Le rôle du CSS est justement la mise en forme donc par exemple mettre en gras. Là il faut pas voir les balises strong comme pour dire je vais placer mon texte en gras. Les balises strong exprime de la sémantique. Tout simplement le mot html a une consonnance forte de ma phrase donc grâce ces balises en CSS. Je vais pouvoir appliquer quel style que je veux : le laisser en gras, en italique, changer la couleur, etc. C'est le point de vue de la partie sémantique. Ces valises strong, il faut pas les utiliser juste pour mettre en gras, même si le font. C'est surtout pour dire que ce texte est important.

<p>apprendre le<strong> html </strong>c'est facile</p>
Vous pouvez voir que j'ai bien les balises strong imbriquésdans mon paragraphe.

<p>apprendre le<strong> html </p>c'est facile</strong>
Alors, attention si vous faites ce genre de ligne de code vous pouvez. On peut voir  que j'ai bien la balise ouvrante cet élément <p> et <strong> qui est inversé donc elle se chevauche. On peut voir que ça ne fonctionne pas.

<p>apprendre le<strong> html </strong>c'est facile</p>
En fait les balises fonctionnent par paires les deux <p><strong></strong></p>.

<p>apprendre le<strong> html </p>c'est facile</strong>
Ma balise <p> chevauche la balise sans être fermé <strong> chevauche ma balise fermante </p> chevauche la balise fermante </strong>. Vous n'aurez pas une erreur en HTML mais vous aurez un comportement inattendue, un affichage bizarre. Parce que la première balise est la balise <p> est le navigateur va comprendre que c'est un paragraphe. Au milieu j'ai une balise strong qui n'est pas une vide ou orpheline (y a deux types de balises les paires et les vides qu'on appelle aussi orpheline) bormalement il faut une balise fermante.Vous allez avoir un problème d'affichage mais par contre vous pouvez voir que le paragraphe est bien existant. Attention ici a bien ouvrir une balise et bien la fermer. Si vous les imbriqué faites bien attention qu'elles soient bien à l'intérieur.

# Éléments vides
Un élément vide c'est tout simplement une balise qu'on va dire qu'elle est orpheline. on a pu voir que les ballises précédentes fonctionnaient par paire. Les balises orphelines ou vides fonctionnnent toute seule.

<img src="pictures/equitation.png" alt="Image de cheval" />
Vous pouvez voir que j'ai ma balise <img>. Elle est ouverte et on voit biem le chevron qui la ferme. Pourquoi il y a des choses au milieu, les balises vides s'utilise un peu différemment. 

src="pictures/equitation.png"
Par contre à l'intérieur on va y glisser des attributs, comme notre classe. Là c'est des attributs différents qui sont bien souvent l'attribut src ici va être réservé à la balise <img>. La balise src c'est la source donc le chemin de mon image. Le chemin sera pictures et le fichier s'appelle equitation.png.

alt="Image de cheval"
Ensuite, vous pouvez voir une deuxième balises alt, c'est ce qui va être dit pour le dêficient visuel. Si quelqu'un est aveugle, les aveugles navigue sur les navigateur rassurez-vous. Ils ont souvent des logiciels de lecture donc ça lit la page. Cest que si vous dites à l'attribut alt, il ne saura pas lire l'image c'est normal. L'image va être remplacer par le texte image de cheval. c'est un attribut très important surtout fans la balise <img>.

On va voir durant ce cours voir l'ensemble des balises et des attributs intéressants. Encore une fois aidez-vous de la documentation. Le but de ce cours est de vous rendre autonome.

# structure HTML
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" />
        <title>Mon super site</title>
    </head>
    <body>
        <p>Bienvenue sur mon site web</p>
    </body>
</html>
On va s'intéresser à la structure d'un fichier HTML. C'est trés important. Il y a plusieurs choses à voir :

<!DOCTYPE html>
- La première chose, c'est qu'on va rencontrer en haut du fichier une balise un spéciale. Chevron ouvrant, point d'exclamation, DOCTYPE, plus loin html et chevron fermant. Le doctype c'est trés important, celui-ci correspond au HTML5 et vous allez devoir le renseigner. Pourquoi ce Doctype on doit le déclarer parce qu'auparavant vous aviez des version. Maintenant vous n'avez plus que du HTML5 mais auparavant on utilisait plusieurs versions de HTML en même temps. Le doctype était différent pour dire à votre navigateur ce aui suit c'est du HTML3, 4, 5. Le problème de ce doctype était qssez long a renseigner. Avec HTML5 vous devez juste retenir que vous inscrivez ce doctype a chaque fois il n'y a pas le comprendre. Ça correspond au doctype pour dire navigateur c'est du HTML5.

- Ensuite vous pouvez observer deux balises une ouvrante et un fermante <html></html>. C'est balise c'est la qu'on va mettre tout le contenu de notre site web.

- Ensuite vous pouvez voir deux balises <head></head> qui se traduit en français tête ca va être le header> Tout ce qui va correspondre aux rensignement du site. Par exemple : le titre de la page, on va y mettre des balises meta. On pourrait y mettre plein de chose par exemple : des tags, des metas pour que le site soit mieux indexer sur les moteurs de recherche. Ce ne sont pas des choses qui vont se voir mais qui vont être important.

- Ensuite on a une deuxiéme balises juste en-dessous qui est à la même hauteur qu'on appelle body qu'on traduit par le corps. ça va être le corps de votre message. Ici on peut voir qu'il y a simplement un paragraphe.

Ce qui faut retenir c'est que la structure d'une page HTML :
- Commence par son doctype,
- ensuite on y insère deux balises html ouvrantes et fermantes. À l'intérieur de cette balise on va y mettre d'autres balises :
    - le head donc le header
    - le body et en dessous le body

Ça c'est une structure trés simple mais elle est obligatoire à connaître rassurez-vous il y a des petites facilitées au niveau des editeurs de codes qui vont nous permettre de pas forcément de pas avoir à le retenir.

<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" />
        <title>Mon super site</title>
    </head>
    <body>
        <p>Bienvenue sur mon site web</p>
    </body>
</html>
Ensuite, je voulais vous perler de l'importance de l'indentation. j'ai écris ma balise <html>, l'éditeur dessine un trait afin de montrer que les balises sont au même niveau. Même si elle se trouve plus bas et que des balises soient imbriqués
Entre chaque balise paire s'y on ouvre une autre balise <head> à l'intérieur, elle sera décaler au niveau de l'indentation soit une tabulation. 

Elle va vous permettre dans certains langages comme le Python vous êtes obligés d'indenter correctement parce aue sinon il va y avoir des erreurs. 

En HTML il y a pas de soucis, vous en aurez pas. Vous pourrez trés bien écrire tout au même niveau. Le problème est que c'est vous allez très vite vous y perdre. On voit ici que c'est beaucoup plus lisible : j'écris ma balise <head> à l'intérieur des balises <html> et que je fais une indentation est une tabulation toute simple.
J'écris ma balise <head>, je fais une indentation pour mettre des choses qui corresponde à la section à la balise head.

Je fais pareil avec body ceux qui je fais un code HTML qui est beaucoup plus lisible et si vous devez vous rendre sur votre code pour le maintenir ou le modifier ce sera beaucoup plus simple. Ça aussi on va le faire parce aue c'est très important.