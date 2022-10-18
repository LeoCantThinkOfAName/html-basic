# Anatomy
> ![CSS Anatomy](/images/css_anatomy.png)
> [MDN](https://developer.mozilla.org/zh-CN/docs/Learn/Getting_started_with_the_web/CSS_basics)
```CSS
body {
    background: ivory;
}
```

# Selector
```CSS
/* all */
* {
    font-size: 16px;
}

/* tag */
div {
    background: pink;
}

/* class */
.red-section {
    background: red;
}

/* id */
#green-section {
    background: green;
}

/* attribute */
[role=dialog] {
    background: yellow;
}
```

# List
```CSS
.list-1, .list-2 {
    background: purple;
}
```

# Combinator
```CSS
/* Descendant */
div h1 {
    background: red;
}

/* Child */
div > h1 {
    background: red;
}

/* Sibling */
div ~ h1 {
    background: red;
}

/* Adjecent Sibling */
div + h1 {
    background: red;
}
```

# Pseudo Selector
```CSS
/* Class */
div:hover {
    background: red;
}

/* Element */
div::before {
    content: 'pseudo element';
}
```

# Specificity
ID - CLASS - TYPE

```CSS
[type="password"]             /* 0-1-0 */
input:focus                   /* 0-1-1 */
:root #myApp input:required   /* 1-2-1 */

/* Example from MDN */
```
- inline style
- `!important`

# Appendix
- [CSS Selectors](https://developer.mozilla.org/zh-TW/docs/Web/CSS/CSS_Selectors)
- [Pseudo Class](https://developer.mozilla.org/zh-TW/docs/Web/CSS/Pseudo-classes)
- [Pseudo Element](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)
- [Specificity](https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity)
