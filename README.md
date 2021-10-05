# HTML-Next-Steps-Semantics
> HTML: Next Steps & Semantics
> 
> Inline Elements vs Block Elements
>
**Inline elements: fit in alonside other elements**
**Block level element: take up a whole "block" of space**


**Generic Containers:**

- Content Division Element: (BLOCK ELEMENTS)

```<div></div>``` - allow to group content together and style it all at once. **Pl:** Tigris és alatta szöveg.

- Span: (INLINE ELEMENTS)

```<span></span>``` - allow to group content together and style it all at once. **Pl:** Redditen a Media,Discussion,Question fül.
&nbsp;
>
> HTML: Next Steps & Semantics
>
**The Thematic Break element:(Horizontal Rule)**

```<hr>``` - doesn't have closing tag. represents a thematic break between paragraph-level elements. Pl: egy sztori vége,topic vége stb..

**The Line Break element:**

```<br>``` - doesn't have closing tag, make a line break. Pl: versnél,címnél(address)


**The Superscript element:**

```<sup></sup>``` - négyzetre emelés


**The Subscript element:**

```<sub></sub>``` - lentre "emelés"
&nbsp;
>
> HTML: Next Steps & Semantics
> 
> Entity Codes
> 
**Website:** https://dev.w3.org/html5/html-author/charref

- start with an ampersand & and end with a semicolon ;

- used to display reserved or difficult characters

**Pl:**
CopyRight jel: ```&copy;```

< greater then : ```&lt;``` 

less than : ```&gt;```

&nbsp;
>
> HTML: Next Steps & Semantics
>
> Semantic Markup - too much ```<dev></dev>``` !!
>
&nbsp;
"What purpose or role does that HTML element have?"

**Pl:** Use more specific elements like:
```
<section></section>
<footer></footer>
<nav></nav> 
<article></article>
<main></main>
<header></header>
<aside></aside>
<summary></summary>
<details></details> 
```
&nbsp;
>
> HTML: Next Steps & Semantics
>
> VSCode Tool - Emmet
>

**Website** - https://docs.emmet.io/cheat-sheet/


**nav>ul>li =**
```
<nav> 
    <ul> 
        <li></li> 
    </ul> 
</nav> 
```
**ul>li*5 =**
```
<ul> 
    <li></li> 
    <li></li>
    <li></li> 
    <li></li> 
    <li></li> 
</ul> 
```
**ul>li.item$x5 =**
```
<ul> 
    <li class="item1"></li> 
    <li class="item2"></li> 
    <li class="item3"></li> 
    <li class="item4"></li> 
    <li class="item5"></li> 
</ul>  
```
