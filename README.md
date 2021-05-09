# Markdown
[Itilicizing text](#itilicizing-Text)

[Bolding Text](#bolding-text)

[Striking Through Text](Striking-Through-Text)

[Adding an External Link](#Adding-an-External-Link)

[Creating Heading](#Creating-Heading)

[Creating Blockquote](#Creating-Blockquote)

[Creating a Heading with Underline](#Creating-a-Heading-with-Underline)

[Adding an internal link or table of content](#Adding-an-internal-link)

[Lists](#Lists)

[Images](#Images)

[Creating a Image with a link](#Creating-a-Image-with-a-link)

[Tables](#Tables)

[Colors for fonts](#Colors-for-font)

[Inlining Code](#Inlining-Code)

[Creating Block of Code](#Creating-Block-of-Code)

[Creating a Task List](#Creating-a-Task-List)



# itilicizing Text
Ambos permiten italic la palabras hay dos maneras de hacerlo con _ o * al principio y al final

`\_Hello, how are you doing?_`


`\*Hello, how are you doing?*`

_Hello, how are you doing?_

*Hello, how are you doing?*

Si queremos usar el underscore sin que se vuelva italic usamos el bashslash \ para escape  
Ejemplo:

`\\_Hello, how are you doing?`

[Index](#Comandos)

# Bolding Text
Para poner una palabra **Bold** ponemos ** al principio y ** a final o el __ y __ al final
here is something **important**.

here is something `**important**`

here is something `__important__`

here is something __important__.

si queremos **italic** y **bold** en la misma palabra o oracion podemos usar `**_Something_**`

**_Something_**

Podemos usar los `\` para escape algun comando de markdown

[Index](#Comandos)


# Striking Through Text
el strike se usa cuando se esta documentando algo pero cambio y lo queremos dejar como referencia pero diciendo que no es asi ya

You should start the app with ~~start~~ **go**.

`**~~strike throught~~**`

[Index](#Comandos)
# Adding an External Link
Para poner un link para un website
podemos el link y nos va a salir en nuestro markdown

www.github.com

Hay otra manera para hacerlo tambien que no sale el link completo pero si la palabra azul y podemos clickiar y nos lleva el link.

`[Github](https://www.github.com)`

[Github](https://www.github.com)

si queremos escribir algo pero queremos que nos lleve al link como en este ejemplo lo hacemos [asi] . el link nos va a salir en la palabra _asi_.
```
[asi]:

\(http://www.link.com)**
```
[asi]:
(https://www.google.com)

[Index](#Comandos)

# Creating Heading
Para hacer un heading es super sincillo y hace un level 1 heading

Heading level 1 - \<h1>


`# Chapter:1: How to use Markdown `

## Heading in markdown
`##Heading level 2` - esto como \<h2>

### Heading level 3
`### Heading level 3`  - esto es como un \<h3>

#### Heading level 4
`#### Heading level 4`

##### Heading level 5
`##### heading level 5`

[Index](#Comandos)

# Creating Blockquote
What is a blockquote? es como un pedazo de pensamiento o bloque de texto para llamar la attencion o usarlo como referencia cuando le hagamos un quote de alguien.
lo hacemos con el operador de **>**

as Ghandi said:
> Be the change you want to see in the word.
```
as Ghandi said:

> Be the change you want to see in the word.
```

Yoyo says:
> Markdown is awesome.
> it really really is

```Yoyo says:

> Markdown is awesome.

> it really really is
```
[Index](#Comandos)

# Creating a Heading with Underline
Eso lo hacemos asi:

Something important

`==`

Something important
==

para hacer la lenia un poco mas abajo no junto con el heading:

something important

`---`

`subnetting`

`---`

`---`

nos hace cuantas lineas queramos

Something important

---
subnetting
---
---
[Index](#Comandos)
# Adding an internal link
### Table of content
[Chapter 1](#chapter-1)

[Chapter 2](#chapter-2)

[Chapter 3](#chapter-3)

---

### Chapter 1
aksldjaslkdj daskldjaslk  aksdjals lkasjdlkas da

asjdklasjdlaskjdasldjklda

[Return to TOC](#table-of-content)
### Chapter 2
sakdjksaldjaskldjasdaks askdjaklsdj aklsjdklasdj aaklsjd

asjdklasjdklas aksljdaskldja aklsjdklasjdalks askldjaklsjd

[Return to TOC](#table-of-content)


### Chapter 3

sakljdaskldjas aklsjdaklsdj daklsjdklas daklsajdaskl djas

askldjlkasjda alksjdalksjdklas

askjdjaklsdjaslkdjaslkdjaskldj

[Return to TOC](#table-of-content)


```Lo hacemos asi:

### Table of content

[Chapter 1](#chapter-1)

[Chapter 2](#chapter-2)

[Chapter 3](#chapter-3)

---

### Chapter 1

text text text text

text text text text

[Return to TOC](#table-of-content)

### Chapter 2

text text text text

text text text text

[Return to TOC](#table-of-content)

### Chapter 3

sakljdaskldjas aklsjdaklsdj daklsjdklas daklsajdaskl djas

askldjlkasjda alksjdalksjdklas

askjdjaklsdjaslkdjaslkdjaskldj

[Return to TOC](#table-of-content)
```
[Index](#Comandos)

# Lists
Solo escribimos los numeros

1. Mikl
2. Bread
3. Bacon

Grociries:

- Cheese

- Milk

```
Groceries:

- Cheese 

- Milk
```
o podemos hacerlo con * o con +

* Milk
```
 * Milk

 + Milk
```
## Para hacer un sublist

* Milk

    + heavy scream
    + sin Grasa
```
* Milk

tab * + heavy scream

tab + * Sin Grasa
```
[Index](#Comandos)


# Images
Para anadir una imagen local

![hacker](hacker.gif)

Asi se hace parececido a internal link solo lo llamamos como se llama en el folder y con este comando

`![hacker](hacker.gif)`

Tambien las imagenes no tienen que estar interna podemos hacerla con imagenes del internet

![test](https://media.giphy.com/media/26tP3M3i03hoIYL6M/giphy.gif)

`![test](https://media.giphy.com/media/26tP3M3i03hoIYL6M/giphy.gif)`

[Index](#Comandos)

# Creating a Image with a link
Si tenemos un logo o algo parecido el formato es diferente
y hacerlo un clickeable link

[![Nene](https://media.giphy.com/media/26tP3M3i03hoIYL6M/giphy.gif)](https://google.com)

`[![Nene](https://media.giphy.com/media/26tP3M3i03hoIYL6M/giphy.gif)](https://google.com)`

Seria este orden

\[!\[Descripcion de la imagen]\(Imagen interna o link web a la imagen)]\(Link del internet que queremos)

si el link es muy largo podemos crear una referencia al final del markdown y llamarlo para que sea mas corto el link y nuestro markdown se vea mas lino en el codigo

[logo]:
https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg

```
[logo]:

Link que queremos https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg

lo llamamos con el nombre que creamos

[![md][logo]](https://amazon.com)
```
[![md][logo]](https://amazon.com)

[Index](#Comandos)

# Tables

Este es el comando para hacer tablas

| Food    |   Facts   | Carbs  | Proteins       |
|---------|:-----------:|-----------:|---------:|
| Donuts  | A lot     | More      | none        |
| Carrots | none      | no much   | a couple    |


Este seria el comando

```
| Food    |   Facts   | Carbs  | Proteins       |

|---------|:-----------:|-----------:|---------:|

| Donuts  | A lot     | More      | none        |

| Carrots | none      | no much   | a couple    |
```




[Index](#Comandos)

# Colors for font
<span style="color:blue">some **Blue** text</span>.

<span style="color:red">some **Red** text</span>.

<span style="color:yellow">some **Yellow** text</span>.

Para colores usamos comando de HTML porque MD no tiene como hacerlo

`<span style="color:blue">some *blue* text\</span>`

o podemos hacer esto para darle color

`color`

**\`color`**

[Index](#Comandos)

# Inlining Code
Para hacer un comando en una sola linea

`sudo apt update`

\`sudo apt update`

[Index](#Comandos)

# Creating Block of Code
Para crear un bloque de tesxt oes bien sencillo solo tenemos que usar el sig no \`\`\`  es la tecla que esta arriba del \<tab> y cerrarlo tambien de la misma manera

Otra cosa que podemos hacer que podemos decirle que tipo de lenguaje que vamos a usar en el mismo y nos va dar el highlight que usa ese lenguaje.
\```bash codigo que vamos a usar y al final le ponemos los tres para cerrarlos 
```php

<?php
echo "hello"
?>

Lo hacemos asi

```php
<?php
echo "hello"
?>

\```
sin el \ backslash
```
# Creating a Task List
Groceries:

[X] Carrot

- [x] Baby Carrot 

[x]  Bread

[ ] Ice Cream

[ ] Steak

```
# Creating a Task List
Groceries:

[x] Carrot   

 - [x] Baby Carrot 

[ ] Bread

[ ] Ice Cream

[ ] Steak

```

[Top of Document](#Comandos)
