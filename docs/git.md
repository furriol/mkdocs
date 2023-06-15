---
titlepage: true
titlepage-background: "img/background5.pdf"

page-background: "img/marca.png"
page-background-opacity: [0.20]

title: Prueba de Pandoc
subtitle: Prueba de Pandoc
author: 
- Alejandro Furriol

titlepage-rule-height: 45
titlepage-rule-color: 673097
toc-own-page: true
toc-title: Continguts

header-left: "Prueba Pandoc"
header-right: Curs 2021-2022

footer-left: CEFIRE Valéncia
footer-right: \thepage


toc-depth: 2


header-includes:
 - \usepackage{awesomebox}

pandoc-latex-environment:
    noteblock: [note]
    tipblock: [tip]
    warningblock: [warning]
    cautionblock: [caution]
    importantblock: [important]



---

# Punto 1

:smile: 
:smile: 
:smile: 
:smile: 
:smile: 


Text can be {--deleted--} and replacement text {++added++}. This can also be
combined into {~~one~>a single~~} operation. {==Highlighting==} is also
possible {>>and comments can be added inline<<}.

{==

Formatting can also be applied to blocks by putting the opening and closing
tags on separate lines and adding new lines between the tags and the content.

==}


[Pincha para más información](https://www.google.es){ .md-button }


!!! tip

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

??? abre para ver la nota
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! info inline end "Lorem ipsum"

    Lorem ipsum dolor sit amet, consectetur
    adipiscing elit. Nulla et euismod nulla.
    Curabitur feugiat, tortor non consequat
    finibus, justo purus auctor massa, nec
    semper lorem quam in massa.


***Hola esto es un párrafo***

::: note
Anotació: Lorem ipsum dolor sit amet, consectetur.
    Mauris pellentesque justo sit amet urna aliquam, dictum egestas felis
    dapibus.
:::

::: tip
Consell: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris
pellentesque justo sit amet urna aliquam, dictum egestas felis dapibus.
:::

::: warning
Avís: Si poses `string` en compte de `String` en donarà molts **problemes
**. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris
pellentesque justo sit amet urna aliquam, dictum egestas felis dapibus.
:::

```java
    public class HelloWorld {
        public static void main(String[] args) {
            System.out.println("Hello, World!");
        }
    }
```


# Punto 1.1

# Punto 2

Hola esto es un párrafo

# Punto 3

Hola esto es un párrafo

## Punto 3.1

Hola esto es un párrafo

### Punto 3.1.1

Hola esto es un párrafo





