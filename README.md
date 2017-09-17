# Notes: How to Markdown

This is the notes / exercise taken for the tutorial on nodeschool.io title how-to-markdown. It's also an attempt to use markdown on GitHub.

## Table of Contents
* [Headings](#headings)
* [Emphasis](#emphasis)
* [Lists](#lists)
* [Links](#links)
* [Images](#images)
* [BlockQuotes](#blockquotes)
* [Code](#code)
* [Tables](#tables)
* [Horizontal Rules](#horizontalrules)
* [HTML](#html)

<a name="headings" />

## 1. Headings

```
# Markdown is awesome!
## This is h2
### This is h3
#### This is h4
##### This is h5
###### This is h6

There are 6 level of headings just like HTML

There are aliases for heading one and heading 2

Put 3 equals sign under this to turn this into heading 1
===

Put 3 dash/hyphen usder this to turn this into heading 2
---
```

# Markdown is awesome!
## This is h2
### This is h3
#### This is h4
##### This is h5
###### This is h6

There are 6 level of headings just like HTML

There are aliases for heading one and heading 2

Put 3 equals sign under this to turn this into heading 1
===

Put 3 dash/hyphen usder this to turn this into heading 2
---

<a name="emphasis" />

## 2. Emphasis

```

* Italic: One _ or * is for italic
* Bold: Two _ or * is for bold
* Combined: You can combine this 2 for bold + italic effects.

It's very easy to use _italic_, **bold** and _**combined**_ emphasis in Markdown!

```


* Italic: One _ or * is for italic
* Bold: Two _ or * is for bold
* Combined: You can combine this 2 for bold + italic effects.

It's very easy to use _italic_, **bold** and _**combined**_ emphasis in Markdown!



<a name="lists" />

## 3. Lists

```

- One
    - 1.1
    - 1.2
- Two
    - 2.1
    - 2.2
- Three
- Four
- Five

1. Hell
2. Yeah

```

- One
    - 1.1
    - 1.2
- Two
    - 2.1
    - 2.2
- Three
- Four
- Five

1. Hell
2. Yeah

<a name="links" />

## 4. Links

```
[how-to-markdown] is a workshopper that teaches you how to write Markdown.

[how-to-markdown]: //git.io/how-to-markdown

## There are 2 types of linking in Markdown

1. Inline style

    **formula** : [text](href "alt")


[Google](https://www.google.com)

2. Reference style

//This keyword is just a variable
[Google] is a search engine

//This will replace what's up there
[Google]: https://www.google.com

```

[how-to-markdown] is a workshopper that teaches you how to write Markdown.

[how-to-markdown]: //git.io/how-to-markdown

## There are 2 types of linking in Markdown

1. Inline style

    **formula** : [text](href "alt")

```
[Google](https://www.google.com)
```
2. Reference style

```
//This keyword is just a variable
[Google] is a search engine

//This will replace what's up there
[Google]: https://www.google.com

```

<a name="images" />

## 5. Images

```
1. How to embed images in Markdown??
    The formula is just like writing links but with a exclamation mark infront

![Markdown logo](http://bit.do/how-to-markdown)
```

1. How to embed images in Markdown??
    The formula is just like writing links but with a exclamation mark infront

![Markdown logo](http://bit.do/how-to-markdown)

<a name="blockquotes" />

## 6. BlockQuotes

```
* Add a ">" infront of a paragraph to make it a blockquotes

> To be, or not to be, that is the question.
> William
```

* Add a ">" infront of a paragraph to make it a blockquotes

> To be, or not to be, that is the question.
> William

<a name="code" />

## 7. Code

3 backticks will allow us to write code.
Add a js behind the 3 backticks to indicate that this is a JS code so the formatter for format accordingly

```js
const add = (a, b) => a + b;
```

<a name="tables" />

## 8. Tables

```
* Drawing tables in Markdown is just like drawing
* You dont actually need all those dashes in between the pipe, you need a minimum of **3**
* You can left-aligned, center or right-aligned the text in each table column
    * :--:   this is center
    * ---    no colon is left-aligned
    * ---:   have a colon at the right hand side is right-aligned

| Year | World population |
| :--: | --------------- |
| 1960 | 3 Billion       |
| 1980 | 4 Billion       |
| 2000 | 6 Billion       |

```

* Drawing tables in Markdown is just like drawing
* You dont actually need all those dashes in between the pipe, you need a minimum of **3**
* You can left-aligned, center or right-aligned the text in each table column
    * :--:   this is center
    * ---    no colon is left-aligned
    * ---:   have a colon at the right hand side is right-aligned

| Year | World population |
| :--: | --------------- |
| 1960 | 3 Billion       |
| 1980 | 4 Billion       |
| 2000 | 6 Billion       |


<a name="horizontalrules" />

## 9. Horizontal Rules

* There are 3 ways to underline in md
```
 1. ***
    2. ___
    3. --- (Remember we said before 3 dashed below some text will make it Heading1? Use this with a space in between the text.)
```

<a name="html" />

## 10. HTML

```
* You can insert html just like what you used to, but be careful because the markdown in the HTML tags will not be rendered.

<p align="center">HTML in Markdown</p>
```


* You can insert html just like what you used to, but be careful because the markdown in the HTML tags will not be rendered.

<p align="center">HTML in Markdown</p>

<a name="gfm" />