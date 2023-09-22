# Markdown

Markdown est un langage de balisage léger créé en 2004 par John Gruber, avec l'aide d'Aaron Swartz1,2, dans le but d'offrir une syntaxe facile à lire et à écrire en l'état dans sa forme non formatée. Markdown est principalement utilisé dans des blogs, des sites de messagerie instantanée, des forums et des pages de documentation de logiciels.

## Pourquoi utiliser le Markdown ?

Markdown est une solution utile à mi-chemin entre les fichiers textes bruts et les logiciels de traitement de texte aux formats hérités. Sa syntaxe simple est facile à apprendre et lisible non seulement en tant que telle, mais aussi après conversion en HTML et vers d'autres formats.

## La syntaxe markdown

Pour formater votre texte vous avez la possibilité d'utiliser la barre d'outils située au-dessus de la zone de texte, ou vous pouvez utiliser la syntaxe markdown.

### Les titres

Pour faire un titre, vous devez mettre un `#` devant la ligne. Pour faire un titre plus petit, vous pourrez créer jusque 6 niveaux de sous-titres.

`#  Titre 1`
`## Titre 2`
`###  Titre 3`
`#### Titre 4`
`#####  Titre 5`
`###### Titre 6`

# Titre 1

## Titre 2

### Titre 3

#### Titre 4

##### Titre 5

###### Titre 6

### Styles de texte

Vous pouvez utiliser \_ ou \* autour d'un mot pour le mettre en italique. Mettez-en deux pour le mettre en gras.

`_italique_` s'affiche ainsi : _italique_
`**gras**` s'affiche ainsi : **gras**
`**_gras-italique_** ` s'affiche ainsi : **_gras-italique_**
`~~barré~~` s'affiche ainsi : ~~barré~~

### Blocs de code

Créez un bloc de code en indentant chaque ligne avec quatre espaces, ou en mettant trois accents graves sur la ligne au dessus et en dessous de votre code. Exemple :  
 ` ```bloc de code``` `s'affiche ainsi : `bloc de code`

### Liens

Créez un lien intégré en mettant le texte désiré entre crochets et le lien associé entre parenthèses.

Aidez-vous avec ` [la documentation de Framasite](https://docs.framasoft.org/fr/grav/)` !

s'affichera : [la documentation de Framasite](https://docs.framasoft.org/fr/grav/) !

Aidez-vous avec la documentation de Framasite !

Vous pouvez ajouter aux liens des attributs `id `et `class` de cetImage d'une montgofiere !te manière :
`[la documentation de Framasite](https://docs.framasoft.org/fr/grav/){#id .class1 .class2}`

### Images

Utilisez une image en ligne en copiant son adresse (finissant par .jpg, .png, .gif etc…) avec un texte alternatif entre crochets (qui sera affiché si l'image n'apparaît pas) et le lien entre parenthèses.

![le logo de Framasoft](https://www.meditationfrance.com/2022-images/blague-meditation.jpg)

Vous pouvez aussi ajouter un texte qui apparaîtra au survol.
`![le logo de Framasoft](https://www.meditationfrance.com/2022-images/blague-meditation.jpg "Image fun")`

![le logo de Framasoft](https://www.meditationfrance.com/2022-images/blague-meditation.jpg "Image fun")

### Citation

Les citations se font avec le signe > :

`> Oh la belle prise !`
Oh la belle prise !

### Listes

Vous pouvez créer des listes avec les caractères \* et - pour des listes non ordonnées ou avec des nombres pour des listes ordonnées.

Une liste non ordonnée :

     * une élément
     * un autre
            * un sous élément
            * un autre sous élément
    * un dernier élément

- une élément
- un autre
  - un sous élément
  - un autre sous élément
- un dernier élément

### Une liste ordonnée :

`1. élément un`
`2. élément deux`

1. élément un
2. lément deux

`| Aligné à gauche  | Centré          | Aligné à droite |`
` | :--------------- |:---------------:| -----:|`
`| Aligné à gauche  |   ce texte        |  Aligné à droite |`
`| Aligné à gauche  | est             |   Aligné à droite |`
`| Aligné à gauche  | centré          |    Aligné à droite | `

| Aligné à gauche |  Centré  | Aligné à droite |
| :-------------- | :------: | --------------: |
| Aligné à gauche | ce texte | Aligné à droite |
| Aligné à gauche |   est    | Aligné à droite |
| Aligné à gauche |  centré  | Aligné à droite |

### Ajouter un GIF avec un URL externe markdown.

`![color picker](https://static-cse.canva.com/blob/604068/giphy.gif)`

![color picker](https://static-cse.canva.com/blob/604068/giphy.gif)
