# Formation-web

salut les passionés :smirk:, vous voulez apprendre le web ? vous êtes au bon endroit.
commencons sans perdre de temps !

# petit mot sur le web 

* Le Web a été inventé par Tim Berners-Lee au début des années 1990.

* Pour créer des sites web, on utilise deux langages informatiques :

  * HTML (HyperText Markup Language) : permet d'écrire et organiser le contenu de la page (paragraphes, titres…) ;

  * CSS (Cascading Style Sheets, aussi appelées Feuilles de style) : permet de mettre en forme la page (couleur, taille…).

* Il y a eu plusieurs versions des langages HTML et CSS. Les dernières versions sont HTML5 et CSS3.

* Le navigateur web est un programme qui permet d'afficher des sites web. Il lit les langages HTML et CSS pour savoir ce qu'il doit afficher.

* Il existe de nombreux navigateurs web différents : Google Chrome, Mozilla Firefox, Internet Explorer, Safari, Opera… Chacun affiche un site web de manière légèrement différente des autres navigateurs.

* Dans ce cours, nous allons apprendre à utiliser les langages HTML et CSS. Nous travaillerons dans un programme appelé « éditeur de texte » (Sublime Text, Notepad++, jEdit, vim…).

# créons notre environnement de travail

nous utiliserons sublime text 3 pour notre formation car c'est un éditeur simple et qui supporte plusieurs langages.
le lien de telechargement : https://www.sublimetext.com/3

suivons ensemble l'installation :runner:

# Les bases du HTML5

* On utilise l'éditeur de texte (Sublime Text, Notepad++, jEdit, vim…) pour créer un fichier ayant l'extension.html(par exemple :test.html). Ce sera notre page web.

* Ce fichier peut être ouvert dans le navigateur web simplement en faisant un double-clic dessus.

* À l'intérieur du fichier, nous écrirons le contenu de notre page, accompagné de balises HTML.

* Les balises peuvent avoir plusieurs formes :

  * ```<balise> </balise>```: elles s'ouvrent et se ferment pour délimiter le contenu (début et fin d'un titre, par exemple).

  * ```<balise />```: balises orphelines (on ne les insère qu'en un seul exemplaire), elles permettent d'insérer un élément à un endroit précis (par exemple une image).

* Les balises sont parfois accompagnées d'attributs pour donner des indications supplémentaires (exemple :<image nom="photo.jpg" />).

* Une page web est constituée de deux sections principales : un en-tête (<head>) et un corps (<body>).

* On peut afficher le code source de n'importe quelle page web en faisant un clic droit puis en sélectionnantAfficher le code source de la page.

* **les commentaire** : on est pas oblige de les utiliser mais ils sont tres utile pour nous retrouver dans notre code car c'est du texte qui n'a aucun impact sur votre code source.
**la syntaxe d'un commentaire html** : ```<!-- Ceci est un commentaire -->```

  ## les paragraphes
  
  Les paragraphes sont définis par la balise ```<p> </p>``` et les sauts de ligne par la balise <br>.
  
  ## les titres
  
  Il existe six niveaux de titre, de ```<h1> </h1>``` à ```<h6> </h6>```, à utiliser selon l'importance du titre.
  
  ## la mise en valeur
  
  On peut mettre en valeur certains mots avec les balises ```<strong>```, ```<em>``` et ```<mark>```
  
  ## les listes
  
  Pour créer des listes, on doit utiliser la balise ```<ul>``` (liste à puces, non ordonnée) ou ```<ol>``` (liste ordonnée). À l'intérieur, on insère les éléments avec une balise ```<li>``` pour chaque item.
  
  ## les liens
  
  * Les liens permettent de changer de page et sont, par défaut, écrits en bleu et soulignés.

  * Pour insérer un lien, on utilise la balise "a" avec l'attributhrefpour indiquer l'adresse de la page cible. Exemple : ```<a href="https://google.com">```.

  * On peut faire un lien vers une autre page de son site simplement en écrivant le nom du fichier : ```<a href="page2.html">```.

  * Les liens permettent aussi d'amener vers d'autres endroits sur la même page. Il faut créer une ancre avec l'attributidpour « marquer » un endroit dans la page, puis faire un lien vers l'ancre comme ceci : ```<a href="#ancre">```.
  
  ## les images :boom:
  
  * Il existe plusieurs formats d'images adaptées au Web :

  * JPEG : pour les photos ;

    * PNG : pour toutes les autres illustrations ;

    * GIF : similaire au PNG, plus limité en nombre de couleurs mais qui peut être animé.

  * On insère une image avec la balise  ```<img />```. Elle doit obligatoirement comporter au moins ces deux attributs :  src(nom de l'image) et  alt(courte description de l'image).

  * Si une image illustre le texte (et n'est pas seulement décorative), il est conseillé de la placer au sein d'une balise  ```<figure>```. La balise  ```<figcaption>``` permet d'écrire la légende de l'image.
  
# :clap: bravo vous maitrisez maintenant la base du html5, mettons tous sa en pratique

avec ce qu'on sait, essayons de commencer notre cv :yum:

