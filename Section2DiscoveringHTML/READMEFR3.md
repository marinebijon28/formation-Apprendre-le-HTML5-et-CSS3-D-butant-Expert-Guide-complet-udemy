#### formation udemy : Apprendre le HTML5 et CSS3 Debutant Expert Guide Complet 

### Section 2 : Découverte du langage HTML

## Les bases du langages HTML

# Syntaxe HTML
Dans cette section on va s'intéresser au base du HTML. Comment on peut construire du HTML et notamment voir comment fonctionne HTML au niveau de la syntaxe. La syntaxe n'est pas très compliquée parce que c'est un langage de balisage.
Pour créer une phrase dans un fichier HTML, on va tout simplement utiliser des balises. 

# Example de balise
<p>Ceci est une phrase</p>
J'ai donc une phrase qui est <p>Ceci est une phrase.</p>. On peut voir que j'ai de deux balises <p> qui sont apparue. C'est une balise qui permet d'écrire un paragraphe en HTML.
Cette balise on peut voir qu'il y en a deux :
- La première c'est la balise ouvrante
- Ensuite, vous avez la balise fermante

Elle est constituée pour la balise ouvrante d'un chevron ouvrant de la lettre, ou le nom de la balise, en l'occurence p et d'un chevron fermant.
Ensuite, on y met nos phrases, nos textes, nos paragraphes. Quand nos paragraphes sont terminés. On va simplement utiliser, un chevron ouvrant, un slash, le nom de la balise et on referme avec un chevron fermant.

# Élément HTML
Ça c'est une balise en fait qui marche par paire : c'est-à-dire qu'il y a une balise ouvrante et une balise fermante automatiquement.
La différence entre la balise ouvrante et fermante, c'est le slash. Cela permet aux navigateurs ce qu'il y a entre eux les balise ouvrante et fermante est tout simplement un paragraphe. Alors, si on prends le contenu complet. Les balises et la phrase : on appelle cela est un élément HTML. C'est important de bien le comprendre

# Attributs
Ensuite, on va avoir des éléments qui sont des attributs. Des attributs c'est très simple.

<p         </p>
Ici nos balises <p>. On peut voir que la balise ouvrante est un peu différente que d'habitude parce que je n'ai pas mis de chevron fermant. J'ai la balise fermante qui est tout fait classique.

<p class="important"></p>
<p class='important'></p>
Pourquoi je n'ai pas fermé la balise le chevron de balise ouvrante. Si on doit ajouter un attribut c'est là où on doit le mettre. Si j'utilise l'attribut class. On verra plus tard ce que c'est. Je lui affecte avec le signe égale avec des simple quote ou des double quote ça marcherai aussi.

Important ça veut dire que ce paragraphe dépends de la classe important. Vous ne savez pas encore ce que c'est. La class va permettre tout simplement de revenir sur ce paragraphe est de modifier grâce au CSS sont apparence. En tout cas, il existe en beaucoup et on peut voir que c'est assez simple à utiliser. On va les utiliser en déclarant les attributs dans la balise ouvrante.

<p class='important'>Ceci est mon paragraphe</p>
Ensuite qu'en j'ai fait ça, je mets mon texte. Là cela va fonctionner, mais au niveau de la classe vous ne le verrez pas à l'affichage. Le HTML sait qu'il y a un attribut class qui s'appelle important.

<p class="important"></p>
Cette partie est la balise ouvrante. J'ouvre mon p et au lieu de le refermer directement avec le chevron fermant, je vais y mettre mes attributs. C'est comme ça que cela va fonctionner et ici on peut observer une balise fermante.

Le HTML va être simplement le fait de connaître les balises et les attributs, etc. À force vous allez voir que vous allez les retenir facilement. De plus, je vais vous expliquer : les balises, les attributs. 

# Mozilla Développer Réseaux
On va voir les plus importantes, mais il est possible que vous tombiez sur des balises que vous ne connaissez pas. Je vais vous donner l'adresse d'un site qui s'appelle Mozilla Developer Network : developer.mozilla.org/fr/. C'est très intéressant, ce site en fait va vous permettre d'utiliser la documentation HTML qui est en plus traduite. 

Une fois que vous êtes sur le site, vous allez au niveau de technologies et vous choisissez HTML.
Alors, là on peut voir sur le menu gauche qui va être intéressante, vous avez la documentation et vous avez toutes les références. C'est ça qui va nous intéresser, si je cherche ici, je demande d'afficher les éléments HTML. On peut voir une liste qui est apparue assez conséquente, qui possède tous les éléments HTML. Si je descends, comme c'est classé par ordre alphabétique. 

On va pouvoir observer que j'ai mon <p>. Si je clique dessus. Ça va m'indiquer : l'élément HTML <p> représente un paragraphe de texte. Les paragraphes sont généralement représentés comme des blocs et séparés par un espace vertical. On a même un exemple en dessous, mais qui contient du texte, on ne va pas s'en occuper pour le moment. Si on descend on a encore des exemples, on nous explique des choses.

On a surtout les attributs de cette balise. En fait, cet élément comme les autres élément HTML a inclus les attributs universels. Quand il n'y a pas vraiment d'attribut spécifique à cette balise, vous allez pouvoir utiliser les attributs universels. si vous utilisez une balise qui a des attributs bien spécifiques. Elles vont apparaitre là et elles vont être expliquées.

Si on revient au niveau de technologies HTML. On va pouvoir aussi observer qu'en dessous d'élément HTML. On a les attributs universels, on peut en voir pas mal, ce qui va être assez intéressant.

On peut découvrir class, si je clique sur class : L'attribut universel class indique une liste de classe associée à l'élément courant. Grâce au CSS ensuite on va pouvoir accéder aux paragraphes qui ont comme attribut la classe : class="note editorial". Dans notre cas c'était important, si j'avais attribué cette classe à plusieurs paragraphes. Je pourrais grâce aux CSS sur l'apparence de tous les paragraphes simplement dans le CSS, c'est assez intéressant.

Autre chose que je voulais signaler sur le site : c'est que vous avez des éléments HTML avec une petite poubelle rouge à côté, ça veut dire que c'est obsolète et qu'il faut éviter de l'utliser. Cette fonctionnalité est obsolète : cette fonctionnalité a été supprimée des standards du Web. Bien que quelques navigateurs puissent encore la supporter, elle est en cours d'éradication. Ne l'utilisez ni dans d'anciens projets, ni dans de nouveaux. Les pages et applications Web l'utilisant peuvent cesser de fonctionner à tout moment.

De la même manière que vous avez un pouce bleu vers le bas qui vous dit que ce n'est pas standardisé. Il vous dit : cet élément n'est pas standard et ne doit pas être utilisé ! Pour intégrer du son à une page web, on utilisera l'élément <audio>. En gros elle ne fonctionnera pas forcément si vous êtes sur internet pour une utilisation pour tout le monde. 

Vous avez tout ce qu'il faut ici. Si vous revenez au niveau de HTML et des attributs. Vous avez quelques petits icones ici une balise ou attribut expérimental qui ne vaut mieux pas l'utiliser en production. Bien que la prise en charge de cet attribut ne soit pas homogène pour les navigateurs, celui-ci est pris en compte par les outils de traduction automatique (Google traduction par exemple) et les outils de traduction utilisées par les traducteurs. De plus, cet attribut doit être utilisé par les auteurs web afin d'indiquer correctement le contenu qui ne devrait pas être traduit. Vous aurez bien compris qu'il faut l'utiliser.

Alors, ce site Mozilla Developer Network va vous être dans grand secours. Si ce n'est pas traduit vous pouvez le changer cliquer changer la langue, vous allez être en bas de la page et vous allez pouvoir la sélectionner.

# Les éléments imbriqués
Pour les éléments ça ne va pas être bien compliqué.
<p>apprendre le<strong> html </strong>c'est facile</p>
Vous pouvez voir ici à l'écran j'ai toujours mon paragraphe avec un texte différent : apprendre le html c'est facile. 

<p>apprendre le html c'est facile</p>
On voit que j'ai mis des balises pour le paragraphe ouvrante et fermante. 

<p>apprendre le<strong> html </strong>c'est facile</p>
Vous pouvez apercevoir à l'intérieur que j'ai imbriqué deux balises strongs. Elles entourent le texte html avec la balise ouvrante à gauche avec : le chevron ouvrante, strong et le chevron fermant. La balise fermante avec : chevron ouvrant, slash, strong, chevron fermant. 

Pour savoir ce qui est la balise strong aller voir la documentation ça va me permettre de mettre le texte en gras. Le HTML va être-là pour le contenu. Le rôle du CSS est justement la mise en forme donc par exemple mettre en gras. Là il ne faut pas voir les balises strong comme pour dire je vais placer mon texte en gras. Les balises strong exprime de la sémantique. Tout simplement le mot html a une consonance forte de ma phrase donc grâce ces balises en CSS. Je vais pouvoir appliquer quel style que je veux : le laisser en gras, en italique, changer la couleur, etc. C'est le point de vue de la partie sémantique. Ces balises strong, il ne faut pas les utiliser juste pour mettre en gras, même si le font. C'est surtout pour dire que ce texte est important.

<p>apprendre le<strong> html </strong>c'est facile</p>
Vous pouvez voir que j'ai bien les balises strong imbriqués dans mon paragraphe.

<p>apprendre le<strong> html </p>c'est facile</strong>
Alors, attention si vous faites ce genre de ligne de code vous pouvez. On peut voir que j'ai bien la balise ouvrante cet élément <p> et <strong> qui est inversé donc elle se chevauche. On peut voir que ça ne fonctionne pas.

<p>apprendre le<strong> html </strong>c'est facile</p>
En fait, les balises fonctionnent par paires les deux <p><strong></strong></p>.

<p>apprendre le<strong> html </p>c'est facile</strong>
Ma balise <p> chevauche la balise sans être fermée <strong> chevauche ma balise fermante </p> chevauche la balise fermante </strong>. Vous n'aurez pas une erreur en HTML, mais vous aurez un comportement inattendue, un affichage bizarre. La première balise est la balise <p> est le navigateur va comprendre que c'est un paragraphe. Au milieu j'ai une balise strong qui n'est pas vide ou orpheline (y a deux types de balises les paires et les vides qu'on appelle aussi orpheline) normalement il faut une balise fermante. Vous allez avoir un problème d'affichage, mais par contre vous pouvez voir que le paragraphe est bien existant. Attention ici a bien ouvrir une balise et bien la fermer. Si vous les imbriquez faites bien attention qu'elles soient bien à l'intérieur.

# Éléments vides
Un élément vide c'est tout simplement une balise qu'on va dire qu'elle est orpheline. On a pu voir que les balises précédentes fonctionnaient par paire. Les balises orphelines ou vides fonctionnent toute seule.

<img src="pictures/equitation.png" alt="Image de cheval" />
Vous pouvez voir que j'ai ma balise <img>. Elle est ouverte et on voit bien le chevron qui la ferme. Pourquoi il y a des choses au milieu, les balises vides s'utilisent un peu différemment. 

src="pictures/equitation.png"
Par contre, à l'intérieur on va y glisser des attributs, comme notre classe. Là ce sont des attributs différents qui sont bien souvent l'attribut src ici va être réservé à la balise <img>. La balise src c'est la source donc le chemin de mon image. Le chemin sera pictures et le fichier s'appelle equitation.png.

alt="Image de cheval"
Ensuite, vous pouvez voir une deuxième balises alt, c'est ce qui va être dit pour le déficient visuel. Si quelqu'un est aveugle, les aveugles naviguent sur les navigateurs rassuraient-vous. Ils ont souvent des logiciels de lecture donc ça lit la page. C'est que si vous dites à l'attribut alt, il ne saura pas lire l'image c'est normal. L'image va être remplacée par le texte image de cheval. C'est un attribut très important surtout dans la balise <img>.

On va voir durant ce cours voir l'ensemble des balises et des attributs intéressants. Encore une fois, aidez-vous de la documentation. Le but de ce cours est de vous rendre autonome.

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
On va s'intéresser à la structure d'un fichier HTML. C'est très important. Il y a plusieurs choses à voir :

<!DOCTYPE html>
- La première chose, c'est qu'on va rencontrer en haut du fichier une balise un peu spéciale. Chevron ouvrant, point d'exclamation, DOCTYPE, plus loin html et chevron fermant. Le doctype c'est très important, celui-ci correspond au HTML5 et vous allez devoir le renseigner. Pourquoi ce Doctype on doit le déclarer parce qu'auparavant vous aviez des versions. Maintenant vous n'avez plus que du HTML5 mais auparavant on utilisait plusieurs versions de HTML en même temps. Le doctype était différent pour dire à votre navigateur ce qui suit c'est du HTML 3, 4, 5. Le problème de ce doctype était assez long à renseigner. Avec HTML5 vous devez juste retenir que vous inscrivez ce doctype à chaque fois il n'y a pas le comprendre. Ça correspond au doctype pour dire navigateur c'est du HTML5.

- Ensuite, vous pouvez observer deux balises une ouvrante et un fermante <html></html>. C'est balise c'est la qu'on va mettre tout le contenu de notre site web.

- Ensuite, vous pouvez voir deux balises <head></head> qui se traduit en français tête ca va être le header. Tout ce qui va correspondre aux renseignements du site. Par exemple : le titre de la page, on va y mettre des balises meta. On pourrait y mettre plein de choses par exemple : des balises, des metas pour que le site soit mieux indexé sur les moteurs de recherche. Ce ne sont pas des choses qui vont se voir, mais qui vont être important.

- Ensuite, on a une deuxiéme balises juste en-dessous qui est à la même hauteur qu'on appelle body qu'on traduit par le corps. Ça va être le corps de votre message. Ici on peut voir qu'il y a simplement un paragraphe.

Ce qu'il faut retenir c'est que la structure d'une page HTML :
- Commence par son doctype,
- Ensuite on y insère deux balises html ouvrantes et fermantes. À l'intérieur de cette balise on va y mettre d'autres balises :
    - le head donc le header
    - le body et en dessous du head

Ça c'est une structure très simple, mais elle est obligatoire à connaître rassurez-vous il y a de petites facilitées au niveau des éditeurs de codes qui vont nous permettre de ne pas forcément devoir à la retenir.

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
Ensuite, je voulais vous parler de l'importance de l'indentation. J'ai écrit ma balise <html>, l'éditeur dessine un trait afin de montrer que les balises sont au même niveau. Même si elle se trouve plus bas et que des balises soient imbriqués.
Entre chaque balise paire si on ouvre une autre balise <head> à l'intérieur, elle sera décalée au niveau de l'indentation soit une tabulation. 

Elle va vous permettre dans certains langages comme le Python vous êtes obligés d'indenter correctement parce que sinon il va y avoir des erreurs. 

En HTML il n'y a pas de souci, vous en aurez pas. Vous pourrez très bien écrire tout au même niveau. Le problème est que c'est vous allez très vite vous y perdre. On voit ici que c'est beaucoup plus lisible : j'écris ma balise <head> à l'intérieur des balises <html> et que je fais une indentation est une tabulation toute simple.
J'écris ma balise <head>, je fais une indentation pour mettre des choses qui correspondent à la section à la balise head.

Je fais pareil avec le body ceux ont déjà fait code HTML qui est beaucoup plus lisible et si vous devez-vous rendre sur votre code pour le maintenir ou le modifier ce sera beaucoup plus simple. On va le faire parce que c'est très important.