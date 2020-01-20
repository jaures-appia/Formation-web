# formation web

Apres les bases de HTML5, nous voici devant le grand portail du CSS3.
ne restons pas la ! **ENTRONS !** :runner:

# Mettons en place le css

* CSS est un autre langage qui vient compléter le HTML. Son rôle est de mettre en forme votre page web.

* Il faut être vigilant sur la compatibilité des navigateurs avec certaines fonctionnalités récentes de CSS3. Quand un navigateur ne connaît pas une instruction de mise en forme, il l'ignore simplement.

* On peut écrire le code CSS à plusieurs endroits différents, le plus conseillé étant de créer un fichier séparé portant l'extension.css(exemple :style.css).

* En CSS, on sélectionne quelles portions de la page HTML on veut modifier et on change leur présentation avec des propriétés CSS :

  ```
  balise1
  {
      propriete1: valeur1;
      propriete2: valeur2;
  }
  ```
* Il existe de nombreuses façons de sélectionner la portion de la page que l'on veut mettre en forme. Par exemple, on peut viser :

  * toutes les balises d'un même type, en écrivant simplement leur nom (h1par exemple) ;

  * certaines balises spécifiques, auxquelles on a donné des noms à l'aide des attributs class ou id(.nomclasse ou #nomid) ;

  * uniquement les balises qui se trouvent à l'intérieur d'autres balises (h3 em).

  * pour plus d'info sur ce site veuillez visiter ce site https://developer.mozilla.org/fr/docs/Web/CSS/S%C3%A9lecteurs_CSS
  
# Formater du texte

* On modifie la taille du texte avec la propriété CSS ```font-size```. On peut indiquer la taille en pixels (16px), en « em » (1.3em), en pourcentage (110%), etc.

* On change la police du texte avec ```font-family```. Attention, seules quelques polices sont connues par tous les ordinateurs. Vous pouvez cependant utiliser une police personnalisée avec la directive ```@font-face``` : cela forcera les navigateurs à télécharger la police de votre choix.
  
  **quelque police qui existe par defaut dans les navigateur**
    
    * **Arial**

    * **Arial Black**

    * **Comic Sans MS**

    * **Courier New**

    * **Georgia**

    * **Impact**

    * **Times New Roman**

    * **Trebuchet MS**

    * **Verdana**.

* De nombreuses propriétés de mise en forme du texte existent : ```font-style``` pour l'italique, ```font-weight``` pour la mise en gras,```text-decoration``` pour le soulignement, etc.

* Le texte peut être aligné avec ```text-align```.

* On peut faire en sorte qu'une image soit habillée (« entourée ») de texte avec ```float```

# Ajoutons de la couleur et du fond :heartpulse:

* On change la couleur du texte avec la propriété On change la couleur du texte avec la propriété On change la couleur du texte avec la propriété ```color```, la couleur de fond avec ```background-color```.

* On peut indiquer une couleur en écrivant son nom en anglais (```black```, par exemple), sous forme hexadécimale (#FFC8D3) ou en notation RGB (```rgb(250,25,118```)).

* On peut ajouter une image de fond avec ```background-image```. On peut choisir de fixer l'image de fond, de l'afficher en mosaïque ou non, et même de la positionner où on veut sur la page.

* On peut rendre une portion de la page transparente avec la propriétéopacityou avec la notation RGBa (identique à la notation RGB, avec une quatrième valeur indiquant le niveau de transparence).

# Les bordures et les ombres

* On peut appliquer une bordure à un élément avec la propriété ```border. Il faut indiquer la largeur de la bordure, sa couleur et son type (trait continu, pointillés…).

* On peut arrondir les bordures avec ```border-radius```.

* On peut ajouter une ombre aux blocs de texte avec ```box-shadow```. On doit indiquer le décalage vertical et horizontal de l'ombre, son niveau d'adoucissement et sa couleur.

* Le texte peut lui aussi avoir une ombre avec ```text-shadow```.

# Creons des apparences dynamiques :boom: :blush:

* En CSS, on peut modifier l'apparence de certaines sections dynamiquement, après le chargement de la page, lorsque certains évènements se produisent. On utilise pour cela les pseudo-formats.

* Le pseudo-format ```:hover``` permet de changer l'apparence au survol (par exemple : ```a:hover``` pour modifier l'apparence des liens lorsque la souris pointe dessus).

* Le pseudo-format ```:active``` modifie l'apparence des liens au moment du clic,```:visited``` lorsqu'un lien a déjà été visité.

* Le pseudo-format ```:focus``` permet de modifier l'apparence d'un élément sélectionné.

# Good avec tout ce qu'on sait, on peut dire qu'on est des pros du css :bowtie:

bref... mettons tous sa en pratique !

