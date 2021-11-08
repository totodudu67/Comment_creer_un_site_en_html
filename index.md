Avant de commencer je vous propose d'installer un editeur qui vas nous permettre de pouvoir créer un site en HTML.
Je vous en donne deux un GRATUIT et un PAYANT :

- Sublime Text (G)

- Adobe Dreamweaver (P)

### 1- LES BALISES :

Pour coder en HTML on va devoir donner des instructions a notre ordinateur. On utilise pour cela des balises.

Les pages HTML sont remplies de ce qu'on appelle des balises. Celles-ci sont invisibles à l'écran pour vos visiteurs, mais elles permettent à l'ordinateur de comprendre ce qu'il doit afficher.


Les balises se repèrent facilement. Elles sont entourées de « chevrons », c'est-à-dire des symboles `< et >` , comme ceci : `<balise>`  .

À quoi est-ce qu'elles servent ? Elles indiquent la nature du texte qu'elles encadrent. Elles veulent dire par exemple : « Ceci est le titre de la page », « Ceci est une image », « Ceci est un paragraphe de texte », etc.

On distingue deux types de balises : les balises en paires et les balises orphelines.

### Les balises en paires :

Elles s'ouvrent, contiennent du texte, et se ferment plus loin. Voici à quoi elles ressemblent :

```markdown
<titre>On place ici le titre de notre site</titre>
```

On distingue une balise ouvrante `<titre>` et une balise fermante `</titre>` qui indique que le titre se termine. Cela signifie pour l'ordinateur que tout ce qui  **n'est** **pas** entre ces deux balises… n'est pas un titre.

```markdown
On ne place pas notre titre ici <titre>Mais là</titre> Mais pas là
```
### Les balises orphelines

Ce sont des balises qui servent le plus souvent à insérer un élément à un endroit précis (par exemple une image). Il n'est pas nécessaire de délimiter le début et la fin de l'image, on veut juste dire à l'ordinateur « Insère une image ici ».

Une balise orpheline s'écrit comme ceci :

```markdown
<image />
```


### _i_-) Notez que le / de fin n'est pas obligatoire. On pourrait écrire seulement <image> . Néanmoins, pour ne pas les confondre avec le premier type de balise, les webmasters recommandent de rajouter ce /  (slash) à la fin des balises orphelines. Vous me verrez donc mettre un /  aux balises orphelines et je vous recommande de faire de même.
  
### Les attributs

Les attributs sont un peu les options des balises. Ils viennent les compléter pour donner des informations supplémentaires. L'attribut se place après le nom de la balise ouvrante et a le plus souvent une valeur, comme ceci :
  
```markdown  
<balise attribut="valeur">
```
À quoi cela sert-il ? Prenons la balise `<image />`  que nous venons de voir. Seule, elle ne sert pas à grand-chose. On pourrait rajouter un attribut qui indique le nom de l'image à afficher :
  
```markdown 
<image nom="photo.jpg" />
```
  
L'ordinateur comprend alors qu'il doit afficher l'image contenue dans le fichier `photo.jpg`.

Dans le cas d'une balise fonctionnant « par paire », on ne met les attributs que dans la balise ouvrante et pas dans la balise fermante. Par exemple, ce code indique que la citation est de Neil Armstrong et qu'elle date du 21 juillet 1969 :
  
```markdown
<citation auteur="Neil Armstrong" date="21/07/1969">
C'est un petit pas pour l'homme, mais un bond de géant pour l'humanité.
</citation>
```
  
### _i_-) Toutes les balises que nous venons de voir sont fictives. Les vraies balises ont des noms en anglais (eh oui !) ; nous allons les découvrir par la suite.
  
### 2- Structure de base d'une page HTML5
  
