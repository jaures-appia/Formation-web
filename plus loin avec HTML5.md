# Formation Web

le html5 est bien plus vaste qu'on le croit, essayons d'en voir plus :wink:

# Les Tableaux

* Un tableau s'insère avec la balise ```<table>``` et se définit ligne par ligne avec ```<tr>```.

* Chaque ligne comporte des cellules ```<td>``` (cellules normales) ou ```<th>``` (cellules d'en-tête).

* Le titre du tableau se définit avec ```<caption>```.

* On peut ajouter une bordure aux cellules du tableau avecborder. Pour fusionner les bordures, on utilise la propriété CSS ```border-collapse```.

* Un tableau peut être divisé en trois sections : ```<thead>``` (en-tête), ```<tbody>``` (corps) et ```<tfoot>``` (bas du tableau). L'utilisation de ces balises n'est pas obligatoire.

* On peut fusionner des cellules horizontalement avec l'attribut ```colspan``` ou verticalement avec ```rowspan```. Il faut indiquer combien de cellules doivent être fusionnées.

# Les Formulaires

* Un formulaire est une zone interactive de la page, dans laquelle vos visiteurs peuvent saisir des informations.

* On délimite un formulaire avec la balise<form>à laquelle il faut ajouter deux attributs :method(mode d'envoi des données) etaction(page vers laquelle le visiteur sera redirigé après envoi du formulaire et qui traitera les informations).

* Une grande partie des éléments du formulaire peut s'insérer avec la balise<input />. La valeur de son attributtypepermet d'indiquer quel type de champ doit être inséré :

  * text: zone de texte ;

  * password: zone de texte pour mot de passe ;

  * tel: numéro de téléphone ;

  * checkbox: case à cocher ;

  * etc.

* La balise<label>permet d'écrire un libellé. On l'associe à un champ de formulaire avec l'attributfor, qui doit avoir la même valeur que l'iddu champ de formulaire.

* On peut rendre un champ obligatoire avec l'attributrequired, faire en sorte qu'il soit sélectionné par défaut avecautofocus, donner une indication dans le champ avecplaceholder…

* Pour récupérer ce que les visiteurs ont saisi, le langage HTML ne suffit pas. Il faut utiliser un langage « serveur » comme PHP… Si vous voulez aller plus loin, il va donc falloir apprendre un nouveau langage !

# de la video et de l'audio :heart_eyes:

* Insérer de la musique ou de la vidéo n'était pas possible autrefois en HTML. Il fallait recourir à un plugin comme Flash.

* Depuis HTML5, les balises<audio>et<video>ont été introduites et permettent de jouer de la musique et des vidéos sans plugin.

* Il existe plusieurs formats audio et vidéo. Il faut notamment connaître :

  * pour l'audio : MP3 et Ogg Vorbis ;

  * pour la vidéo : H.264, Ogg Theora et WebM.

* Aucun format n'est reconnu par l'ensemble des navigateurs : il faut proposer différentes versions de sa musique ou de sa vidéo pour satisfaire tous les navigateurs.

* Il faut ajouter l'attributcontrolsaux balises<audio>et<video>pour permettre au visiteur de lancer ou d'arrêter le média.

* Ces balises ne sont pas conçues pour empêcher le téléchargement de la musique et de la vidéo. Vous ne pouvez pas protéger votre média contre la copie.

