### Des notions HTML

1. HTML
HyperText Markup Language ( langage de balise hypertexte)

=> un fichier .HTML c'est d'abord du texte.
=> il est écrit par un développeur (avec VScode par exemple)
=> il est vu par un utilisateur ( avec Firefox par exemple)

Une balise HTML s'écrit : <maBalise></maBalise> 

**Ex** <h1></h1>

Le texte s'écrit **entre les balises**

**Ex** <h1>Mon texte</h1>

Il existe aussi des balises orphelines : `<!Doctype html>, <br>, <img> ...`  

Référence : Mozilla [https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements)

Une balise ouvrante peut contenir un attribut, notemment `class=""` :

`<h1 class="maClasse"></h1>`

Quelques balises importantes :
- `<h1></h1>` : titres
- `<p></p>` : paragraphes
- `<a href=""></a>` : lien
- `<ul></ul>` : listes sans ordre
- `<ol></ol>` : listes avec ordre
- `<li></li>` : faire des items de liste
- `<img src="">` : ajouter une image

Pour trouver le chemin vers un fichier, on peut regarder :
- dans le dossier courant avec `./`
- dans un dossier extérieur avec `../`


2. CSS

Cascading Style SHeet : page de style en cascade

On peut écrire du CSS :
- directement dans lefichier HTML entre les balises `<style></style>`
- dans une fichier `CSS`

Pour écrire du CSS, il faut un sélecteur (nom d'une balise ou d'une class), des accolades, des propriétées, des valeurs.

```css
selecteur {
    propriete1 : valeur1;
    propriete2 : valeur2;
}
```

Il existe plus de 500 propriétés et encore d'avantages de valeurs possibles. Cependant, les valeurs sont souvent :
- une couleur
- une taille

Rem : on trouve toutes les propriétés sur le site ds développeurs de Mozilla.

Les propriétés CSS s'appliquent en cascade, des éléments les plus globaux (`body`, `div`) vers les éléments les plus internes (pour finir par les classes).

Remarque : principe du modèle en boite.
Les éléments d'une page sont contenus dans une boite entourée d'une bordure (invisible par défaut).
L'espace entre :
- le contenu et la bordure s'appelle `padding`
- la bordure et les éléments autour s'appelle `margin`.

La bordureborder  peut elle-même avoir un style.

Remarque : les conteurs universels sont `<div></div>` et `<span></span>`.

Il existe de nombreuses propriétés relaives au texte:
- 